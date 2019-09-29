# Flutter Media Permission Handler

Forked from [flutter_permission_handler](https://github.com/BaseflowIT/flutter-permission-handler) to deal with the following issue:

Using the base package, the app-store would reject your app unless you had specified a description for every single ios permission covered in the package. There is still the same behavior here but because all the non media permission were removed, the only description that you must still provide are those five:
 
 `NSPhotoLibraryUsageDescription`
 `NSMicrophoneUsageDescription`
 `NSCameraUsageDescription`
 `kTCCServiceMediaLibrary`
 `NSAppleMusicUsageDescription`
 
 There was no changes made to the android part of the package
 
 Please check out the original package readme, you may find some intresting information or answers to potential questions.
