ApsalarDemoiOSApp
=================

Source code for Apsalar SDK integration

=================
README
=================
Download the Apsalar iOS SDK Demo App. There are 3 examples of event instrumentation included. You may run the application on Simulator.

Built on Xcode version 4.5.1.

Under iOS-SDK-4.1.3U, view:

- Apsalar.js
- Apsalar.h
- libApsalar.a

Under Apsalar folder in the Apsalar project, view:

- ApsalarAppDelegate.m
- ApsalarDetailViewController.m

In Frameworks, view:

- AdSupport.framework
- Security.framework
- SystemConfiguration.framework
- libsqlite3.0.dylib

For examples of event instrumentation:

In ApsalarAppDelegate.m, view the methods 

- (void)applicationDidBecomeActive:(UIApplication *)application
- (BOOL)application:(UIApplication *)application openURL:(NSURL *)url sourceApplication:(NSString *)sourceApplication annotation:(id)annotation

In ApsalarDetailViewController.m, view the method

- (void)viewDidLoad
