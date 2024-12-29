# OTP Auth for Raycast

A Raycast extension that provides quick access to your OTP Auth tokens. This extension integrates with [OTP Auth](https://apps.apple.com/us/app/otp-auth/id1471867429) by Roland Moers, allowing you to view your 2FA codes directly from Raycast.

![otp-auth-1](https://github.com/user-attachments/assets/6a500461-b3a0-41fa-8ca3-4ce04a638685)
![otp-auth-2](https://github.com/user-attachments/assets/fae5591d-4737-482c-9238-e4f3a21c07d3)
![otp-auth-3](https://github.com/user-attachments/assets/c10427bf-3634-4c52-92a0-86fa00c7b894)



## Requirements

- [OTP Auth for Mac](https://apps.apple.com/us/app/otp-auth/id1471867429) must be installed
- The extension will not work without the official Mac app installed
- This extension is not meant to replace the official [OTP Auth Mac app](https://apps.apple.com/us/app/otp-auth/id1471867429).
- We strongly encourage you to support the developer by purchasing the premium version of OTP Auth, which provides additional features like:
  - Encrypted iCloud Sync
  - Notification Center widget
  - Safari extension
  - Touch ID security
  - Encrypted backups
  - And more!

## Features

- Quick access to your OTP Auth tokens through Raycast
- Supports iCloud backup paths for seamless integration
- Works with your existing OTP Auth database

## Technical Details

This extension uses [decrypt-otpauth-ts](https://www.npmjs.com/package/decrypt-otpauth-ts) under the hood to securely read your OTP Auth database.

## Support

For issues related to the OTP Auth app itself, please contact the original developer through the App Store. For extension-specific issues, please use the GitHub issues.
