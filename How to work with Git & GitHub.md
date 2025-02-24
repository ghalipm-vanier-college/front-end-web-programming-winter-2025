# How to work with Git & GitHub

Here are what steps you need to take to work with Git, GitHub, and GitHub Classroom:

1. Create a folder on your desktop, rename it to "Labs" and open up the command prompt (terminal).
2. Type in "cd " and drag and drop the folder you just created to the terminal window.
3. Then, type in "git clone <URL-to-repo>" and add your URL to the repository.
4. Now type in "cd " again and drag and drop the folder you just cloned to the terminal window. Leave this window open.
5. Do the assignment!
6. Once you are done, go back to the terminal window and type in "git status" to see what files need to be staged. The files will be in red.
7. Next, type in "git add ." to stage all files.
8.  Type in "git status" once again to see they are staged. The files should be green now.
9.  Next, type in "git commit -m "<YOUR-COMMENT>"" to commit the changes.
10. And lastly, type in "git push" to push your code to the remote repository on GitHub.
11. Now you can go to your GitHub repository page to check your resutls.

### **How to Install Git on Windows**  

#### **Step 1: Download Git for Windows**  
1. Go to the official Git website:  
   👉 [https://git-scm.com/downloads](https://git-scm.com/downloads)  
2. Click **"Download for Windows"** – It will automatically detect your Windows version (64-bit/32-bit).  
3. Once the installer (`.exe` file) is downloaded, open it.  

---

#### **Step 2: Install Git**
1. **Run the installer** and follow the setup wizard.  
2. **Choose the installation location** (default is `C:\Program Files\Git`). Click **Next**.  
3. **Select components** (leave default selections unless you need specific options). Click **Next**.  
4. **Choose default editor** (Select **Notepad++**, **VS Code**, or **Vim**). Click **Next**.  
5. **Adjust PATH environment**  
   - Choose **"Git from the command line and also from 3rd-party software"** (recommended).  
   - Click **Next**.  
6. **Choose HTTPS transport backend**  
   - Select **"Use the OpenSSL library"** (default). Click **Next**.  
7. **Choose line-ending conversion**  
   - Select **"Checkout Windows-style, commit Unix-style line endings"** (recommended). Click **Next**.  
8. **Choose terminal emulator**  
   - Select **"Use MinTTY (default terminal for Git Bash)"**. Click **Next**.  
9. **Enable extra options** (default settings are fine). Click **Install**.  
10. **Wait for the installation to complete**, then click **Finish**.  

---

#### **Step 3: Verify Git Installation**  
1. Open **Command Prompt (cmd)** or **Git Bash**  
2. Run the following command:  

   ```sh
   git --version
   ```

   ✅ If Git is installed correctly, it will show a version number like:  
   ```
   git version 2.x.x
   ```

---

#### **Step 4: Configure Git (First-Time Setup)**
1. Set your username:  
   ```sh
   git config --global user.name "Your Name"
   ```
2. Set your email:  
   ```sh
   git config --global user.email "your.email@example.com"
   ```
3. Check your Git configuration:  
   ```sh
   git config --list
   ```

Now you're ready to use Git on Windows! 🎉 🚀




### **How to Clone a Repository from GitHub**  

#### **Step 1: Copy the Repository URL**
1. Go to the GitHub repository you want to clone.  
2. Click on the **"Code"** button (Green button).  
3. Copy the **HTTPS URL** (e.g., `https://github.com/your-username/repo-name.git`).  

---

#### **Step 2: Open Terminal (Command Line)**
- On **Windows**: Open **Git Bash** or **Command Prompt** (`cmd`).  
- On **Mac/Linux**: Open **Terminal**.  

---

#### **Step 3: Navigate to the Folder Where You Want to Clone the Repo**
Use the `cd` command to change to your desired directory.  
For example, to clone into the **Documents** folder:  

```sh
cd ~/Documents
```

---

#### **Step 4: Clone the Repository**
Run the following command:  

```sh
git clone https://github.com/your-username/repo-name.git
```
---

#### **Step 5: Navigate into the Cloned Repository**
After cloning, move into the project folder:  

```sh
cd repo-name
```

---

#### **Step 6: Verify the Cloning Was Successful**
Run:  
```sh
git status
```
If the repository is successfully cloned, it will show:  
```
On branch main
Your branch is up to date with 'origin/main'.
```

Now you're ready to start working on your cloned GitHub repository! 🚀
