# Android Privacy Hardening Guide

## Privacy on Stock Android

Stock Android comes with Google services deeply integrated, which presents inherent privacy challenges. This guide helps minimize data collection and tracking on regular Android devices without requiring rooting or custom ROMs like GrapheneOS.

## Initial Setup for Maximum Privacy

If you're setting up a new Android device, consider these steps:

1. **Minimal Google Account Integration**
   - Consider setting up without a Google account
   - If needed, create a separate Google account just for this device
   - Decline extra Google services during setup

2. **Skip Biometric Setup**
   - Use a strong PIN or password instead
   - Set up biometrics later if needed

3. **Decline Analytics and Diagnostics**
   - Opt out of all "improvement programs"
   - Decline "personalized experience" options

## Google Service Restrictions

### Google Account Settings
- Go to **Settings → Google**
   - **Manage your Google Account → Data & Privacy**
     - Turn off Web & App Activity
     - Turn off Location History 
     - Turn off YouTube History
     - Turn off Ad Personalization
     - Set Auto-Delete for any history you keep
   - **Manage your Google Account → Security**
     - Review which apps have access to your account

### Google App Settings
- **Google app → Profile → Settings → General**
   - Disable Google Search History 
   - Disable Google Now cards

### Play Store Settings
- **Google Play Store → Profile → Settings**
   - **General → Account and device preferences**
     - Disable "Add icon to Home screen"
   - **Network preferences**
     - Enable "App download preference" to Wi-Fi only
   - **About → Play Store version**
     - Tap multiple times and access internal settings menu
     - Disable "Usage & diagnostics"

## System-level Privacy Settings

### App Permissions
- Go to **Settings → Privacy → Permission manager**
   - Review each permission category
   - Restrict sensitive permissions:
     - Location: "Only while using" or "Ask every time"
     - Camera/Microphone: "Only while using" or "Ask every time"
     - Body sensors: Deny when possible
     - Call logs: Deny when possible
     - Contacts: Minimize access
     - Storage: Use scoped storage when available

### Location Settings
- Go to **Settings → Location**
   - Disable "Google Location Accuracy"
   - Disable "Google Location History"
   - Disable "Google Location Sharing"
   - Review app-level location permissions

### Privacy Dashboard
- Go to **Settings → Privacy → Privacy dashboard**
   - Review which apps accessed sensitive data
   - Check for suspicious patterns of access

### Android Advertising ID
- Go to **Settings → Privacy → Ads**
   - Select "Delete advertising ID"
   - Disable ad personalization

### Nearby Device Scanning
- Go to **Settings → Google → Devices & sharing → Nearby Share**
   - Turn off or set to "Hidden"
- Go to **Settings → Google → Devices & sharing → Devices**
   - Disable "Scan for nearby devices"

### Network & Internet
- Go to **Settings → Network & internet**
   - **Wi-Fi → Wi-Fi preferences**
     - Disable "Connect to public networks"
     - Enable MAC randomization
   - **Private DNS**
     - Configure private DNS (dns.adguard.com, dns.quad9.net, or dns.nextdns.io)

## Alternative Apps for Better Privacy

Replace default Google applications with these privacy-focused alternatives:

| Google App | Privacy Alternative |
|------------|---------------------|
| Chrome | Firefox, Bromite, Mull |
| Gmail | K-9 Mail, FairEmail |
| GBoard | AnySoftKeyboard, Simple Keyboard |
| Google Photos | Simple Gallery Pro, Aves |
| Google Drive | Nextcloud, Syncthing |
| Google Maps | OsmAnd, Organic Maps |
| YouTube | NewPipe, LibreTube |
| Google Calendar | Simple Calendar, Etar |
| Google Contacts | Simple Contacts |
| Google Docs | Collabora Office, OnlyOffice |
| Messages | Signal, Session |

## App Store Alternatives

The Google Play Store contains trackers and logs your app installation history. Consider:

1. **F-Droid**
   - Repository of free and open-source apps
   - No tracking or account required
   - Install by allowing "unknown sources" and downloading from f-droid.org

2. **Aurora Store**
   - Anonymous access to Google Play apps
   - Use without Google account
   - Available on F-Droid

## Advanced Privacy Techniques

### Application Control
- Go to **Settings → Apps**
   - Disable unnecessary pre-installed apps
   - For each app, check "Mobile data & Wi-Fi" usage permissions
   - Set "Unrestricted data" only for essential apps

### Sensors Control
- Go to **Settings → Privacy**
   - Disable camera and microphone access globally when not needed
   - Use "Android Sensor Block" app to control other sensors

### Background Process Control
- Go to **Settings → Battery → Battery usage**
   - Restrict background activity for non-essential apps

### Work Profile Isolation
1. Install "Shelter" from F-Droid
2. Create a work profile for privacy-concerning apps
3. Use the work profile only when needed
4. Freeze work profile when not in use

## Addressing Android Limitations

Despite these measures, stock Android has privacy limitations:

1. **Google Play Services** runs with elevated privileges
2. **System apps** may still collect data
3. **Telemetry** exists at various system levels
4. **Hardware identifiers** may still be accessible
5. **Closed-source components** cannot be fully audited

For users needing stronger privacy protection, consider GrapheneOS as described in our [GrapheneOS Getting Started](grapheneos-start.md) guide.

## Privacy Maintenance Routine

Establish a regular privacy maintenance routine:

1. **Weekly**:
   - Check Privacy Dashboard for permission usage
   - Clear cache for browsers and social apps
   - Review active background processes

2. **Monthly**:
   - Update all apps (security patches)
   - Review app permissions
   - Delete unused apps

3. **Quarterly**:
   - Reset advertising ID
   - Check for system updates
   - Review Google account settings
   - Clear app data for non-essential apps

By following these steps, you can significantly reduce tracking and data collection on stock Android devices, though complete privacy requires moving to a privacy-focused OS like GrapheneOS.
