# GrapheneOS: Getting Started

## What is GrapheneOS?

GrapheneOS is a privacy and security focused mobile operating system built on top of the Android Open Source Project. Unlike stock Android, GrapheneOS focuses on enhanced security features, removes Google services by default (though they can be optionally installed in a sandboxed environment), and provides stronger privacy protections.

- [Official GrapheneOS Documentation](https://grapheneos.org/usage)
- [GrapheneOS Subreddit](https://reddit.com/r/GrapheneOS)
- [GrapheneOS Matrix Community](https://matrix.to/#/#grapheneos:grapheneos.org)
- [GitHub Repository](https://github.com/GrapheneOS)

## Is GrapheneOS Right for You?

### Consider GrapheneOS if you:
- Want maximum privacy and security on a mobile device
- Are concerned about Google's data collection practices
- Are comfortable with some technical processes
- Don't depend heavily on Google services (or are willing to use alternatives)
- Have a compatible device (primarily Google Pixel phones)
- Are willing to trade some convenience for enhanced privacy

### GrapheneOS might not be ideal if you:
- Require seamless Google service integration
- Aren't comfortable with technical setup processes
- Need specific apps that require Google services to function
- Don't have a compatible device

## Compatible Devices

GrapheneOS officially supports Google Pixel devices due to their strong security architecture:

- **Currently Supported**: Pixel 4a, 5, 5a, 6, 6 Pro, 6a, 7, 7 Pro, 7a, 8, 8 Pro, 8a, 9, 9 Pro, 9 Pro XL, and 9 Pro Fold
- **Support Period**: Typically follows Google's official support period for security updates

Before purchasing, verify the current support status on the [GrapheneOS device support page](https://grapheneos.org/faq#supported-devices).

## Installation Overview

The installation process involves:

1. **Unlocking the bootloader** of your Pixel device
2. **Installing GrapheneOS** via web installer or manual method
3. **Locking the bootloader** to restore security
4. **Initial device setup**

GrapheneOS offers a web-based installer that simplifies this process significantly. For most users, this is the recommended installation method.

### Prerequisites
- A compatible Pixel device
- A computer with Chrome or a Chromium-based browser
- USB cable to connect phone to computer
- Backup of any existing data on your device
- Stable internet connection

### Basic Installation Steps
1. Visit the [GrapheneOS web installer](https://grapheneos.org/install/web)
2. Follow the guided process to:
   - Enable Developer options on your Pixel
   - Enable USB debugging
   - Unlock the bootloader
   - Install GrapheneOS
   - Re-lock the bootloader

The web installer handles the complex technical details, making installation accessible to most users with basic technical skills.

### After Installation
- Complete initial device setup
- Configure privacy settings
- Install your preferred apps

## Key Privacy Features

GrapheneOS includes several privacy enhancements beyond stock Android:

### Enhanced App Permissions
- **Network Permission Controls**: Restrict which apps can access the internet
- **Sensors Permission**: Fine-grained control over sensor access
- **Storage Scopes**: Limit what folders apps can access

### Sandboxed Google Services (Optional)
- Install Google services in a restricted environment
- Provides app compatibility while limiting Google's data collection
- Available through the included Apps app

### Security Enhancements
- **Hardened Memory Allocator**: Prevents memory exploitation
- **Vanadium Browser**: Privacy-focused browser based on Chromium
- **Improved Encryption**: Enhanced filesystem encryption

## Essential First Steps

After installing GrapheneOS, take these steps:

1. **Review System Settings**
   - Go through all privacy settings
   - Configure app permissions
   - Set up secure lock screen

2. **Install Basic Apps**
   - F-Droid for open-source apps
   - Aurora Store for accessing Google Play apps anonymously
   - Signal or Session for secure messaging

3. **Consider Google Services**
   - Decide whether you need sandboxed Google Play services
   - If yes, install from the Apps app
   - Configure with minimal permissions

4. **Configure Network Privacy**
   - Set up a trusted VPN
   - Configure DNS over HTTPS
   - Review network permissions for all apps

5. **Set Up App Store Alternatives**
   - F-Droid for open-source apps
   - Aurora Store for Google Play apps without Google account

## Common Challenges and Solutions

### App Compatibility
- **Challenge**: Some apps require Google services
- **Solution**: Install sandboxed Google Play services or find alternatives

### Banking Apps
- **Challenge**: Many banking apps check for "device integrity"
- **Solution**: Use sandboxed Play services with Play Integrity API

### Notifications
- **Challenge**: Push notifications may not work without Google services
- **Solution**: Use apps with alternative notification methods or install sandboxed Play services

### App Store Updates
- **Challenge**: Managing updates from multiple sources
- **Solution**: Use the "Apps" app which integrates update management

## Resources for Learning More

- [Official GrapheneOS Documentation](https://grapheneos.org/usage)
- [GrapheneOS Subreddit](https://reddit.com/r/GrapheneOS)
- [GrapheneOS Matrix Community](https://matrix.to/#/#grapheneos:grapheneos.org)
- [GitHub Repository](https://github.com/GrapheneOS)

## Privacy Beyond GrapheneOS

Remember that while GrapheneOS significantly enhances your mobile privacy, other factors impact your overall digital privacy:

- Your online accounts and services
- Your browsing habits and search behavior
- Physical security of your device
- Network security (home Wi-Fi, public networks)
- Your overall digital behavior

Use GrapheneOS as part of a comprehensive privacy strategy, not as your only privacy measure.

## Common Questions

**Q: Will my banking apps work?**  
A: Many banking apps work with sandboxed Google Play services. Some may require additional steps or may not work at all.

**Q: Can I install Google apps?**  
A: Yes, through the sandboxed Google Play services option.

**Q: How do I update GrapheneOS?**  
A: Updates are delivered automatically over-the-air, similar to regular Android updates.

**Q: Will I lose features compared to stock Android?**  
A: Some Google-specific features may not be available or work differently, but core functionality remains intact.

**Q: Is it reversible?**  
A: Yes, you can always reinstall stock Android following Google's factory image installation process.
