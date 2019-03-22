# Smart-Bicycle

To get the application up and running:

1. The API key for the android application has not been provided along with the source code due to fact that Skobbler is proprietary software. 
   Visit http://developer.skobbler.com/apikeys to generate a new API key and paste it in the AndroidManifest.xml file of the android source code.

2. Install Android studio and import the source code. Compile the source code with the API key replaced and generate a signed APK file. 
   The APK file without API key has been already included in the folder under the name of "app-release.apk". 

3. Install the arduino software, compile and upload the source code into the arduino uno based on the hardware data sheets included under the pin diagram folder of source code.

4. Pair the HC-05 bluetooth module and proceed with the usage of the application.
