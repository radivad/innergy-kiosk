# Chrome Group Policy Settings

Download the [Chrome policy](https://support.google.com/chrome/a/answer/187202?hl=en) and follow the instructions to set up for your kiosk device.

## Recommended Policy Settings

### Computer Configuration > Policies > Administrative Templates > Google > Google Chrome

| Policy  | Setting | Parameter | Required |
| -- | -- | -- | -- |
| Allow access to a list of URLs | Enabled | innergy.com | Required |
| Allow access to a list of URLs | Enabled | app.innergy.com | Required|
| Block access to a list of URLs | Enabled | * | Required |
| Browser sign in settings | Enabled | Disable browser sign-in | Required |
| Control where Developer Tools can be used | Enabled | Disallow usage of the Developer Tools | Optional |
| Enable AutoFill for addresses | Disabled | | Recommended |
| Enable AutoFill for credit cards | Disabled | | Recommended |

### Computer Configuration > Policies > Administrative Templates > Google > Google Chrome > Extensions

| Policy  | Setting | Parameter | Required |
| -- | -- | -- | -- |
| Configure extension installation allow list | Enabled | [ajdehnbmilfnjbfhffbjdmkohamimpjo](https://chrome.google.com/webstore/detail/innfinergy-v419/ajdehnbmilfnjbfhffbjdmkohamimpjo) | Recommended |
| Configure extension installation blocklist | Enabled | * | Recommended |
| Configure the list of force-installed apps and extensions | Enabled | [ajdehnbmilfnjbfhffbjdmkohamimpjo](https://chrome.google.com/webstore/detail/innfinergy-v419/ajdehnbmilfnjbfhffbjdmkohamimpjo) | Recommended |

### Computer Configuration/Policies/Administrative Templates/Google/Google Chrome/Password manager

| Policy  | Setting | Parameter | Required |
| -- | -- | -- | -- |
| Enable saving passwords to the password manager | Disabled | | Recommended |

### Computer Configuration > Policies > Administrative Templates > Google > Google Chrome > Startup, Home page and New Tab page

| Policy  | Setting | Parameter | Required |
| -- | -- | -- | -- |
| Action on startup | Enabled | Open a list of URLs | Required |
| Configure the home page URL | Enabled | https://app.innergy.com/kiosk/ | Required |
| Configure the New Tab page URL | Enabled | https://app.innergy.com/kiosk/ | Required |
| URLs to open on startup | Enabled | https://app.innergy.com/kiosk/ | Required |

### Computer Configuration > Administrative Templates > Windows Components > Windows Update > Windows Updates for Business

| Policy  | Setting | Parameter | Required |
| -- | -- | -- | -- |
| Select the target Feature Update version | Enabled | Which WIndows product version would you like to receive feature updates for? = "Windows 10" | Required |
| Select the target Feature Update version | Enabled | Target Version for Feature Updates = "21H2" | Required |