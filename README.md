# Security6

first we have to login , then a token will be generated ,using this token we can access the permitted api according to the respected roles of the user.



#the way to login

{
    "email":"su@gmail.com",
    "password":"su@123"
}



#The way to register user in postman using the bearer token (only the admin,super admin can do CRUD operations on the user)

{
    "userRoles": {
        "roleId": 2,
        "rolePermissions": [
            {
                "permissionId": 2,
                "permissionType": "Write"
            },
            {
                "permissionId": 3,
                "permissionType": "Update"
            },
            {
                "permissionId": 4,
                "permissionType": "Delete"
            }
        ],
        "roleName": "Admin",
        "roleDescription": "Admin role for the project who have most of the access"
    },
    "email":"shubh@gmail.com",
    "password":"shubh123",
    "status":true,
    "username":"ShubhSingh",
    "updatedBy":"Admin",
    "fullname":"Shubh kr. Singh"
}



