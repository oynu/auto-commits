# GitHub Auto Committer

This repository uses a GitHub Action to automatically make a commit every day, keeping your GitHub contribution streak alive without needing to run anything on your PC.

## How to use this for your own account

1. **Fork this repository:** Click the "Fork" button in the top right corner of this page to create a copy in your own account.
2. **Enable Actions:** Go to the **Actions** tab in your new forked repository. GitHub disables actions on forks by default, so click the green button to enable them.
3. **Enable the workflow:** On the left side of the Actions tab, click on **Auto Commit**, then click **Enable workflow**.
4. **Test it (Optional):** Click **Run workflow** -> **Run workflow** on the right side to trigger it immediately and ensure it works.

Once enabled, this script will run automatically every day at 07:00 UTC and push a new commit to your repository.
