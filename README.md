# Cardano Pool's Social Info Repository

This repository is meant to serve as a central location for Cardano stake pool operators to add and update their social media information. The data is stored in a JSON file named `fullcontact.json`.

## How to Update Your Pool's Information

If you are a Cardano stake pool operator and would like to add or update your pool's information, please follow the steps below:

### Step 1: Fork the Repository

In the top right corner of this page, you will see a button that says "Fork". Click on this button to create a copy of this repository in your own GitHub account.

### Step 2: Locate Your Pool in the JSON File

Once you have a fork of the repository, navigate to the `fullcontact.json` file. Within this file, find the entry for your pool. 

An entry looks like this:

```json
{
    "name": "Your Pool Name",
    "ticker": "YOURTICKER",
    "homepage": "https://yourpoolhomepage.com",
    "twitter": "",
    "discord": "",
    "telegram": ""
}
```

### Step 3: Edit the JSON File

Click on the pencil icon in the top right of the file view to start editing the file.

Fill in or update the fields for your pool. Please ensure that the information you enter is within the double quotes "". 

For example, if your pool's Twitter handle is `@yourpool`, your entry should look like this:

```json
{
    "name": "Your Pool Name",
    "ticker": "YOURTICKER",
    "homepage": "https://yourpoolhomepage.com",
    "twitter": "https://twitter.com/yourpool",
    "discord": "",
    "telegram": ""
}
```

Do the same for any other social platforms your pool uses.

### Step 4: Save Your Changes

Scroll down to the bottom of the page and click the "Commit changes" button to save your changes.

### Step 5: Submit a Pull Request

Once you've committed your changes, navigate back to the main page of your forked repository. Click on the "Pull request" button.

On the next page, click the "Create pull request" button. You can leave a comment With your pool Name, then click "Create pull request" again.

Once you've submitted your pull request, we will review your changes. After we've verified the information, we'll merge your changes into the main repository.

### IMPORTANT: 

- Please only change information related to your own pool.
- Do not remove any pools or modify other pools' information.
- Ensure the URLs you provide are accurate and functional.
- Make sure to maintain the JSON format. Incorrect formatting may result in your pull request being rejected.
- Make sure to include your pool name in comment.

Thank you for helping keep this resource accurate and up-to-date!

---
