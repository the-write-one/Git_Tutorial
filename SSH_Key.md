# Setting Up SSH Key
An SSH key is an access credential. Its function is primarily used for automated processes and implements a single sign-on (SSO) by system administrators and power users. This short tutorial includes user screenshots and follows the method found [here](https://docs.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## Checking for Existing SSH Keys
Check for existing SSH keys before adding a key.
1. Open Git Bash from the Windows Start menu.
2. Enter `ls -al ~.ssh` in the command line and press return.
If any files exist, the `ls` command shows the files in your directory.
3. Verify the directory listing to see if you already have a public SSH key.

In the following example, the command returned no existing SSH key files. You will need to generate an SSH key and then add it to the SSH agent.

<img src="/images/Check_Existing_SSH_Key.png" width="400"/>

## Generating a New SSH Key
If you don't want to reenter a password every time you use your SSH key, you must add your key to an SSH agent. The SSH agent manages SSH keys and remembers your passwords.
1. Open Git Bash.
2. Enter the following test and substitute your email address: `$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`.
The command generates a new SSH key, using the email address as a label.
3. Press **enter** when prompted to **Enter a file to save the key**. This action accepts the default file location.
4. Enter a secure passphrase when prompted.
>:bulb: If you do not want a passphrase associated with the SSH key, leave the passphrase field empty by pressing enter. Press enter again when prompted again to enter a  passphrase.

<img src="images/Create_SSH_Key.png" width="400"/>

## Adding Your SSH Key to the SSH-Agent
Git Bash is a recommended way of running `git` commands on Windows. GitHub Desktop can also clone repositories and is a workaround for not having to deal with SSH keys.
1. Verify the SSH-Agent is running by entering the following command:
```
# start the ssh-agent in the background
$ eval $(ssh-agent -s)
> Agent pid 59566
```
2. Add your SSH private key to the SSH-agent.
`$ ssh-add ~/.ssh/id_rsa`
> :bulb: If you created your key with a different name, or are adding an existing key that has different name, replace id_rsa in the command with the name of your private key file.
3. Add the SSH key to your GitHub account. (If you do not have a GitHub account, you will need to create one.)
4. Start the SSH-agent in the background.
5. Add your SSH private to the SSH-agent.

<img src="images/Adding_SSH_Key_to_SSH_Agent.png" width="400"/>


...

Congratulations! You have successfully set up SSH key for use with the GitHub repository.

## Resources
The following are extra resources to help you through the installation process. 
1. About SSH: <br> (https://docs.github.com/en/enterprise/2.15/user/articles/about-ssh)
2. Checking for SSH Key: <br> https://docs.github.com/en/enterprise/2.15/user/articles/checking-for-existing-ssh-keys
3. Generating a New SSH Key: <br> https://docs.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

