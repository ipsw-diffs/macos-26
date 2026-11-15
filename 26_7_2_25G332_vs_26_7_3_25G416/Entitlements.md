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


