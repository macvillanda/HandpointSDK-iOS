## How to release the HandpointSDK for iOS

Commit and push all your work first

`git tag -a <version> -m "<version> - Minified changelog"`

`git push origin --tags`

`pod trunk push HandpointSDK.podspec`