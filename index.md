---
layout: default
title: "README"
---
## Requirements

* Xcode 9 or later
* Minimum deployment target of iOS 10
* Compile the target application for arm64, not armv7.

## Get Started

1. Provision Apps with [Apple]({{ site.baseurl }}/get-started/apple.html).
1. [Create your apps]({{ site.baseurl }}/get-started/create-apps-overview.html) in the MobilePush Marketing Cloud app.
1. [Download the SDK]({{site.codeurl}}).
1. [Implement the SDK]({{ site.baseurl }}/get-started/implement-sdk.html).
1. Implement [push notifications]({{ site.baseurl }}/push-notifications/push-notifications.html) for your apps.
  * Create a [test audience](https://help.salesforce.com/articleView?id=mc_mp_create_an_audience.htm&type=5).
  * Create a [test message](https://help.salesforce.com/articleView?id=mc_mp_outbound_message.htm&type=5) in the Marketing Cloud MobilePush app.
1. Add optional purchased features, such as [CloudPages]({{ site.baseurl }}/inbox/inbox.html) and [Location Services]({{ site.baseurl }}/location/geolocation-overview.html), to your apps.

> You can use an iOS simulator for testing, but the simulator will not receive push messages as part of the testing process.
You must test push using Apple's production environment, not a sandbox environment. Build and run on a device installed with a release build.

## Additional Resources

* The <a href="https://help.salesforce.com/articleView?id=mc_mp_mobilepush.htm&type=5" target="_blank">Marketing Cloud MobilePush Documentation</a> contains information on the Marketing Cloud MobilePush app, including information on associating MobilePush with a mobile app.
* The Marketing Cloud provides the <a href="https://github.com/salesforce-marketingcloud/LearningAppIos" target="_blank">Learning App for iOS</a> that implements features of the SDK to allow you to explore how a native app implements the MarketingCloudSDK.
* [Sign up for email updates about the iOS MarketingCloudSDK](http://pub.s1.exacttarget.com/2ujjacpet3t).<br/><br/>

## Release History

For releases prior to 5.0.0, see: <a href="http://salesforce-marketingcloud.github.io/JB4A-SDK-iOS/" target="_blank">Prior Release Documentation</a>

#### Version 5.0.0
_Released January 22, 2017, correlating with the Marketing Cloud January 2018 release_

* We redesigned the SDK to make it easier to integrate than ever before. This release includes a slimmer API that makes it easier to add Marketing Cloud features to your app. Existing users can upgrade their version to take advantage of the improved SDK. New users can follow the existing Getting Started directions to get the SDK up and running.

* We updated the SDK for full support of iOS 11.
