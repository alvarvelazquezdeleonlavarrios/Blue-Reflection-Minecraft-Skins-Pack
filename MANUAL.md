# Blue Reflection Minecraft Skins Pack Manual

## Downloading Pack for PC

### GUI method
This is the easiest way to download the source skins images on your PC's disk. Recommended only if you want to download the skins pack once.

* **Step 1**: Go to the [main page](https://github.com/alvarvelazquezdeleonlavarrios/Blue-Reflection-Minecraft-Skins-Pack) of this repository
* **Step 2**: Click on the **Code** button from the code section of the repository
* **Step 3**: Click on the **Download ZIP** option to save a compressed file of the project on your PC's Downloads folder
* **Step 4**: Unzip the ZIP file and move the folder to your favorite location.

![DownloadPCgui](/src/img/manual/DownloadPCgui.png)

### Command Line method

***Note: this option requires you to have a GitHub account!***

This way is more complex and intended for those users who have programming knowledges using the Git Bash or a command line terminal. Recommended if, in addition to download the skins, you want to receive future updates from the repository without the need to download a ZIP file every time.

**Step 1: Install Git**
1. First of all, you'll need to install Git on your computer. Here you can download [Git](https://git-scm.com/downloads). Just follow the instructions according to your Operative System.

**Step 2: Generate a personal access token**

Due to changes in GitHub's policies, you cannot use anymore Git commands with your GitHub's account password as authentication. So, in their place you must generate a token for your GitHub account.

1. After installing Git on your PC, in your GitHub account you've to generate a personal access token (PAT). For that, go to your **Setting --> Developer setting --> Personal access tokens** and click on the button **Generate new token**.

![DownloadPCtoken](/src/img/manual/DownloadPCtoken.png)

2. Give that token a descriptive name, set the expiration time and select the permissions you want (for this project, is enough with _repo_ permissions). Click on the green button **Generate token**.
3. Next, copy the token generated to your clipboard or an auxilary plaintext file. ***Caution: you must save temporarily that token, or you won't be able to see it again!***

For more information and references, read the GitHub documentation about [this topic](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

**Step 3: Setting up your PC's keychain to GitHub**

***Note: you’ll want to do this step only once if this is your first time using Git on your computer.***

1. Open the Git Bash terminal (only Windows) or your CMD/Terminal application (Windows, MacOS and Ubuntu).
2. Type in the command line `git config --global credential.helper manager` (Windows) or `git config --global credential.helper osxkeychain` (MacOS) to associate the keychain of your PC to your GitHub account the next time you login via Git bash or Terminal. This is useful because you'll have to type your username and token only the first time you want to clone, pull or push a remote (web) repository.

For more information about linking your PC's keychain to GitHub, read these useful two pages:
- [Storing Git Credentials with Git Credential Helper](https://techexpertise.medium.com/storing-git-credentials-with-git-credential-helper-33d22a6b5ce7)
- [How to use Mac KeyChain to store GitHub repos credentials?](https://gist.github.com/nepsilon/0fd0c779f76d7172f12477ba9d71bb66)

**Step 4: Cloning (downloading) the _Blue Reflection Minecraft Skins Pack_ repository in your local disk**
1. In the Git Bash use de `cd` command to change your current directory (folder) to a specific directory on your PC (for example, `cd C:/users/YOUR_USER/Desktop` or just `cd Desktop` if the bash is currently running in your user's folder).
2. In the GitHub's repository [main page](https://github.com/alvarvelazquezdeleonlavarrios/Blue-Reflection-Minecraft-Skins-Pack), click on the **Code** button from the code section of the repository.
3. In the HTTPS section, copy the URL to your clipboard.

![DownloadPCurl](/src/img/manual/DownloadPCurl.png)

4. Type in the Git Bash the command `git clone URL`, where URL is the link copied in the previous step. Press Enter.
5. The first time, you'll have to enter the following information:

	**Username:** *your GitHub username* (which is in the url of your GitHub page. For example: https://github.com/alvarvelazquezdeleonlavarrios --> `alvarvelazquezdeleonlavarrios`)

	**Password:** *your personal access token* (generated and saved previously in your GitHub account)

6. After few seconds, you should see a new folder named *Blue-Reflection-Minecraft-Skins-Pack* in the directory you performed the `clone` command. This folder contains the skins (PNG files), another project files and the repository itself (.git hidden file). In addition, your username and password (token) are now stored inside your PC's keychain.

The next time you perform an operation with Git commands, isn't necessary to enter again the username and password, unless the token has a limited expiration time.

7. Finally, you can move the folder *Blue-Reflection-Minecraft-Skins-Pack* to your favorite location, but consider that your current Git Bash path doesn't exist anymore.


### Updating the Skins Pack (PC and Command Line Only)
If you want to receive skins for new or existing characters in your pack folder, you must perform the following steps to update your local folder with the new changes from the remote repository:

1. Open the Git Bash application (or CMD/Terminal in Windows, MacOS and Ubuntu).
2. Change the directory with the `cd` command to the *Blue-Reflection-Minecraft-Skins-Pack* folder path.
3. Type the command `git pull` to ***update the skins pack***.
4. Finally, enjoy the new feastures! Remember you can check whether there are new updates on the pack visiting the repository's [main page](https://github.com/alvarvelazquezdeleonlavarrios/Blue-Reflection-Minecraft-Skins-Pack), reading the latest commit's description or checking from GitHub each **markdown** file inside the *src* directory for each skins folder (BlueReflection.md, BlueReflectionRay.md, Costumes.md, etc.).


## Downloading Pack for Mobile Devices
Unfortunately, there is no a direct and safety way to download the entire pack to your mobile device (iOS or Android).

Currently, there are two simple but inefficient methods to download the skins on a mobile phone or tablet:

* **Method 1**: Searching the repository via your mobile's web browser application, and downloading each PNG file separately saving them in your photos application.
* **Method 2**: Having a PC, transfer the PNG skins images to your phone or tablet via USB (or AirDrop if you have Apple devices).


## Applying Skins to your Minecraft's Character

### PC Versions (Java and Bedrock Editions)
For Java Edition:

1. Open the Minecraft Launcher.
2. Select the Java Edition from the left window.
3. Select the **Skins tab**.
4. Click on **Add New Custom Skin**.
5. Upload a custom skin from the *Blue-Reflection-Minecraft-Skins-Pack* folder, and then make sure that it appears as expected on the character model, checking the body type (classic or slim) of your character.
6. Save the changes.

For Bedrock Edition:

1. Open the Minecraft Launcher.
2. Select the Bedrock Edition from the left window.
3. Click on **Play**.
4. Inside the game, select **Dressing Room** under your current character
5. Select the menu button at the top-left of the screen for more options, and then select **Classic Skins**.
6. Select the blank skin model under **Owned Skins**, and then select **Choose New Skin**.
7. Upload a custom skin from the *Blue-Reflection-Minecraft-Skins-Pack* folder, and then make sure that it appears as expected on the character model, checking the body type (classic or slim) of your character.


### Mobile Version (Pocket Edition)
The process for Mobile devices is the same as for PC's Bedrock Edition, but skipping the Minecraft Launcher step and making sure the skin files must be allocated in the **photos application** of your mobile phone or tablet.

![MinecraftHinako](/src/img/manual/MinecraftHinako.png)

![MinecraftCustomSkin](/src/img/manual/MinecraftCustomSkin.png)
