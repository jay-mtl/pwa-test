
# Angular PWA vs Flutter

## Angular PWA

### Pro and cons

|                       Pros                       |                          Cons                    |
|--------------------------------------------------|--------------------------------------------------|
|Use angular that is a well know tech at MSL       |Don’t handle all native app mobile os intéractions (not a issue for the project since we don’t need them)|
|Used by big companies Upwork, Deutsche Bank, Paypal|Not very practical for testing on your mobile, can’t be tested in a emulator only in the browser (No so easy to create an apk), it'not native|
| |Seems to need a website to use the mobile app

### Features


|Geo localisation|:heavy_check_mark: |https://stackoverflow.com/questions/62632147/how-to-turn-on-gps-programmatically-from-an-angular-pwa-application|
|-------|--------|-------|
| QR code/NFC| :heavy_check_mark:|https://googlechrome.github.io/samples/web-nfc/|
|Bluetooth|No|


## Flutter

Flutter for web is mobile style oriented (your web app will look a bit as a mobile app don’t know if it’s a con in our case)


### Pros and cons

|                       Pros                       |                          Cons                    |
|--------------------------------------------------|--------------------------------------------------|
|Used by big companies (created by Google)|Dart programming language ( but very similar to javascript)|
|Lot of components are available natively for coding your app (you can do stuff very fast)|No SEO friendly|
|Can be also used for the web (almost natively) | |
|Compatibility with AWS serverless is very good (it’s easy to bundle your flutter web in a S3 bucket) | |
|The hype has passed and it’s still trendy | |
|Well integrated with google materials | |


### Features

|Geo localisation|:heavy_check_mark: |
|-------|--------|-------|
| QR code/NFC| :heavy_check_mark:|
|Bluetooth|:heavy_check_mark:|