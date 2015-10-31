# PassVault
Password remembrance application.

This project is under developpement.

The application will use a database of encrypted passwords, which will then make a request to the server to acquire the key. Once this is completed, the application receives the encrypted password and the key; it then processes the password and destroyes the key. The key is always kept in the server, so if you lose your phone, you're ok.

# General Rules

1. To create a new activity, don't name it (main, upper, login). Name it something meaningful
   Ex : LoginRequest, PasswordList, DatabaseAccess etc. (no underscore "_" no hyphen "-" no space " ")
2. Layout files (.xml) files should have the same name of their respective activity without capital and words seperated with underscores and always start with "activity_" and  ends with "_layout"
   Ex : activity_login_request_layout, activity_password_list_layout, activity_database_access_layout.
3. More comments are always welcome. We will not confirm your pull request if you didn't properly commented your work.

Application being developped by : Alexandre Boyer and Alexandre Séguin.
