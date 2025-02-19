# Flutter Media Permission Handler

Forked from [flutter_permission_handler](https://github.com/BaseflowIT/flutter-permission-handler) to deal with [this](https://github.com/BaseflowIT/flutter-permission-handler/issues/26) issue:

Using the base package, the app-store would reject your app unless you had specified a description for every single ios permission covered in the package. There is still the same behavior here but because all the non media permission were removed, the only description that you must still provide are those five:
 
 `NSPhotoLibraryUsageDescription`
 `NSMicrophoneUsageDescription`
 `NSCameraUsageDescription`
 `kTCCServiceMediaLibrary`
 `NSAppleMusicUsageDescription`
 
 Note: if you want to save images to the photo app, you may also need to add the `NSPhotoLibraryAddUsageDescription` for the newer version of ios
 
 There was no changes made to the android part of the package
 
 Please check out the original package readme, you may find some intresting information or answers to potential questions.

## Using this package

If you want to use this package in your flutter project, add this to your `pubspec.yaml`
```yaml
dependencies:
  
  ....
  
  media_permission_handler:
    git: 'git://github.com/tGautot/flutter-media-permission-handler.git'

  ....
```

Please note that I created this package in a few hours from a fork, it has not been tested at all on ios, there is no guarantee of it working properly until I do (or someone else).


Do not hesitate to share anything
