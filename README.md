# FirebaseMultiLogin
Multi Login using Firebase Ui

add the following in your gradle

implementation 'com.firebaseui:firebase-ui-auth:6.2.0'

  // Required only if Facebook login support is required
  // Find the latest Facebook SDK releases here: https://goo.gl/Ce5L94
    
    
 implementation 'com.facebook.android:facebook-android-sdk:5.0.0'
 
 obtain facebook app id and secret id, add it in strings.xml
 
  <string name="facebook_application_id" translatable="false">fb_app_id</string>
    <!-- Facebook Application ID, prefixed by 'fb'. Enables Chrome Custom tabs. -->
        <string name="facebook_login_protocol_scheme" translatable="false">fb<fb_app_id></string>


