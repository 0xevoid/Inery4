## Preparation before running task 4

1. ##### Github Accounts

2. ##### Github tokens

3. ##### Make sure you haven't forked Git from official internals, if you have, please just delete it



## 1. Preparation

1. ##### Register [Github](https://github.com/) Account

2. ##### Create a Github Token

    1. Click [this link](https://github.com/settings/tokens) to generate github token
    2. Select the **"Generate new token"** button
    3. Select **generate new token (classic)** and enter the name of the token, **example** "access-inery-token"
    Check the scopes option below

       ✓ **repo**

       ✓ **workflow**

       ✓ **admin:org**
      
    4. Then press the **Generate Token** button at the bottom
    5. **Save your tokens carefully**

## 2. Doing Task 4

1. ##### Run the command below to do task 4 automatically

    ```shells
    wget --no-check-certificate --no-cache --no-cookies -q -O task4.sh https://raw.githubusercontent.com/0xevoid/Inery4/main/task4.sh && chmod +x task4.sh
    ```

2. ##### Run the code below to start running the task

    ```shells
    ./task4.sh
    ```

    Enter the requested details

3. ##### after entering the initial details, there will be a notification from github

    **"? What account do you want to log into?"**

    1. Select **GitHub.com** , enter
    2. Select **HTTPS** enter
    3. Type **Y** when asked, enter
    4. Select **Paste an authentication token** , enter
    5. Paste the token that you generated in the first step, enter

4. ##### Done, just wait, task 4 is completed!!!!
