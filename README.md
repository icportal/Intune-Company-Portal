## Download Intune Company Portal

Follow the steps below to install the Company Portal for Windows using the MSI installer. If you're distributing the client across an organization, the `msiexec` command can be used in the terminal to perform the installation.

1. Download the correct version of the Company Portal installer that matches your system architecture:

* **[Windows 64-bit](*)**  *(most commonly used)*
* **[Windows 32-bit](*)**
* **[Windows ARM64](*)**

2. Start the installer by double-clicking the file you downloaded.

3. When the welcome screen appears, select **Next**.

4. To accept the license agreement, check the box labeled **I accept the terms in the License Agreement**, then choose **Next**.

5. Under Installation Scope, select one of the following:

* **Install just for you**: Installs the Company Portal in a user-specific directory, making it accessible only to your account. No admin privileges are required.

* **Install for all users of this machine**: Installs the Company Portal for the entire system so that it's available to all user accounts. Requires administrative rights.

6. Click **Install** to begin installing the application.

7. After the setup completes, select **Finish**.

8. If you left the **Launch Company Portal when setup exits** option enabled, the app will launch automatically. Otherwise, you can start it manually by searching for **Company Portal** from the Start menu.

Before connecting to your apps or devices via Windows, ensure the following requirements are met:

* An active internet connection

* A supported Windows OS version:

  * Windows 11
  * Windows 10
  * Windows Server 2022
  * Windows Server 2019
  * Windows Server 2016

* .NET Framework version 4.6.2 or later. This might need to be manually installed on some builds of Windows 10 or on Windows Server 2016. Visit the official .NET Framework download page to get the latest version.

### Android

Install the Company Portal app for Android from any of the following sources:

* [Portal AppStore](*)
* [Google Play](*)
* [Amazon Appstore for Android](*)

If these app stores are not accessible, or if you're using a device that doesn't support Google Mobile Services, you can [download Microsoft Intune Company Portal for Android](*) and sideload the app manually. Keep in mind that manually installed apps don’t receive automatic updates or security patches, so make sure to check and update it regularly.

In the People's Republic of China, the Google Play Store is not available. You can instead install the Company Portal app through selected Chinese app marketplaces.

### iOS

Get the Company Portal app for iOS via the [Apple App Store](*).

### macOS

To install the Company Portal on macOS, download it directly from [Enroll my Mac](*). Clicking this link initiates the download of the installer package immediately.

## Sign in to app

There are three different ways you can sign in to the Company Portal:

* Use your work or school email and password.
* Sign in using a certificate (if your organization supports it).
* Authenticate from another device.

For the best experience, follow the sign-in method recommended by your organization.

### Sign in with school or work account

1. Launch the app and tap **Sign In**.
2. Enter the email address linked to your school or work account, then tap **Next**.
3. Provide your password and tap **Sign In**.
4. Wait while your credentials are being verified. Once complete, you'll gain access to the app’s features and organizational resources.

### Sign in with certificate

This option is available only if your organization supports certificate-based sign-in and you already have a certificate configured.

1. Open the Company Portal app on your device.
2. Type in the email address linked to your work or school account, then tap **Next**.
3. Choose **Sign in with a certificate**.
4. Tap **Continue** to proceed with the selected certificate.
5. The app will validate the certificate. Once verified, you'll have access to your organization's resources and the app’s full features.
