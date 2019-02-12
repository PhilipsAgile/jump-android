#Introduction 
The Janrain Mobile libaries for Android is available open-source under a Berkeley license, as found in the LICENSE file.

Current Version : 7.1.1

Upgrading to v7.1.1 from v7.1.0
NOTE: The library now forces HTTP 1.1 or 2.0 connections using TLS version 1.2 only when communicating to all Janrain
Servers Library dependencies updated:
'com.android.support:support-v4:27.1.0'
files('libs/org.apache.http.legacy.jar')
'com.squareup.okhttp3:okhttp:3.10.0'
'com.squareup.okhttp3:okhttp-apache:3.10.0'
'com.squareup.okio:okio:1.14.0'
'net.openid:appauth:0.7.0'



#Android Studio Import Guide
To import jump to your project, open build.gradle file and add below dependency:
implementation 'com.janrain.android:jump-android:7.1.1'


#Artifactory publish Guide
Execute below command to publish jump-android-release.aar to artifactory:
./gradlew artifactoryPublish