# Android-Mqtt-Client
This is a simple Android application that can comunicate with a MQTT Broker like CloudMQTT. In this project you can look at subscribing and publishing using the Paho Android Service.


## AndroidManifest.xml:

### Permissions

   ```
   <uses-permission android:name="android.permission.WAKE_LOCK" />
   <uses-permission android:name="android.permission.INTERNET" />
   <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
   ```
   
### Services 
(before </ application >)

   ```
   <service android:name="org.eclipse.paho.android.service.MqttService" />
   ```
   
## Dependencies (-> build.grandle(Module:app)

```
 implementation 'org.eclipse.paho:org.eclipse.paho.android.service:1.1.1'
 implementation 'org.eclipse.paho:org.eclipse.paho.client.mqttv3:1.1.0'
```

## Broker: 

https://www.cloudmqtt.com/
