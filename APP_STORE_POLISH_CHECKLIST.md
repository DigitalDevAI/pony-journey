# App Store Polish Checklist

## Implemented in source
- Local bundled game assets
- SwiftUI shell
- WKWebView
- Native haptics using Core Haptics with fallback
- Game Center authentication hook
- Leaderboard submission hook
- Achievement submission hook
- App lifecycle save hook
- Safe-area handling
- Portrait + landscape support
- Reduced-motion support
- Focus-visible controls
- No unnecessary sensitive permissions
- Browser/PWA version retained

## Required in Xcode/App Store Connect
- Final bundle ID/team/signing
- Final icons and launch assets
- Game Center leaderboard and achievement records
- Privacy details and policy URL based on actual data practices
- Age-rating questionnaire
- App Store screenshots and description
- Physical device QA
- Crash/performance testing
- TestFlight
- Final archive and submission

Apple says App Store submissions must be complete, functional and tested, and its current 4.2 guidance emphasizes a distinctive app-like experience rather than a repackaged website. This build therefore uses local game assets and native iOS features rather than opening the Netlify URL.
