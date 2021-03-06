---
nav_title: Sample Apps
platform: iOS
page_order: 9

---
# Sample Apps

Braze's SDKs each come with a sample application within the repository for your convenience. Each of these apps is fully buildable so you can test Braze features alongside implementing them within your own applications. Testing behavior within your own application versus expected behavior and codepaths within the sample applications is an excellent way to debug any problems you may run into.

## Building the Stopwatch Test Application
Braze's test application within the [iOS SDK Github repository][1] is called Stopwatch. Follow the instructions below to build a fully functional copy of it alongside your project.

1. Create a new ["App Group"][25] and note the production API key.
2. Place your production API key within the appropriate field in the `AppDelegate.m` file.

>  Push notifications for the iOS test application requires additional configuration. See the [iOS Push Documentation][7] for details.

[1]: https://github.com/appboy/appboy-ios-sdk "Appboy iOS Github Repository"
[25]: {{site.baseurl}}/developer_guide/platform_wide/app_group_configuration/#creating-your-app-group-in-my-apps
[7]: {{site.baseurl}}/developer_guide/platform_integration_guides/ios/push_notifications/integration/
