## Disable built-in Administrator account on Windows Server
### About
Disabling the built-in Administrator account on Windows Server is often considered a security best practice
1. Open Computer Management
2. Navigate to Local Users and Groups -> Users
3. Right click or click on Action / More Actions
4. Select `New User`
![image](https://github.com/iamfabo/windows/assets/60046736/337e3388-7988-46a0-830d-33635fcafde4)
5. Set a new name and password\
![image](https://github.com/iamfabo/windows/assets/60046736/c2ffa788-be3d-4324-9736-c049e9888a7d)
6. Navigate to Local Users and Groups -> Groups
7. Right click on Administrators and select `Add to Group`
![image](https://github.com/iamfabo/windows/assets/60046736/332d094f-4ba5-4188-9d55-39cbe36a0fb6)
8. Click on Add and enter the name of the newly created user to add them to the Administrators group\
![image](https://github.com/iamfabo/windows/assets/60046736/9bd59973-5652-4448-933a-9bc482a43dc9)
9. Navigate to Local Users and Groups -> Users
10. Right-click on Administrator and select Properties
11. Check the box on `Account is disabled`, confirm and log out\
![image](https://github.com/iamfabo/windows/assets/60046736/1e7ecced-8c33-4039-9793-a7a7eea20407)
### Result
The built-in administrator account should no longer be available, instead the newly added account will be displayed on the login screen\
![image](https://github.com/iamfabo/windows/assets/60046736/83d490bc-c372-454a-8601-0f96aea42bcf)
