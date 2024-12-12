# Assignment_3_4
creating GitHub Actions to run their Jest tests in response to Git commits
Step 1: Create a Local Git Repository

1. Open your terminal or command prompt.
2. Navigate to your project directory:
   ```bash
   cd path/to/your/project
   ```
3. Initialize a new Git repository:
   ```bash
   git init
   ```
4. Add your files to the repository:
   ```bash
   git add .
   ```
5. Commit your files:
   ```bash
   git commit -m "Initial commit"
   ```
   
Step 2: Create a GitHub Repository
1. Log in to your GitHub account.
2. Click the '+' icon in the top-right corner and select "New repository".
3. Name your repository and choose whether it should be public or private.
4. DO initialize the repository with a README, and set MIT license.
5. Click "Create repository".

Step 3: Generate a Personal Access Token (PAT)
1. In GitHub, click on your profile picture and go to "Settings".
2. Scroll down to "Developer settings" in the left sidebar.
3. Click on "Personal access tokens" and then "Generate new token".
4. Give your token a descriptive name.
5. Select the scopes or permissions you'd like to grant this token. For basic repository access, select "repo".
6. Click "Generate token".
7. Copy the token immediately and store it securely. 

# THIS CHANGE WAS MADE ON LOCAL CLIENT 
#
Step 4: Connect Local Repository to GitHub
1. In your terminal, add the GitHub repository as a remote:
   ```bash
   git remote add origin https://github.com/username/repository.git
   ```
2. Push your code to GitHub using your PAT:
   ```bash
   git push -u origin main
   ```
3. When prompted for a password, use your PAT instead of your GitHub password.

# this change was made on GITHUB




