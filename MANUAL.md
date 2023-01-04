# Blue Reflection Minecraft Skins Pack Manual

## Download Skins Pack for PC

### GUI method
This is the easiest way to download the skin images on the PC's disk. Recommended only if you just want to download the skins once.

* Step 1: Click on the **Code** button from the code section of the repository
* Step 2: Click on the **Download ZIP** option to save a compressed file of the project on your PC's Downloads folder
* Step 3: Uncompress the ZIP file and move the folder to your favorite location.

![DownloadPCgui](/src/img/manual/DownloadPCgui.png)

### Command Line method

***Note: this option requires you to have a GitHub account!***

This way is more complex and intended for those users who have programming knowledges or knowledges using the Git Bash or a command line terminal. Recommended if, in addition to download the skins, you want to receive future updates from my repository without the need to download a ZIP file every time.

**Step 1: Install Git**
1. First of all, you'll need to install Git on your computer. Here you can download [Git](https://git-scm.com/downloads). Just follow the instructions according to your Operative System.

**Step 2: Generate a personal access token**

Due to changes in GitHub's policies, you cannot use anymore Git commands with your GitHub password as authentication. So, in their place you must generate a token for your GitHub acount.

1. After installing Git on your PC, in your GitHub account you've to generate a personal access token (PAT). For that, go to your **Setting --> Developer setting --> Personal access tokens** and click on the button **Generate new token**.

![DownloadPCtoken](/src/img/manual/DownloadPCtoken.png)

2. Give that token a descriptive name, set the expiration time and select the permissions you want (for this project, is enough with _repo_ permissions). Click the green button **Generate token**.
3. Next, copy the token generated to your clipboard or an auxilar plaintext file. ***Caution: you must save temporarily that token, or you won't be able to see it again!***

For more information and references, read the GitHub docummentation about [this topic](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

**Step 3: Setting up the keychain of your PC to GitHub**
1. Open the Git Bash terminal (only Windows) or your Terminal application (MacOS and Ubuntu).
2. Type in the command line `git config --global credential.helper manager` (Windows) or `git config --global credential.helper osxkeychain` (MacOS) to associate the keychain in your PC to your GitHub account the next time you loggin via the Git bash or terminal. This is useful because you'll only have to type your username and token the first time you want to clone, pull or push a remote (internet) repository.

For more information about linking your keychain to GitHub, read these two pages:
- [Storing Git Credentials with Git Credential Helper](https://techexpertise.medium.com/storing-git-credentials-with-git-credential-helper-33d22a6b5ce7)
- [How to use Mac KeyChain to store GitHub repos credentials?](https://gist.github.com/nepsilon/0fd0c779f76d7172f12477ba9d71bb66)

**Step 4: Cloning (downloading) the _Blue Reflection Minecraft Skins Pack_ repository in your local disk**
1. In the Git Bash use de `cd` command to change your current directory (folder) to an specific directory on your PC (e.g. `cd C:/users/YOUR_USER/Desktop` or just `cd Desktop` if the bash is currently in your user's folder).
2. In the GitHub repository, click on the **Code** button from the code section of the repository.
3. In the HTTPS section, copy the url to your clipboard.

![DownloadPCurl](/src/img/manual/DownloadPCurl.png)

4. Type the command `git clone URL`, where URL is the link copied in the previous step, in the Git Bash and press Enter.
5. The first time, you've to enter the following information:

	**Username:** *your GitHub username* (which is in the url of your GitHub page. E.g. https://github.com/alvarvelazquezdeleonlavarrios --> `alvarvelazquezdeleonlavarrios`)

	**Password:** *your personal access token* (generated and saved previously in your GitHub account)

6. After few seconds, you should see a new folder named *Blue-Reflection-Minecraft-Skins-Pack* in the directory you performed the `clone` command. This folder contains the project files (skins) and the repository itself. In addition, your username and password (token) are now stored in the keychain of your computer.

The next time you perform an operation with Git commands, isn't necessary to enter again the username and password, unless the token has a limited expiration time.

7. Finally, you can move the folder to your favorite location, but consider that your current Git Bash directory doesn't exist anymore.

## Download Skins Pack for Mobile?
Unfortunately, there is no direct and safety way to dowload the entire pack to your mobile device (iOS or Android).

Actually, there are two simple but inefficient methods to download the skins on a mobile phone or tablet:

1. Searching the repository via your mobile's browser application, and download each PNG file separately saving them in your photos application.
2. Having a PC, transfer the PNG files to your phone or tablet via USB (or AirDrop if you have Apple devices).

## Update the Skins Pack (Only for PC and Command Line)
If you want to have the most recent files in your skins folder, you must perform the following steps to update from the remote repository:

1. Open the Git Bash application (or Terminal in MacOS and Ubuntu).
2. Change the directory with the `cd` command to the *Blue-Reflection-Minecraft-Skins-Pack* folder path.
3. Type the command `git pull` to ***update the skins pack***.
4. Finally, enjoy the new changes. Remember you can check if there are new skins added to the pack in the main page of the repository in GitHub (check the README.md).

## Apply a Blue Reflection skin to your Minecraft player

### PC versions (Java, Bedrock and Windows Editions)
The process is the same as with other custom skins:

1. Launch Minecraft on your computer
2. Select **Dressing Room under** your current character
3. Select the menu button at the top-left of the screen for more options, and then select **Classic Skins**.
4. Select the blank skin model under **Owned Skins**, and then select **Choose New Skin**.
5. Upload a custom skin from the *Blue-Reflection-Minecraft-Skins-Pack* folder, and then make sure that it appears as expected on the character model, checking the body type (classic or slim) of your character.

### Mobile version (Pocket Edition)
The process for Mobile devices is the same as for PC, but the skin files must be allocated in the **photos application** of your mobile phone or tablet.

![MinecraftHinako](/src/img/manual/MinecraftHinako.png)

![MinecraftCustomSkin](/src/img/manual/MinecraftCustomSkin.png)
