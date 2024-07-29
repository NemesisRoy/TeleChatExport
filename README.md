# To Export Telegram Chat via Mobile App

# Install Termux on Your Device
Download and install the Termux app from the Google Play Store or your preferred app store.

# Set Up Termux
Open Termux and run the following commands to update and install necessary packages:

```bash
pkg update && pkg upgrade
pkg install python
pip install telethon
```

# Necessary Variables
Visit [HERE](my.telegram.org) to get your API_ID and API_HASH.

# Download the Scripts
Download Login.py and main.py files from this repository . Save them to a directory on your device.

# Open the Directory in Termux
Give termux permission to access files 
```bash
termux-setup-storage
```
And now type following commands 
```bash
ls
```
You will pe prompted some options , choose where the downloaded files are saved , for example 
```bash
cd downloads
```

# Run the Login Script
Now execute the following command:
```bash
python Login.py
```

# LOGIN
Enter your API_ID and API_HASH when prompted to log in. 
* Enter phone number with +91 country code for 🇮🇳

# Run the Main Script
After logging in, run the main script and enter details again
```bash
python main.py
```

# Export Chats
Open any Telegram chat and type the `/save` command. The chat will be exported to a .txt file and sent to your Saved Messages.

<hr>

🌟 Star & Fork this Repository if it was helpful;

⚠️ After Exporting chats, Go to settings --> Devices --> Terminate all other sessions, for safety purposes !

💌 If you Face any Error Feel free to [contact me](https://t.me/NemesisRoy)
