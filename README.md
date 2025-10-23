Developed TikTok-like video sharing app with built-in video compression, media storage, and intuitive user interface.
Published to the Google Play Store with 10+ active users and real-time video upload, streaming, and interaction features.
Worked in a small team and was responsible for managing backend utilities - ensuring scalable, cloud-hosted data management, and secure authentication with Firebase/OAuth Authentication for backend services and Cloudinary for media storage.

Challenges: The main challenge was navigating a Java environment setup issue that prevented Google Sign-In authentication. The primary obstacle was that JAVA_HOME wasn't configured 
and keytool commands weren't available in the system PATH, blocking our ability to obtain the required SHA-1 fingerprint. I had to manually locate Android Studio's built-in Java 
installation and deal with some PowerShell syntax issues when executing commands. The most significant challenge was understanding that the misleading SecurityException: Unknown calling 
package name error was actually caused by a missing SHA-1 fingerprint registration in Firebase Console, not a code configuration issue. Through systematic troubleshooting, we successfully
extracted the SHA-1 fingerprint and registered it in Firebase, which should resolve the Google Sign-In authentication problems.
