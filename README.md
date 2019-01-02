# deeplink-fallback

Simple redirection to Android / iOS app store when mobile app link is not recognized or not installed on the device.

Mandatory GET data:  
- `deeplink`: the mobile app deep link encoded URI (ex: `twitter%3A%2F%2Fuser%3Fscreen_name%3DTwitter%20`)
- `playstore`: the app id on the Google Play Store (ex: `com.twitter.android`)
- `itunes`: the app id on iTunes App Store (ex: `id333903271`)

(Full link example: https://naei.github.io/deeplink-fallback/?deeplink=twitter%3A%2F%2Fuser%3Fscreen_name%3DTwitter%20&playstore=com.twitter.android&itunes=id333903271)