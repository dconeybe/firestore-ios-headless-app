## Barebones iOS test app for Firestore bugs.

By: dconeybe@google.com

This app was created to quickly test out bugs in the Firestore iOS SDK.
It was initially motivated by https://github.com/firebase/firebase-ios-sdk/issues/5235.

## Usage

1. Clone this Git repository
1. Download `GoogleService-Info.plist` from the Firebase console.
1. Copy `GoogleService-Info.plist` into the `FriendlyEats` subfolder.
1. Run `pod update`
1. Create a "restaurants" collection with a document named "1YkESDBLGz9vEmphIUFJ" in it via the Firebase console (or other means).
1. Open the generated `FriendlyEats.xcworkspace` in Xcode.

The Firebase project must be configured so that the Firestore database rules allow unauthenticated access.
