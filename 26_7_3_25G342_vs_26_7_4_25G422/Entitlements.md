## 🔑 Entitlements

### filesystem

### NotificationCenter

> `/System/Library/CoreServices/NotificationCenter.app/Contents/MacOS/NotificationCenter`

```diff

 		<string>kTCCServiceSystemPolicyAppBundles</string>
 		<string>kTCCServiceSystemPolicyAppData</string>
 	</array>
+	<key>com.apple.private.usernotifications.content-extension-host</key>
+	<true/>
 	<key>com.apple.private.usernotifications.forwarding</key>
 	<true/>
 	<key>com.apple.private.windowmanager</key>

```
### managedappdistributionagent

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributionagent`

```diff

 	<true/>
 	<key>com.apple.private.security.bootpolicy.readonly</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.managedappdistributionagent</string>
+	</array>
 	<key>com.apple.private.security.storage.installcoordinationd</key>
 	<true/>
 	<key>com.apple.private.sqlite.sqlite-encryption</key>

```
### managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

```diff

 	</array>
 	<key>com.apple.private.remotemanagement.subscriber</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.managedappdistributiond</string>
+	</array>
 	<key>com.apple.private.store.privileged.task</key>
 	<true/>
 	<key>com.apple.private.system_installd.connection</key>

```
### com.apple.StreamingUnzipService.privileged

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/Contents/MacOS/com.apple.StreamingUnzipService.privileged`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.private.vfs.entitled-reserve-access</key>

```
### com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.private.vfs.entitled-reserve-access</key>

```
### com.apple.StreamingUnzipService.privileged

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/Current/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/Contents/MacOS/com.apple.StreamingUnzipService.privileged`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.private.vfs.entitled-reserve-access</key>

```
### com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/Current/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.private.vfs.entitled-reserve-access</key>

```
### bird

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/Support/bird`

```diff

 	<true/>
 	<key>com.apple.private.foundation.fileprovideridentifier</key>
 	<string>com.apple.bird</string>
+	<key>com.apple.private.genstore.icd-fpfs-migration</key>
+	<true/>
 	<key>com.apple.private.iaaccounts</key>
 	<true/>
 	<key>com.apple.private.kernel.global-proc-info</key>

```
### tmdiagnose

> `/usr/bin/tmdiagnose`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.backupd.session</key>
+	<string>tmdiagnose</string>
+</dict>
+</plist>
 

```


