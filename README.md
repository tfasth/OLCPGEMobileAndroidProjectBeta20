# OLC Pixel Game Engine Mobile Android Project Beta 2.1.0
<p>Correct support for Older SDK, Engine now supports <b>SDK 21 (Lollipop 5.0 - 5.0.2) to SDK 31/32 (Android 12 (S) 12.0). <br/>NOTE Android SDK 33 is also known as Android 13 Beta has been tested</b></p>
<p><b>Added a FileHandler as accessing Android/iOS App Storage is not east... well it is now :)</b></p>
<p>Thank you to @VasCoder check out: <a href="https://github.com/tfasth">https://github.com/tfasth</a></p>
<p>Thank you to @YouGotJoshed check out: <a href="http://sig.projectdivar.com/sigonasr2/">http://sig.projectdivar.com/sigonasr2/</a></p>
<p>Please follow this steps folks:</p>
<p>1: Launch Visual Studio 2022 Installer</p> <!--Thanks @Pirate Voxel -->
<p>2: Click Modify</p>
<p>3: Install Mobile Development with C++ </p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/5812774f-54fa-4875-90ec-4f2e2d7a9899' />
</p>
<p>5: Install Java 17: https://www.oracle.com/java/technologies/downloads/#java17</p>
<p>6: Open Command Prompt in Administrator Mode, enter: setx -m JAVA_HOME "C:\Program Files\Java\jdk-17"</p>
<p>7: Open Visual Studio -->Tools-->Options-->Cross Platform. Update your SDK, NDK and Java Path as shown</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/77f70549-0d99-4f1e-9415-42fda6a99b20' /></p>
<p>8: Copy the <a href="https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/blob/master/OLCPGEMobileAndroidProjectBeta210.zip">OLCPGEMobileAndroidProjectBeta210.zip</a> to your Projects Templates folder. Example: C:\Users\<i>your username</i>\OneDrive\Documents\Visual Studio 2022\Templates\ProjectTemplates</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/6b31d28f-0fd1-4fb2-969e-912927ba32b8' /></p>
<p>9: Put your Android phone into Development Mode: https://developer.android.com/studio/debug/dev-options</p> <!--Thanks @Pirate Voxel -->
<p>10: Run Visual Studio 2022 in Admin Mode</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/daa5e9a6-309c-4b48-be44-c897ff54b6b2' /></p>
<p>11: Select Create Project</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/c720f822-4e62-417c-8322-b38f8f102059' /></p>
<p>12: Select OLC Pixel Game Engine Mobile BETA 2.1.0 for Android</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/7a5abc8d-f4e4-44a0-8897-e15c63cfefc6' /></p>
<p>13: Give your game a cool name. <b>NO SPACES</b> Do not start your project with a number: i.e. 3DShapes, 4Runner</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/4c13b4b4-d8c5-4e27-bc5b-c4caa653201f' /></p>
<p>14: Connect your phone and rebuild the solution, enjoy OLC Pixel Game Engine Mobile 2.0!</p>
<p><img src='https://github.com/Johnnyg63/OLCPGEMobileAndroidProjectBeta20/assets/96908304/b5e9e72e-73cf-4fe1-ba66-7df31790fce9' /></p>

<p><b>Beta Support Details</b></p>
<p>
<ul>
  <li>2.01: BETA Port code from olcPixelGameEngine.h to olcPixelGameEngine_mobile.h</li>
  <li>2.02: Corrected support for X86</li>
  <li>2.03: Update EventManager to handle, Touch, Mouse and Keyboard events</li>
  <li>2.04: Corrected Touch offset, added 1 touch point, unlinked Mouse & Touch Events</li>
  <li>2.05: Sensors Support added</li>
  <li>2.06: Multi Touch Support</li>
  <li>2.06a: Added basic mouse support for Android Emulator</li>
  <li>2.07: Updated SIMD_SSE for Intel Atom devices, Updated GetTouch() to default to touch point zero</li>
  <li>2.07a: Corrected two small bugs in main.cpp</li>
  <li>2.08: Added ClearTouchPoints(int8_t startIndex = 0) for clearing of touch points at index x, some bug fixes too<br/> <i>Added Demos folder with some demos. Just Copy and Paste the code into main.cpp</i></li>
  <li>2.09: Added Demos folder with some demos</i>
	<br/> Added: FileManager: for gaining acccess to the Andriod Assets APK and iOS Zip Packages
				<br/> app_LoadFileFromAssets()
				<br/> app_ExtractFileFromAssets()
				<br/> app_GetInternalAppStorage()
				<br/> app_GetExternalAppStorage()
				<br/> app_GetPublicAppStorage()
				<br/> SmartPtr filehandler
				<br/> LoadFileFromAssets()
				<br/> ExtractFileFromAssets()
				<br/> GetInternalAppStorage()
				<br/> GetExternalAppStorage()
				<br/> GetPublicAppStorage()
  </li>
  <li>2.10: Removed ASensor_getHandle() as it only supports SDK 29 and higher. Updated project to support SDK 21 to SDK32, Thank you @VasCoder</li>
</ul>
	
</p>
<p>
	<b>Apple Platforms will not see these updates immediately</b><br/>
	<b>Starting on iOS next Saturday 22nd July 2023</b>
</p>
