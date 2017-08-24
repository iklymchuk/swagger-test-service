# User test service

### Paths
**/user**
![alt get-user](https://content.screencast.com/users/Klimchuk/folders/Jing/media/c8e34d0e-f600-4875-a2e8-466abd0cef8d/2017-08-24_1753.png)
![alt post-user](https://content.screencast.com/users/Klimchuk/folders/Jing/media/1c17083b-4008-4bb8-af46-e7e1d47273e6/2017-08-24_1756.png)

**/user/{id}**
![alt get-userid](https://content.screencast.com/users/Klimchuk/folders/Jing/media/fb1f97c2-c975-4719-beaa-50271e58afcd/2017-08-24_1757.png)
![alt put-userid](https://content.screencast.com/users/Klimchuk/folders/Jing/media/0389500f-7ea0-474e-952b-8eda2f1633a4/2017-08-24_1758.png)
![alt delete-userid](https://content.screencast.com/users/Klimchuk/folders/Jing/media/4158279b-7629-44e3-a334-369b22640a96/2017-08-24_1759.png)

**Models**

GetUsersListResponse
⇄	
GetUsersListResponse {
users:	
[]
}

GetUserResponse
⇄	
GetUserResponse {
id:	
string *
username:	
string *
password:	
string *
}

User
⇄	
User {
username:	
 string *
password:	
 string *
}

GeneralResponse
⇄	
GeneralResponse {
success:	
 number *
description:	
 string *
}

ErrorResponse
⇄	
ErrorResponse {
message:	
string *
}
