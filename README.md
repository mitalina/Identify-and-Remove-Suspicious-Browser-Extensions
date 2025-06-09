# Identify-and-Remove-Suspicious-Browser-Extensions

## Objective:

To identify and remove any suspicious or potentially malicious browser extensions to ensure data security and optimal browser performance.

## ⚠️ How Malicious Extensions Harm Users:

- Data Theft – Steal personal data (logins, passwords, payment info).

- Ad Injections – Insert ads, redirect search results to ad-heavy or scam sites.

- Browser Hijacking – Modify default settings, change homepage or search engine.

- Tracking and Surveillance – Track browsing activity and sell data to third parties.

- Credential Harvesting – Capture keystrokes or screenshots on secure sites.

- Resource Abuse – Use CPU for crypto mining or inject malicious scripts.

  ## How to remove Chrome extensions:-

- Open Google Chrome.

- Click the three vertical dots in the top-right of the browser window to open the menu.

- Select More tools from the dropdown menu and choose Extensions from the list of options. You should now see all your downloaded browser extensions.

![Screenshot 2025-06-10 030550](https://github.com/user-attachments/assets/476c014e-65a5-446e-8fa1-cdc3652a41b3)

- Find the extension you want to delete and click the Remove button.

![Screenshot 2025-06-10 031143](https://github.com/user-attachments/assets/99554705-e9b3-4b79-b038-28d7838def16)
 
 ## How to delete hidden Chrome extensions on Windows:-
 
1. Open your file explorer and paste the following pathway into the navigation bar, replacing username with the username you use on your computer, then press Enter.

C:\Users\username\AppData\Local\Google\Chrome\User Data\Default\Extensions

2. Inside the extensions folder are more folders for each extension, with the folder names as strings of letters.

![Screenshot 2025-06-10 033651](https://github.com/user-attachments/assets/6eb5699c-a061-4c7b-a454-e2e22100c076)

3. Open any folder. You won’t know which extension each folder is for until you go a little deeper.

4. Open the subfolder with the extension’s version number.

![Screenshot 2025-06-10 034013](https://github.com/user-attachments/assets/7a685882-9065-478a-810d-bd6a61cd285a)

5. Look for a manifest.json file, which is a simple JSON file that tells the browser how the extension’s user interface should appear when installed on desktop or mobile devices.

![Screenshot 2025-06-10 034212](https://github.com/user-attachments/assets/06c39560-2e50-4a7c-a8eb-813c017e4c0d)

6. Open the manifest.json file by right-clicking and selecting “open with” and choosing your preferred text or code editor.
   Then identify the name of the extension by checking the short_name field.
   
![Screenshot 2025-06-10 034416](https://github.com/user-attachments/assets/3a6069ff-fd09-46f4-b89d-960a4d901bcf)

7. To remove this extension, return to its main folder (step 3, where all the folders are listed with strings of letters as names) and delete the folder.

8. Restart Google Chrome.


## How to identify malicious extensions:-

Before adding a new extension or plugin to your browser, make sure you’re not adding something malicious. Here’s a quick checklist to make sure you don’t add any unsafe extensions.

### 1. Research the developer

  - No identifiable publisher

  - Few or no user reviews

  - No support website or privacy policy 
     
### 2. Check the extension’s requested permissions

  Malicious extensions often ask for excessive permissions, such as:
   
  - Full access to read/change all your data on websites

  - Access to clipboard, downloads, or browser history

  - Ability to manage extensions or change browser settings

### 3. After installing the extension, look for strange behavior

  - Slowing down browser performance

  - Showing aggressive pop-ups or fake virus alerts

  - Changing your homepage or search engine

### 4. Check for Hidden or Unauthorized Installation:
      
   - Appears in the browser without user’s consent

   - Installed via bundled software or phishing emails

###  5. Scan with Security Tools:
    
  Use trusted cybersecurity tools or online scanners (like VirusTotal) to analyze the extension’s .crx or ID.

        




