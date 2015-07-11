#  Hello Cordova Media
Simple library  for cordova-plugin-media

## Feature
 play/stop feature with button.

## library 
 hello_media/js/myaudio.js  
 myAudio.play("path/to/sound/file", a_callback_when_finished);  
 myAudio.stop();  

## Button sample
 hello_media/js/index.js  
 app.audioButton();  

## Settings
 Add following tags in config.xml  
 ```xml
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
 ```
 Add following tags in platforms/android/AndroidManifest.xml  
 ```xml
 <uses-permission android:name="android.permission.RECORD_AUDIO" />  
 <uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />  
 <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />  
 ```

### cordova-plugin-media
 https://github.com/apache/cordova-plugin-media

### License
MIT



