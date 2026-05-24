# Zendesk Call Downloader

A lightweight, dependency-free JavaScript utility to bulk download audio recordings (MP3s) from Zendesk tickets directly from your browser's developer console.



## How to Use

1. Open your Zendesk agent interface in your browser (e.g., `https://yoursubdomain.zendesk.com/agent/...`).
2. Press **F12** and select the **Console** tab.
3. Open `downloader.js` from this repository, copy the entire script, and paste it into your console.
4. Update the `TARGET_ASSIGNEE` variable if you want to download calls for a specific user ID instead of yourself.
5. Press **Enter** to run.
6. **Note:** Allow the browser permission to download multiple files when prompted.
