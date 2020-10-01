# Setting Up SSH Key
An SSH key is an access credential. Its function is primarly used for automated process and for implementing single sign-on by system administrators and power users. 

## Checking for Existing SSH Keys
It is recommended to check for existing SSH keys before adding a key.
1. Open Git Bash from the Windows Start menu.
2. Enter `ls -al ~.ssh` in the command line and press return.
If any files exist, the `ls` command shows the files in your directory.
3. Verify the directory listing to see if you already have a public SSH key.

The following example, the command returned no existing SSH key files. You will need to generate an SSH key and the add it to the SSH agent.

IMAGE HERE

## Generating a New SSH Key
If you don't want to reenter a password every time you use your SSH key, you must add your key to an SSH agent. The SSH agent manages SSH keys and remembers your passwords.
1. Open Git Bash.
2. Enter the following test and substitute your email address: `$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
This command generates a new SSH key, using the email address as a label.
3. Press **enter** when prompted to **Enter a file in which to save the key**. This accepts the default file location.
4. Enter a secure passphrase when prompted.
>:bulb: If you do not want a passphrase associated with the SSH key, leave the passphrase field empty by pressing enter. Press enter again when prompted again to enter a  passphrase.

IMAGE HERE




...

Congratulations! You have successfully set up SSH key for use with the GitHub repository.

## Resources
The following are extra resources to help you through the installation process. 
1. About SSH: <br> https://docs.github.com/en/enterprise/2.15/user/articles/about-ssh 
2. Checking for SSH Key: <br> https://docs.github.com/en/enterprise/2.15/user/articles/checking-for-existing-ssh-keys
3. Generating a New SSH Key: <br> https://docs.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

