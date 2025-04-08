1. Clone the Repository

First, clone your repository to your PC:

git clone https://github.com/mehranbhatti/rgb_odometry.git

cd rgb_odometry

4. Copy Files into the Repository

Let’s say your files are in this folder on your PC:

C:/Users/HP/Downloads/my_files_to_upload/

Use this command to move them into the cloned repo:

mv /c/Users/HP/Downloads/my_files_to_upload/* .

Alternatively, you can use File Explorer to copy-paste them into the rgb_odometry folder.

6. Configure Git (only needed once per device)

If you haven’t done this before, run:

git config --global user.name "mehranbhatti"

git config --global user.email "your_email@example.com"

Replace your_email@example.com with the email linked to your GitHub account.

8. Stage the New Files

Add all the new files (don’t add folders you don’t want like spray):

git add .

Or if you only want specific folders/files:

git add folder1 folder2 file1.py

10. Commit the Changes

Write a clear commit message:

git commit -m "Added new files from local folder"

13. Push to GitHub

Assuming you're using the main branch (double-check if it's main or master):

git push origin main
