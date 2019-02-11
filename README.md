# FoxAuth Importer
A database importer for FoxAuth Authenticator, fork from [android otp extractor](https://github.com/puddly/android-otp-extractor).

## Usage
Required: 
- **rooted** Android phone.
- adb connection with developer mode turned on.
- database decrypted in previous app.

After adb connection to your Android, run as the argument `python3 -u android-otp-extractor-foxauth.py --firefox-extension`. This shall print data as how FoxAuth required.