# Silvertgosint - Telegram OSINT Tool

This tool connects to your Telegram account using the API ID and API hash and retrieves all messages of the target user from the groups you are in, saving them to a TXT file and additionally storing them in a database.  

When logging in, you need to access your Telegram account via [my.telegram.org](https://my.telegram.org) and generate an API ID and API hash.  

Additionally, if the target group is publicly accessible, various details such as ID, username, name, number, etc., can be collected.  

**Useful Note:** You can add the account linked to this tool to hundreds of groups and collect the target’s messages from all those groups.

![Image Alt](https://github.com/silverxpymaster/silvertgosint/blob/main/Screenshot.png?raw=true)

## Features
```
- All groups the target user is in and all messages they have sent in those groups are collected.  
- Statistics on how many messages the target has sent in each group are gathered (this allows you to see which group they are most active in).  
- All members of the target group (in ID, name, username, and number format) are collected and saved to a TXT file.  
- All media from the target group is downloaded.
```

## Installation

### Setup
1. Obtain API credentials from [my.telegram.org](https://my.telegram.org):
   - Login and navigate to "API development tools."
   - Create a new app and note the `API ID` and `API Hash`.
2. Clone this repository:
   ```bash
   git clone https://github.com/silverxpymaster/silvertgosint.git
   ```
3. Navigate into the project folder:
   ```bash
   cd silvertgosint
   ```
4. Download the required libraries
   ```bash
   pip install -r requirements.txt
   ```
4. Run the tool:
   ```bash
   python silvertgosint.py
   ```
## YouTube Tutorial
[![Video Title](https://img.youtube.com/vi/U9mA-wkfxY4/0.jpg)](https://www.youtube.com/watch?v=U9mA-wkfxY4)

Click photo and watch youtube tutorial

## Notes
- This tool requires authentication with Telegram using a phone number and an active session.
- The SQLite database stores collected messages for further analysis.

## Author
**SilverX**  
[YouTube Channel](https://youtube.com/@silverxcyber)  
[Telegram Channel](https://t.me/silverxvip)

---
**Disclaimer:** This tool is for educational and research purposes only. Use it responsibly and ensure compliance with Telegram's terms of service.

