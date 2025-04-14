# iOS Privacy Hardening Guide

## Privacy on iOS: Capabilities and Limitations

iOS provides various privacy features that, when properly configured, can significantly reduce tracking and data collection. However, it's important to understand that Apple still maintains access to much of your data and activity. This guide helps you maximize privacy within these constraints.

## Essential iOS Privacy Settings

Work through these settings systematically to enhance your privacy:

### 1. Apple ID and iCloud Settings
- Go to **Settings → [your name] → iCloud**
   - Review which apps sync data to iCloud
   - Disable syncing for sensitive apps
   - Consider disabling iCloud Backup (creates unencrypted backups on Apple servers)
   - Use **iCloud Private Relay** if subscribed to iCloud+ (masks IP address)
   - Enable **Hide My Email** to create email aliases

### 2. Privacy & Security Settings
- Go to **Settings → Privacy & Security**
   - **Location Services**:
     - Review app permissions
     - Set apps to "While Using" or "Ask Next Time"
     - Disable "Precise Location" for apps that don't need it
     - Scroll to bottom → System Services → disable unnecessary location tracking
     - Disable "Significant Locations" tracking
   - **Tracking**: 
     - Enable "Ask Apps Not to Track"
   - **App Privacy Report**:
     - Enable to monitor how apps use permissions
     - Review weekly to identify suspicious behavior
   - Review permissions for **Contacts**, **Calendars**, **Photos**, etc.
     - Grant minimal access (selected photos instead of full library)
     - Use "Ask Each Time" for sensitive permissions

### 3. Analytics & Advertising
- Go to **Settings → Privacy & Security → Analytics & Improvements**
   - Disable "Share iPhone Analytics"
   - Disable "Improve Siri & Dictation"
   - Disable "Share iCloud Analytics"
- Go to **Settings → Privacy & Security → Apple Advertising**
   - Disable "Personalized Ads"

### 4. Network Privacy
- Go to **Settings → Wi-Fi**
   - Tap (i) icon next to connected network → Enable "Private Wi-Fi Address"
- Go to **Settings → Bluetooth**
   - Turn off when not in use
- Go to **Settings → General → VPN & Device Management**
   - Configure a privacy-focused VPN

### 5. Safari Privacy
- Go to **Settings → Safari**
   - Enable "Prevent Cross-Site Tracking"
   - Enable "Block All Cookies" (may break some sites)
   - Enable "Fraudulent Website Warning"
   - Set "Privacy Preserving Ad Measurement" to off
   - Set "Check for Apple Pay" to off
   - Under "Advanced" → "Website Data" → remove data periodically

### 6. Siri and Search
- Go to **Settings → Siri & Search**
   - Disable "Listen for 'Hey Siri'" if concerned about always-on microphone
   - Review app search permissions
   - Disable "Show Suggestions from Apple" in various contexts

### 7. TouchID/FaceID Settings
- Go to **Settings → Face ID & Passcode (or Touch ID & Passcode)**
   - Use a strong alphanumeric passcode (not just 6 digits)
   - Disable features accessible on lock screen
   - Enable "Erase Data" after 10 failed passcode attempts

## Secure Communications on iOS

### Messaging Options
- **iMessage** provides E2EE but only for Apple-to-Apple communications
- **Signal** for truly secure messaging (available on App Store)
- **Session** for anonymous communication (available on App Store)
- Avoid standard SMS for sensitive communications

### Default Apps Replacement
| Built-in App | Privacy-Focused Alternative |
|--------------|--------------------------|
| Safari | Firefox Focus, Brave, Onion Browser |
| Mail | ProtonMail, Tutanota |
| Maps | OsmAnd, Organic Maps |
| Notes | Standard Notes, Joplin |
| Calendar | Proton Calendar, Tutanota Calendar |
| Photos | Stingle Photos, Cryptee |

## Additional Privacy Measures

### Content Blockers
1. Install content blockers from App Store:
   - AdGuard
   - 1Blocker
   - Better
2. Configure in **Settings → Safari → Extensions → Content Blockers**

### Lockdown Mode
For users facing serious targeted threats, consider enabling Lockdown Mode:
- Go to **Settings → Privacy & Security → Lockdown Mode**
- Be aware this significantly restricts functionality

### App Store Privacy Labels
- Review privacy labels before installing apps
- Look for "Data Not Collected" or minimal data collection
- Be wary of apps collecting "Data Used to Track You"

### Background App Refresh
- Go to **Settings → General → Background App Refresh**
- Disable for apps that don't need real-time updates
- Consider setting to "Wi-Fi Only"

## iOS Privacy Limitations

Despite these measures, be aware of these inherent limitations:

1. **System-level telemetry** cannot be fully disabled
2. **App Store restrictions** prevent certain privacy tools
3. **Apple services** collect data even with privacy settings
4. **iCloud backups** are not end-to-end encrypted (except for specific categories)
5. **iOS updates** may change privacy settings or introduce new tracking

## Privacy Maintenance Routine

Establish a regular privacy maintenance routine:

1. **Weekly**:
   - Review App Privacy Report
   - Clear website data from Safari
   - Check which apps requested sensitive permissions

2. **Monthly**:
   - Review installed apps and remove unnecessary ones
   - Check for iOS updates (important for security patches)
   - Review Privacy settings for any changes after updates

3. **Quarterly**:
   - Reset Advertising Identifier
   - Audit apps connected to Apple ID
   - Review all privacy settings comprehensively

Remember that privacy on iOS requires ongoing vigilance as both apps and the operating system evolve over time.
