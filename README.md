#  Hello Cordova Media
sample code for cordova-plugin-media

## Settings
 Add following tags in config.xml  
 <platform name="android">  
  <feature name="Media">  
  <param name="android-package" value="org.apache.cordova.media.AudioHandler"/>  
  </feature>  
 </platform>  
 <platform name="ios">  
  <feature name="Media">  
   <param name="ios-package" value="CDVSound"/>  
  </feature>  
 </platform>  
 
 Add following tags in platforms/android/AndroidManifest.xml  
 <uses-permission android:name="android.permission.RECORD_AUDIO" />  
 <uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />  
 <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />  





