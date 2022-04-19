# GoogleWorkspace
Here I will collect by tips&tricks&scripts related to GoogleWorkspace

## Getting audit logs via API
Google provides limited access to logs via GUI. Some simple questions like "who used SMS auth to login?" can't be answered using Workspace GUI. 
Some reports (e.g., suspicious logins, leaked passwords) are also easier to get via API. 
Google API is very complex thing. It based on OAuth2.0 -> no easy way to get logs using a python script. Postman tool helped me here to automate most of the things, but still its "semi-manual" work. If you know how to do that via Python - please let me know!
Prerequisits:
- super admin access to Workspace / GApps
- download and install Postman tool

### Google Cloud platform
1. Go to https://console.cloud.google.com/apis/dashboard 
2. Enable "Admin SDK API"
<img width="696" alt="image" src="https://user-images.githubusercontent.com/5716798/163975203-5086dd0b-12ff-4261-b5d3-aa4c129156b2.png">
3. Open "Credentials" and add new OAuth 2.0 credentials
![image](https://user-images.githubusercontent.com/5716798/163975611-9efd192c-9f34-47ac-a0b3-1dcca10d0ce4.png)




### Using Postman


### Links
1. StackOverflow page on using Postman with Google API https://stackoverflow.com/questions/32076503/using-postman-to-access-oauth-2-0-google-apis
2. Google's documentation on login events https://developers.google.com/admin-sdk/reports/v1/appendix/activity/login
