======================================================================
SHALOM BHAJAN - iOS (.ipa) & iPhone Installation Guide
Package / Bundle ID: com.shalom.bhajanmandali.anand
App Name: SHALOM BHAJAN (ગાયનટોળી ભજનાવલી)
======================================================================

Because Apple's iOS compiler (Xcode) only runs on macOS, here are the 3 best ways
to create and install the iOS app on iPhones & iPads from your Windows PC:

----------------------------------------------------------------------
METHOD 1: Build the .IPA on Windows for FREE using GitHub Actions (No Mac Needed!)
----------------------------------------------------------------------
This project already includes an automated macOS build script at:
.github/workflows/build_ipa.yml

1. Create a free account at https://github.com and create a new Repository.
2. Upload the contents of this "ShalomBhajan_iOS" folder to your repository.
3. Click the "Actions" tab at the top of your GitHub repository.
4. Click "Build iOS IPA (SHALOM BHAJAN)" -> "Run workflow".
5. In ~2 minutes, GitHub's free cloud Mac will compile the project and give you
   a downloadable "SHALOM_BHAJAN.ipa" file under Artifacts!
6. To install "SHALOM_BHAJAN.ipa" on your iPhone from Windows for free, use
   Sideloadly (https://sideloadly.io/) or AltStore (https://altstore.io/) with
   your free Apple ID.

----------------------------------------------------------------------
METHOD 2: Instant iPhone Home Screen App (Zero Apple Fees, Never Expires)
----------------------------------------------------------------------
Unlike Android, Apple revokes free sideloaded .ipa apps every 7 days unless you
pay Apple $99/year. To install SHALOM BHAJAN on 100+ congregation iPhones for
100% FREE so it NEVER expires:

1. Host "ShalomBhajan/index.html" on a free static link (such as GitHub Pages or Netlify).
2. Open that link in Safari on any iPhone.
3. Tap the Share button (square with up arrow) -> "Add to Home Screen".
4. It installs onto the iPhone Home Screen with the SHALOM BHAJAN icon, launches
   fullscreen without Safari bars, and works 100% offline forever!

----------------------------------------------------------------------
METHOD 3: Build on a Mac with Xcode
----------------------------------------------------------------------
1. Open "ShalomBhajan.xcodeproj" in Xcode on a Mac.
2. Click "ShalomBhajan" in the left sidebar -> "Signing & Capabilities".
3. Select your Apple ID under "Team".
4. Connect your iPhone and click the Play (Run) button, or click
   Product -> Archive -> Distribute App to export the signed .ipa file.
