# ISS Overhead Notifier (Python Project)

This project checks if the International Space Station (ISS) is currently flying over your location and notifies you.  
It uses the ISS location API and sunrise/sunset data to decide if the station is visible.

---

## How to Run This Project

### Step 1: Install Python
Make sure you have Python 3.8 or higher installed.  
Check with:
```bash
python --version
##
##You need the requests library:
##step2
bash
pip install requests
##Step 3: Set Your Location
##Open main.py and edit these values:

##python
MY_LAT = 17.3850   # Your latitude
MY_LONG = 78.4867  # Your longitude
##Step 4: Configure Email (Optional)
##If you want email alerts:

##python
MY_EMAIL = "your_email@example.com"
PASSWORD = "your_app_password"
##Step 5: Run the Script
##From your terminal or PyCharm:

##bash
python main.py
##If the ISS is overhead and it’s dark, you’ll see:

##Code
Look up! The ISS is above you in the sky!
##Or you’ll get an email notification.
