## NCSC macOS configurations ##
|MDM settings|As per Profile Manager MDM|
|---|---|
||
|General||
|Profile Distribution Type|Automatic Push|
|Security (Controls when the profile can be removed)|Never|
|Automatically Remove Profile (Settings for automatic profile removal)|Never|
||
|Passcode||
|Configure this section to organisation policy||
||
|Restrictions - Preferences||
|Restrict items in System Preferences|Yes (disable selected items): iCloudProfilesSecurity & PrivacyStartup Disk|
||
|Restrictions - Apps||
|Restrict which apps are allowed to launch|YesAdd a list of approved applications permitted by the business|
||
|Restrictions - Media||
|Configure this section to organisation policy||
||
|Restrictions - Sharing||
|Select services that should be available in the share menu|Disable:AirDrop Messages Twitter Facebook LinkedIn Video Services Sina Weibo|
||
|Restrictions - Functionality||
|Allow password sharing|No|
|Allow proximity based password sharing requests|No|
|Allow Classroom to lock the device without prompting|No|
|Automatically join Classroom classes without prompting|No|
|Require teacher permission to leave Classroom unmanaged classes|No|
|Allow use of iCloud password for local accounts|No|
|Allow iCloud Drive|No|
|Allow iCloud Desktop & Documents|No|
|Allow iCloud Keychain|No|
|Allow iCloud Mail|No|
|Allow iCloud Contacts|No|
|Allow iCloud Calendars|No|
||
|Security & Privacy Payload - General||
|Configure Gatekeeper Settings|Mac App Store and identified developers|
|Do not allow user to override Gatekeeper setting|Yes|
||
|Security & Privacy Payload - FileVault||
|Require FileVault|Yes|
|Escrow Personal Recovery Key|Yes|
||
|Security & Privacy Payload - Firewall||
|Manage Firewall Settings|Yes|
|Enable Firewall|Yes|
|Block all incoming connections|Yes|
||
|Software Update Payload||
|Allow installation of macOS beta releases|No|
|Allow non-admin users to purchase apps and install software updates|Yes|
|Automatically install macOS updates|Yes|
|Automatically install app updates from the App Store|Yes|
||
|VPN configuration - IPsec PRIME profile||
|Connection type|IKEv2|
|Always-on (supervised only)|Yes|
|Machine Authentication|Certificate|
|Enable perfect forward secrecy|Yes|
|Enable certificate revocation check|Yes|
|Encryption algorithm (IKE & Child SA)|AES-128-GCM|
|Diffie-Hellman Group (IKE & Child SA)|19|
|Allow traffic from captive web sheet outside the VPN tunnel|Yes|
||