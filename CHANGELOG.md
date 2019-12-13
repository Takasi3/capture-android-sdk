### Version 3.0.1
- Bug fixes

### Version 2.5.17
- Bug fixes

### Version 3.0.0
- SDK is compiled at Android version 28. This version of the SDK supports 'android.support' and 'androidx' libraries. This version is recommended for projects compiling at Android 28 and above.

### Version 2.5.16
- Minor bug fixes for Document and Face capture screens

### Version 2.5.15
- Minor Bug fixes

### Version 2.5.14
- Bug fix for Document Capture screen in Andriod 10 devices

### Version 2.5.13
- Security improvements

### Version 2.5.12
- Added precise location exif data from FusedLocationProvider using Google location APIs

### Version 2.5.11
- Added custom colors for face circle - Override face_capture_circle_success to change the color when face is detected successfully and face_capture_circle_failure to change the color when face is not detected or face is detected with errors in colors.xml

### Version 2.5.10
- Converted all png images to vector images - results in significant reduction in SDK size

### Version 2.5.8
- Fix blur issues in Honor N9 and Vivo 1814 phones
- Add sentry for logging crashes and errors

### Version 2.4.8
- Added support for x86_64
- Bug fixes

### Version 2.4.7
- Added provision for selfie-selfie match API call
- Added optional PDF response to document capture
- Bug fixes

### Version 2.4.6
- Added QR scanner module
- Added helper method to make validation API call

### Version 2.4.5
- SDK Size optimisation

### Version 2.4.4
- Added setter methods to set custom strings for all texts shown
- Bug fixes

### Version 2.4.3
- Camera improvements to improve the picture quality.
 
### Version 2.4.2
- Liveness URL can be now be configured 
- Optional Camera Flip button added for Face capture
- Bug fix w.r.t permission handling 

### Version 2.4.1
- Minor SDK size optimisation changes

### Version 2.4.0
- Added headers support in makeOCRCall and makeFaceMatchCall
- Changed Error enum to HVError Object
- Changed error structure to return server errors directly
- Added camera permission handling in the SDK
- Fixed bug with document padding


### Version 2.3.4
- Minor bug fix in HVNetworkHelper
- Added support for error codes for API calls

### Version 2.3.3
- Added HVNetworkHelper to make network requests within the app.

### Version 2.3.2
- Added mixpanel support with the SDK
- Added exif parameters for all images captured using the SDK

### Version 2.3.1
- Issue fixes with native camera used in the SDK

### Version 2.3.0
-  Added optional Instruction Pages for Face and Document Capture
-  Added Review Page for Document capture
-  Added provision for style customisation for all prominent labels and buttons
-  Added customisation options for strings and colors used in the SDK
-  Added optional 'clientID' field to liveness calls

### Version 2.2.0
- Added AUTHENTICATION_ERROR for wrong appID and appKey
- UI changes in HVDocsActivity
- Modified localisation support to ease integration with react native
- Performance improvements
- Minor bug fixes

### Version 2.0.3
- Fixed issue with multiple permissions in Manifest file

### Version 2.0.1
- Crash Fix in HVDocsActivity on multiple clicks

### Version 2.0.0
- Liveness Module Added
- UI revamp in both document and face capture Activities
- Moved the 'Document' enum to 'HyperSnapParams.Document'

### Version 1.0.8
- Nexus 6P Face Detection Issues Fixes

### Version 1.0.7
- Better quality of captured documents because of lesser compression

### Version 1.0.6
- Camera Orientation fix for Nexus devices
- Renderscript support needs to be added to defaultConfig in app's `build.gradle`

### Version 1.0.4
- DocumentActivity returning image path with improper extension
