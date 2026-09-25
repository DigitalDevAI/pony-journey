# App Store Preparation Status

## Completed in this build
- Local/offline-capable game assets
- Native WKWebView shell source
- JavaScript/native message bridge
- Native haptic feedback bridge
- Safe-area handling
- App lifecycle save hook
- Xcode assembly instructions
- Browser/PWA build retained for Netlify

## Still required before submission
- Final Apple Developer account/team
- Final bundle identifier
- App icon set and launch assets
- Privacy policy URL/content appropriate to actual data collection
- App Store metadata and screenshots
- Physical-device testing
- Accessibility testing
- Performance/memory testing
- TestFlight beta
- Xcode archive/signing
- App Store Connect upload and review

Apple's current App Review Guidelines require submissions to be complete and functional, and guideline 4.2 says an app should provide an app-like experience beyond a repackaged website. The native shell therefore bundles the game locally and adds native interaction rather than simply pointing to the Netlify URL.
