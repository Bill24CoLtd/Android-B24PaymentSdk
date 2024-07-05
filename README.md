# B24PaymentSdk

### Light Mode
<table>
  <tr>
    <td>Payment Method Screen</td>
     <td>KHQR Screen</td>
     <td>Success Screen</td>
  </tr>
  <tr>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338811/image-preview" width=270 height=480></td>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338812/image-preview" width=270 height=480></td>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338813/image-preview" width=270 height=480></td>
  </tr>
 </table>
 
 ### Dark Mode
 <table>
  <tr>
    <td>Payment Method Screen</td>
     <td>KHQR Screen</td>
     <td>Success Screen</td>
  </tr>
  <tr>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338814/image-preview" width=270 height=480></td>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338815/image-preview" width=270 height=480></td>
    <td><img src="https://api.apidog.com/api/v1/projects/374432/resources/338816/image-preview" width=270 height=480></td>
  </tr>
 </table>

 # How to use : 
 - add file b24paymentsdk.arr to your project- 
 - in build.gradle add some dependency
     - implementation 'com.squareup.retrofit2:retrofit:2.9.0'
     - implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
     - implementation 'com.squareup.picasso:picasso:2.8'
     - implementation 'com.google.code.gson:gson:2.10.1'
     - implementation 'com.squareup.okhttp3:logging-interceptor:4.11.0'
     - implementation 'pl.droidsonroids.gif:android-gif-drawable:1.2.28'
     - implementation  ('io.socket:socket.io-client:2.1.0') {
        // excluding org.json which is provided by Android
        exclude group: 'org.json', module: 'json'

    }