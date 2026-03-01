# GitHub-Tips-&-Tricks

## MD format and tricks
https://www.markdownguide.org/cheat-sheet/

## Delete Files
Method 1: Deleting a File via the GitHub Web Interface
- Navigate to the Repository: Log in to your GitHub account and go to the repository containing the file you want to delete.
- Locate and Select the File: Browse through the repository's files and click on the specific file you intend to remove.
- Initiate Deletion: On the file's page, locate and click the trash can icon (🗑️) or a three-dot menu, and then select "Delete file."
- Commit Changes: You will be prompted to commit the changes. Provide a concise commit message describing the deletion.
- Confirm Deletion: Click "Commit changes" to finalize the deletion. The file will be removed from the repository.

## Move Files
Using the GitHub Web Interface:
- Navigate to the file: In your repository, locate and click on the file you want to move.
- Enter edit mode: Click the pencil icon (Edit this file) to open the file editor.
- Modify the filename path: In the filename field at the top, change the path to include the new directory where you want the file to reside. For example, to move my_file.bin to a new_folder, change the filename from my_file.bin to new_folder/my_file.bin. If the new_folder does not exist, GitHub will create it.
- Commit changes: Provide a commit message and optionally a description. Decide whether to commit directly to the current branch or create a new branch, then click "Commit changes" or "Propose changes."

## Deleting a Repository
🧹 How to Delete a Repository on GitHub — Step by Step
⚠️ Important: Only users with admin/owner permissions on the repository can delete it. If you don’t see the delete option, you might not have sufficient permissions.
1. Log In to GitHub - Open your web browser and sign into your GitHub account at github.com.
2. Go to the Repository
   - Navigate to the main page of the repository you want to delete:
   - Click your profile icon → Your repositories
   - Select the repository from your list.
3. Open Settings - At the top of the repository page: Click the Settings tab. (If you don’t see it, look under the dropdown at the far right of the tabs.)
4. Scroll Down to the “Danger Zone”
   - On the General settings page:
   - Scroll all the way to the bottom until you see the Danger Zone section.
5. Click “Delete this repository”
   - In the Danger Zone:
   - Click the Delete this repository button.
   - You’ll see a series of warnings about permanent deletion.
6. Confirm the Deletion
   - GitHub will ask you to type the exact repository name to confirm you want to delete it (e.g., your-username/repo-name).
   - Carefully type the repo name exactly as shown.
   - Click I understand the consequences, delete this repository.
7. Final Removal
   - Once confirmed:
   - The repository will be permanently deleted from GitHub.
   - You’ll be redirected back to your list of repositories or your dashboard.
