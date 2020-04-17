# Helpful Engineering Shared Credentials

Whenever possible, no account should be shared with other users.  However, in some instances (e.g. social media accounts, some email accounts, *et cetera*) it will be required to share a single set of credentials with multiple users using a tool called [LastPass](https://www.lastpass.com).

 ⚠️ Credentials should **never** be shared outside LastPass: please **don't** send passwords in plaintext by any other means.

## LastPass master account
The DevOps and Infosec teams maintain a master account where all credentials are stored and shared with the approved users. Passwords are being rotated regularly for security reasons, and the new ones will automatically synchronize in the other users' LastPass vaults.  

## Creating a LastPass account
If you do not have a lastpass account please [create one](https://lastpass.com/create-account.php).  **DO NOT FORGET YOUR LASTPASS PASSWORD!**  It cannot be reset by the infosec team or lastpass.  Your password is used to generate your encryption key, so it is unique to you.  We also recommend installing the lastpass browser extension to your favorite browser.

After your account is created make sure to sign in, this will generate your encryption keys so passwords can be shared securely.  Send the email address you used to sign up to the infosec team ([#skill-infosec](https://app.slack.com/client/TUTSYURT3/CV4TYGC1Z)) and they will share passwords with you.  If you are outside of the admin group in slack approval for access will be required.  The infosec team will reach out to the admin group for approval. 

[Lastpass sharing documentation](https://helpdesk.lastpass.com/sharing-4-0/)

## Changing passwords
When changing a password, you should [generate the new one with LastPass](https://helpdesk.lastpass.com/generating-a-password/) (or equivalent) using the following settings:

* **All characters**:
  - [x] Uppercase
  - [x] Lowercase
  - [x] Numbers
  - [x] Symbols
* Length: **15 or more** characters.

Once you change a password, please update the record in LastPass, so it's automatically shared with all the authorized users.
