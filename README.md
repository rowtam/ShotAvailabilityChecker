# Covid19VaccineChecker
## Checks the Oklahoma Covid Vaccine Website for Availability

# Setup
1) Requires Selenium ChromeDriver matching the version of Chrome you have installed
2) You must have the user-specific URL given to you after registration at the Vaccine website.
3) SMTP account (gmail or any other).
4) SMS/MMS Gateway or E-mail address:

# Configuration File
### Location of Chrome Browser Driver
webdriver=["C:\Users\Path-To\Documents\chromedriver_win32\chromedriver.exe"]

### Multiple Entries
entry=["Massachusetts","First Last","https://vaccinate.oklahoma.gov/follow-up-vaccine/?id=XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXX","12","25","1970","1600 Pennsylvania Blvd, Boston, MA 99999, United States","100"]

entry=["Massachusetts","First Last","https://vaccinate.oklahoma.gov/follow-up-vaccine/?id=XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXX","12","25","1970","1600 Pennsylvania Blvd, Boston, MA 99999, United States","100"]

### E-Mail Notification Settings
smtphost=["smtp.gmail.com"]

smtpport=["465"]

smtpauth=["true"]

emailfromname=["XXXXXX@gmail.com"]

emailfrompassword=["xxxxxxxxxxx"]

### Multiple Recipients
emailtoname=["######@vzwpix.com"]

emailtoname=["######@yahoo.com"]