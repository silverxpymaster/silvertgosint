# Silvertgosint

This tool connects to your Telegram account using the API ID and API hash and retrieves all messages of the target user from the groups you are in, saving them to a TXT file and additionally storing them in a database.  

When logging in, you need to access your Telegram account via [my.telegram.org](https://my.telegram.org) and generate an API ID and API hash.  

Additionally, if the target group is publicly accessible, various details such as ID, username, name, number, etc., can be collected.  

**Useful Note:** You can add the account linked to this tool to hundreds of groups and collect the target’s messages from all those groups.

## Features
- Collect messages from Telegram groups and users
- Store messages in a SQLite database
- Retrieve and save group information
- Download media files from groups
- Generate message statistics for specific users

## Installation

### Requirements
Ensure you have Python installed along with the required dependencies. Install them using:

```bash
pip install -r requirements.txt
```

### Setup
1. Obtain API credentials from [my.telegram.org](https://my.telegram.org):
   - Login and navigate to "API development tools."
   - Create a new app and note the `API ID` and `API Hash`.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/telegram-osint-tool.git
   ```
3. Navigate into the project folder:
   ```bash
   cd telegram-osint-tool
   ```
4. Run the tool:
   ```bash
   python main.py
   ```

## Usage

1. **Collect User Messages:** Enter the target Telegram username or ID to retrieve messages from groups.
2. **Get Group Info:** Provide a Telegram group link to extract group details and member information.
3. **Generate Message Statistics:** Analyze a user's activity across multiple groups.
4. **Download Group Media:** Retrieve all images and videos from a specified Telegram group.

## Notes
- This tool requires authentication with Telegram using a phone number and an active session.
- The SQLite database stores collected messages for further analysis.

## Author
**SilverX**  
[YouTube Channel](https://youtube.com/@silverxcyber)  
[Telegram](https://t.me/silverxvip)

---
**Disclaimer:** This tool is for educational and research purposes only. Use it responsibly and ensure compliance with Telegram's terms of service.

