# DriveThru Extension Privacy Policy

## Single Purpose Description
DriveThru adds a "Re-download" button to Google Drive files when viewing them, allowing users to easily re-download files if they encounter any issues with the initial download. This enhances the Google Drive download experience by providing a simple, one-click solution for file download issues.

## Permission Justifications

### Storage Permission
**Feature**: The extension needs to remember if a file has been previously downloaded and track download states.
**Why needed**: Without storage permission, the extension couldn't:
- Remember which files have been downloaded
- Save user preferences for download behavior
- Track download progress and status

### Downloads Permission
**Feature**: The "Re-download" button that appears on Google Drive file pages.
**Why needed**: Without downloads permission, the extension couldn't:
- Initiate file downloads when users click the re-download button
- Handle file downloads from Google Drive
- Manage download states and retries

### Tabs Permission
**Feature**: The automatic injection of the re-download button on Google Drive file pages.
**Why needed**: Without tabs permission, the extension couldn't:
- Detect when you're viewing a Google Drive file
- Add the re-download button to the correct page
- Update the button state based on file status

### Notifications Permission
**Feature**: Download status notifications that tell you when:
- A download has started
- A download has completed
- There was an error during download
**Why needed**: Without notifications permission, users wouldn't know if their download was successful or failed

### Scripting Permission
**Feature**: The re-download button that appears on Google Drive pages.
**Why needed**: Without scripting permission, the extension couldn't:
- Add the re-download button to Google Drive pages
- Make the button interactive
- Handle click events on the button

### Host Permission
**Feature**: Integration with Google Drive's file viewer and download system.
**Why needed**: Without host permission for Google Drive domains, the extension couldn't:
- Access Google Drive pages to add the re-download button
- Interact with Google Drive's file viewer
- Handle file downloads from Google Drive URLs

### Identity Permission
**Feature**: The extension needs to work with Google Drive's file system which requires:
- Accessing Google Drive files in the browser
- Handling file downloads from Google Drive URLs
- Working with Google Drive's file viewer

**Why needed**: Without identity permission, the extension couldn't:
- Access Google Drive pages properly
- Work with Google Drive's file system
- Handle file downloads from authenticated Google Drive sessions

Note: The extension does NOT:
- Store any user identity information
- Access any personal Google account data
- Require users to log in separately
- Send any identity information to external servers

It only uses the identity permission to work within the existing Google Drive session that users are already logged into in their browser.

## Remote Code
**No remote code is used**
All code is packaged within the extension. The extension only:
- Uses local JavaScript files
- Doesn't load any external scripts
- Doesn't use eval() or external resources

## Data Usage

### Data Collection
DriveThru does NOT collect or store any of the following types of data:
- ❌ Personally identifiable information
- ❌ Health information
- ❌ Financial and payment information
- ❌ Authentication information
- ❌ Personal communications
- ❌ Location
- ❌ Web history
- ❌ User activity
- ❌ Website content

### Data Usage Certifications
✅ I certify that:
1. I do not sell or transfer user data to third parties, outside of the approved use cases
2. I do not use or transfer user data for purposes that are unrelated to my item's single purpose
3. I do not use or transfer user data to determine creditworthiness or for lending purposes


---

### Additional Privacy Information
1. The extension operates entirely locally within the user's browser
2. No user data is collected, stored, or transmitted to external servers
3. The extension only interacts with Google Drive's interface to enhance the user experience
4. All file operations are performed directly between the user's browser and Google Drive
5. No analytics or tracking mechanisms are implemented 
