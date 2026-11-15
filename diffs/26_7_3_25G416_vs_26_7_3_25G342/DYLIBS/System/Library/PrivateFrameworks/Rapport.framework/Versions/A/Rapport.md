## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport`

```diff

-716.700.11.0.0
-  __TEXT.__text: 0xa9e60
-  __TEXT.__auth_stubs: 0x1c30
-  __TEXT.__objc_methlist: 0x8f64
-  __TEXT.__const: 0x3ad8
-  __TEXT.__cstring: 0x14bac
-  __TEXT.__gcc_except_tab: 0x16e0
-  __TEXT.__oslogstring: 0x85d
-  __TEXT.__swift5_typeref: 0x7e3
-  __TEXT.__swift5_capture: 0x118
-  __TEXT.__swift5_fieldmd: 0x800
-  __TEXT.__constg_swiftt: 0x6fc
-  __TEXT.__swift5_reflstr: 0x36c
-  __TEXT.__swift5_proto: 0x128
-  __TEXT.__swift5_types: 0x98
+716.700.12.0.0
+  __TEXT.__text: 0xe0a9c
+  __TEXT.__auth_stubs: 0x1f20
+  __TEXT.__objc_methlist: 0x9c5c
+  __TEXT.__const: 0x3e38
+  __TEXT.__cstring: 0x12acc
+  __TEXT.__gcc_except_tab: 0x144c
+  __TEXT.__oslogstring: 0x22fd
+  __TEXT.__swift5_typeref: 0xb95
+  __TEXT.__swift5_capture: 0x79c
+  __TEXT.__swift5_fieldmd: 0xb00
+  __TEXT.__constg_swiftt: 0xd64
+  __TEXT.__swift5_reflstr: 0x8ec
+  __TEXT.__swift5_proto: 0x144
+  __TEXT.__swift5_types: 0xac
   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x10
-  __TEXT.__swift5_assocty: 0x40
-  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_assocty: 0x88
+  __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2aa0
-  __TEXT.__eh_frame: 0x8c8
-  __TEXT.__objc_classname: 0xc31
-  __TEXT.__objc_methname: 0x11123
-  __TEXT.__objc_methtype: 0x2d34
-  __TEXT.__objc_stubs: 0x9200
-  __DATA_CONST.__got: 0x440
-  __DATA_CONST.__const: 0x10f0
-  __DATA_CONST.__objc_classlist: 0x2a8
+  __TEXT.__unwind_info: 0x3108
+  __TEXT.__eh_frame: 0x9b0
+  __TEXT.__objc_classname: 0xc61
+  __TEXT.__objc_methname: 0x12ea3
+  __TEXT.__objc_methtype: 0x3144
+  __TEXT.__objc_stubs: 0xb180
+  __DATA_CONST.__got: 0x498
+  __DATA_CONST.__const: 0x12d8
+  __DATA_CONST.__objc_classlist: 0x2b0
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x150
+  __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3ae8
-  __DATA_CONST.__objc_protorefs: 0xe8
+  __DATA_CONST.__objc_selrefs: 0x4310
+  __DATA_CONST.__objc_protorefs: 0xf0
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0xb0
-  __AUTH_CONST.__auth_got: 0xe28
-  __AUTH_CONST.__const: 0x2bd0
-  __AUTH_CONST.__cfstring: 0x5280
-  __AUTH_CONST.__objc_const: 0x10a10
-  __AUTH_CONST.__objc_intobj: 0x2b8
+  __AUTH_CONST.__auth_got: 0xfa0
+  __AUTH_CONST.__const: 0x39d8
+  __AUTH_CONST.__cfstring: 0x4de0
+  __AUTH_CONST.__objc_const: 0x10d98
+  __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH.__objc_data: 0x850
-  __AUTH.__data: 0x8e8
-  __DATA.__objc_ivar: 0x1140
-  __DATA.__data: 0x1eb0
-  __DATA.__bss: 0x2b20
-  __DATA.__common: 0x70
+  __AUTH.__objc_data: 0xff0
+  __AUTH.__data: 0x910
+  __DATA.__objc_ivar: 0x10b0
+  __DATA.__data: 0x2118
+  __DATA.__bss: 0x2eb0
+  __DATA.__common: 0x90
   __DATA_DIRTY.__objc_data: 0x14a0
   __DATA_DIRTY.__data: 0x200
   __DATA_DIRTY.__bss: 0x30

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4704
-  Symbols:   7529
-  CStrings:  6305
+  Functions: 5675
+  Symbols:   7940
+  CStrings:  6487
 
Symbols:
+ +[RPConnection _makeIdentityWithPublicKey:identifier:type:]
+ +[RPConnection _sepPrivateKeyOfPairingIdentity:]
+ +[RPConnection _setPairingIdentity:sepPrivateKey:]
+ +[RPConnection _updateIdentity:withSEPPrivateKey:]
+ +[RPConnection _updateIdentity:withSecretKey:]
+ -[RPConnection _addInUseProcess:]
+ -[RPConnection _addSelfIdentityInfoToMessage:flags:]
+ -[RPConnection _addSharedHomeIdentityWithMessage:]
+ -[RPConnection _bonjourFlagsFromLocalDeviceFlags]
+ -[RPConnection _btPipeHighPriorityConnected]
+ -[RPConnection _btPipeHighPriorityRequestable]
+ -[RPConnection _btPipeSelfIdentifier]
+ -[RPConnection _buildFrameHeaderData:length:]
+ -[RPConnection _callAuthCompletionHandler:]
+ -[RPConnection _callPairVerifyCompletion:]
+ -[RPConnection _canPeerDecode128bit:major:minor:patch:]
+ -[RPConnection _cloudDaemonIDSDeviceIDSelf]
+ -[RPConnection _cloudDaemonOSVersionForID:]
+ -[RPConnection _companionLinkFlagsString]
+ -[RPConnection _companionLinkFlagsSyncedMask]
+ -[RPConnection _completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:]
+ -[RPConnection _completeSendMetrics:error:]
+ -[RPConnection _controlFlagsString]
+ -[RPConnection _controlFlagsSyncedMask]
+ -[RPConnection _createBleConnectTimer]
+ -[RPConnection _createOneShotTimer:handler:]
+ -[RPConnection _createRetryTimerWithDelay:]
+ -[RPConnection _createServerStartTimer]
+ -[RPConnection _createStartTimer]
+ -[RPConnection _decodeNSError:]
+ -[RPConnection _deviceCapabilitiesFlagsSyncedMask]
+ -[RPConnection _disableResolvedIdentityForSeconds:]
+ -[RPConnection _encodeNSError:intoDict:]
+ -[RPConnection _eventIDIsChatty:]
+ -[RPConnection _forgetBleConnectTimer]
+ -[RPConnection _forgetRetryTimer]
+ -[RPConnection _forgetStartTimer]
+ -[RPConnection _generatePeerIdentifierIfNeeded]
+ -[RPConnection _gestaltDeviceClassForModel:]
+ -[RPConnection _gestaltUserAssignedDeviceName]
+ -[RPConnection _getCanDecode128bit]
+ -[RPConnection _getCompanionLinkFlags]
+ -[RPConnection _getPeerStatusFlags]
+ -[RPConnection _getStatusFlags]
+ -[RPConnection _hasBtPipeHighPriority]
+ -[RPConnection _hasBtPipe]
+ -[RPConnection _hasIdentityDaemon]
+ -[RPConnection _homeKitIdentityIdentifierFromDaemon]
+ -[RPConnection _identityDaemonAddSessionPairedIdentity:]
+ -[RPConnection _identityDaemonIdentitiesOfType:error:]
+ -[RPConnection _identityDaemonIdentityOfSelfAndReturnError:]
+ -[RPConnection _identityDaemonResolveIdentityForSignature:data:typeFlags:error:]
+ -[RPConnection _identityDaemonSessionPairingIdentifier]
+ -[RPConnection _inUseProcessesToString]
+ -[RPConnection _insertBits32:newBits:mask:]
+ -[RPConnection _insertBits64:newBits:mask:]
+ -[RPConnection _isLocalDeviceCommunal]
+ -[RPConnection _linkTypeString]
+ -[RPConnection _localDeviceInfoPassword]
+ -[RPConnection _logRequestMetricsOnLinkType:length:rtt:]
+ -[RPConnection _logSendMetricsForLength:]
+ -[RPConnection _osVersionToString:]
+ -[RPConnection _pairingAppFlagsString:]
+ -[RPConnection _peerDeviceInfoSetTransportFlag:]
+ -[RPConnection _reportLargeSendContext:process:length:]
+ -[RPConnection _requestIDIsHighVolume:messageIsChatty:]
+ -[RPConnection _saveIdentityWithIDSDeviceID:message:]
+ -[RPConnection _scrubPskData]
+ -[RPConnection _sendFrameType:bodyObject:]
+ -[RPConnection _sendFrameType:dictionaryObject:]
+ -[RPConnection _setAppInfoPeer:]
+ -[RPConnection _setCanDecode128bit:]
+ -[RPConnection _setCompanionLinkFlags:]
+ -[RPConnection _setPeerAccountAltDSID:]
+ -[RPConnection _setPeerAccountID:]
+ -[RPConnection _setPeerActiveUserAltDSID:]
+ -[RPConnection _setPeerActivityLevel:]
+ -[RPConnection _setPeerCompanionLinkFlags:]
+ -[RPConnection _setPeerDeviceCapabilityFlags:]
+ -[RPConnection _setPeerDeviceColor:]
+ -[RPConnection _setPeerHomeKitIdentifier:]
+ -[RPConnection _setPeerIDSCorrelationIdentifier:]
+ -[RPConnection _setPeerIDSDeviceIdentifier:]
+ -[RPConnection _setPeerListeningPort:]
+ -[RPConnection _setPeerMediaRemoteIdentifier:]
+ -[RPConnection _setPeerMediaRouteIdentifier:]
+ -[RPConnection _setPeerMediaSystemIdentifier:]
+ -[RPConnection _setPeerMediaSystemName:]
+ -[RPConnection _setPeerMediaSystemRole:]
+ -[RPConnection _setPeerMediaSystemState:]
+ -[RPConnection _setPeerModel:]
+ -[RPConnection _setPeerName:]
+ -[RPConnection _setPeerOperatingSystemVersion:]
+ -[RPConnection _setPeerPublicIdentifier:]
+ -[RPConnection _setPeerRole:]
+ -[RPConnection _setPeerRoomName:]
+ -[RPConnection _setPeerServiceTypes:]
+ -[RPConnection _setPeerSessionPairingIdentifier:]
+ -[RPConnection _setPeerSiriInfo:]
+ -[RPConnection _setPeerSourceVersion:]
+ -[RPConnection _setPeerStatusFlags:]
+ -[RPConnection _setPeerVerifiedIdentity:]
+ -[RPConnection _setStatusFlags:]
+ -[RPConnection _signpostBeginClientResponse:requestID:]
+ -[RPConnection _signpostBeginSendRequest:requestID:length:linkType:highPriority:]
+ -[RPConnection _signpostEndClientResponse:length:linkType:highPriority:]
+ -[RPConnection _signpostEndSendRequest:rtt:requestSize:responseSize:]
+ -[RPConnection _signpostEndSendRequestTimeout:]
+ -[RPConnection _sourceVersionString]
+ -[RPConnection _startEventMessageMetrics:length:]
+ -[RPConnection _startReceivingFrames]
+ -[RPConnection _startRequestMessageMetrics:length:]
+ -[RPConnection _startResponseMessageMetrics:]
+ -[RPConnection _statusFlagsAccessFlagsMask]
+ -[RPConnection _statusFlagsAuthenticatedMask]
+ -[RPConnection _statusFlagsMeDeviceIsMe]
+ -[RPConnection _statusFlagsString]
+ -[RPConnection _statusFlagsSyncedMask]
+ -[RPConnection _stringToOSVersion:]
+ -[RPConnection _submitEventMetrics:length:]
+ -[RPConnection _updateBonjourFlagsOnPeerDevice:]
+ -[RPConnection _updateSessionPairedIdentityWithVerifiedIdentity:model:name:]
+ -[RPConnection isGuest]
+ -[RPConnection setValue:forUndefinedKey:]
+ -[RPConnection valueForUndefinedKey:]
+ -[RPEventRegistration registrationID]
+ -[RPEventRegistration setRegistrationID:]
+ -[RPRequestRegistration registrationID]
+ -[RPRequestRegistration setRegistrationID:]
+ GCC_except_table285
+ GCC_except_table75
+ GCC_except_table77
+ GCC_except_table79
+ GCC_except_table98
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$__TtC7Rapport16RPConnectionCore
+ _OBJC_IVAR_$_RPConnection._core
+ _OBJC_IVAR_$_RPEventRegistration._registrationID
+ _OBJC_IVAR_$_RPRequestRegistration._registrationID
+ _OBJC_METACLASS_$__TtC7Rapport16RPConnectionCore
+ _OPACKDecodeNSData
+ _OPACKEncoderCreateNSData
+ _RPAuthenticationTypeToString
+ _RPPasswordTypeToString
+ __DATA__TtC7Rapport16RPConnectionCore
+ __INSTANCE_METHODS__TtC7Rapport16RPConnectionCore
+ __IVARS__TtC7Rapport16RPConnectionCore
+ __METACLASS_DATA__TtC7Rapport16RPConnectionCore
+ __OBJC_$_CLASS_METHODS_RPConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CUReadWriteRequestable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CUReadWriteRequestable
+ __OBJC_LABEL_PROTOCOL_$_CUReadWriteRequestable
+ __OBJC_PROTOCOL_$_CUReadWriteRequestable
+ __PROPERTIES__TtC7Rapport16RPConnectionCore
+ ___33-[RPConnection _createStartTimer]_block_invoke
+ ___38-[RPConnection _createBleConnectTimer]_block_invoke
+ ___39-[RPConnection _createServerStartTimer]_block_invoke
+ ___43-[RPConnection _createRetryTimerWithDelay:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0l
+ ___block_descriptor_48_e8_32s40w_e5_v8?0l
+ ___copy_helper_block_e8_32s40w
+ ___copy_helper_block_e8_32w
+ ___destroy_helper_block_e8_32s40w
+ ___destroy_helper_block_e8_32w
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0
+ _associated conformance 7Rapport25RPConnectionInternalStateOSHAASQ
+ _bzero
+ _flat unique So22CUReadWriteRequestable_p
+ _objc_copyWeak
+ _objc_initWeak
+ _objc_msgSend$__swift_objectForKeyedSubscript:
+ _objc_msgSend$__swift_setObject:forKeyedSubscript:
+ _objc_msgSend$_addInUseProcess:
+ _objc_msgSend$_addSelfIdentityInfoToMessage:flags:
+ _objc_msgSend$_addSharedHomeIdentityWithMessage:
+ _objc_msgSend$_bonjourFlagsFromLocalDeviceFlags
+ _objc_msgSend$_btPipeHighPriorityConnected
+ _objc_msgSend$_btPipeHighPriorityRequestable
+ _objc_msgSend$_btPipeSelfIdentifier
+ _objc_msgSend$_buildFrameHeaderData:length:
+ _objc_msgSend$_callAuthCompletionHandler:
+ _objc_msgSend$_callPairVerifyCompletion:
+ _objc_msgSend$_canPeerDecode128bit:major:minor:patch:
+ _objc_msgSend$_cloudDaemonIDSDeviceIDSelf
+ _objc_msgSend$_cloudDaemonOSVersionForID:
+ _objc_msgSend$_companionLinkFlagsString
+ _objc_msgSend$_companionLinkFlagsSyncedMask
+ _objc_msgSend$_completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:
+ _objc_msgSend$_completeSendMetrics:error:
+ _objc_msgSend$_controlFlagsString
+ _objc_msgSend$_controlFlagsSyncedMask
+ _objc_msgSend$_createBleConnectTimer
+ _objc_msgSend$_createOneShotTimer:handler:
+ _objc_msgSend$_createRetryTimerWithDelay:
+ _objc_msgSend$_createServerStartTimer
+ _objc_msgSend$_createStartTimer
+ _objc_msgSend$_decodeNSError:
+ _objc_msgSend$_deviceCapabilitiesFlagsSyncedMask
+ _objc_msgSend$_disableResolvedIdentityForSeconds:
+ _objc_msgSend$_encodeNSError:intoDict:
+ _objc_msgSend$_eventIDIsChatty:
+ _objc_msgSend$_forgetBleConnectTimer
+ _objc_msgSend$_forgetRetryTimer
+ _objc_msgSend$_forgetStartTimer
+ _objc_msgSend$_generatePeerIdentifierIfNeeded
+ _objc_msgSend$_gestaltDeviceClassForModel:
+ _objc_msgSend$_gestaltUserAssignedDeviceName
+ _objc_msgSend$_getCanDecode128bit
+ _objc_msgSend$_getCompanionLinkFlags
+ _objc_msgSend$_getPeerStatusFlags
+ _objc_msgSend$_getStatusFlags
+ _objc_msgSend$_hasBtPipe
+ _objc_msgSend$_hasBtPipeHighPriority
+ _objc_msgSend$_hasIdentityDaemon
+ _objc_msgSend$_homeKitIdentityIdentifierFromDaemon
+ _objc_msgSend$_identityDaemonAddSessionPairedIdentity:
+ _objc_msgSend$_identityDaemonIdentitiesOfType:error:
+ _objc_msgSend$_identityDaemonIdentityOfSelfAndReturnError:
+ _objc_msgSend$_identityDaemonResolveIdentityForSignature:data:typeFlags:error:
+ _objc_msgSend$_identityDaemonSessionPairingIdentifier
+ _objc_msgSend$_inUseProcessesToString
+ _objc_msgSend$_insertBits32:newBits:mask:
+ _objc_msgSend$_insertBits64:newBits:mask:
+ _objc_msgSend$_isLocalDeviceCommunal
+ _objc_msgSend$_linkTypeString
+ _objc_msgSend$_localDeviceInfoPassword
+ _objc_msgSend$_logRequestMetricsOnLinkType:length:rtt:
+ _objc_msgSend$_logSendMetricsForLength:
+ _objc_msgSend$_makeIdentityWithPublicKey:identifier:type:
+ _objc_msgSend$_osVersionToString:
+ _objc_msgSend$_pairingAppFlagsString:
+ _objc_msgSend$_peerDeviceInfoSetTransportFlag:
+ _objc_msgSend$_reportLargeSendContext:process:length:
+ _objc_msgSend$_requestIDIsHighVolume:messageIsChatty:
+ _objc_msgSend$_saveIdentityWithIDSDeviceID:message:
+ _objc_msgSend$_scrubPskData
+ _objc_msgSend$_sendFrameBodyImpl:body:
+ _objc_msgSend$_sendFrameObjectImpl:unencryptedObject:
+ _objc_msgSend$_sendFrameType:bodyObject:
+ _objc_msgSend$_sendFrameType:dictionaryObject:
+ _objc_msgSend$_sepPrivateKeyOfPairingIdentity:
+ _objc_msgSend$_setAppInfoPeer:
+ _objc_msgSend$_setCanDecode128bit:
+ _objc_msgSend$_setCompanionLinkFlags:
+ _objc_msgSend$_setPairingIdentity:sepPrivateKey:
+ _objc_msgSend$_setPeerAccountAltDSID:
+ _objc_msgSend$_setPeerAccountID:
+ _objc_msgSend$_setPeerActiveUserAltDSID:
+ _objc_msgSend$_setPeerActivityLevel:
+ _objc_msgSend$_setPeerCompanionLinkFlags:
+ _objc_msgSend$_setPeerDeviceCapabilityFlags:
+ _objc_msgSend$_setPeerDeviceColor:
+ _objc_msgSend$_setPeerHomeKitIdentifier:
+ _objc_msgSend$_setPeerIDSCorrelationIdentifier:
+ _objc_msgSend$_setPeerIDSDeviceIdentifier:
+ _objc_msgSend$_setPeerListeningPort:
+ _objc_msgSend$_setPeerMediaRemoteIdentifier:
+ _objc_msgSend$_setPeerMediaRouteIdentifier:
+ _objc_msgSend$_setPeerMediaSystemIdentifier:
+ _objc_msgSend$_setPeerMediaSystemName:
+ _objc_msgSend$_setPeerMediaSystemRole:
+ _objc_msgSend$_setPeerMediaSystemState:
+ _objc_msgSend$_setPeerModel:
+ _objc_msgSend$_setPeerName:
+ _objc_msgSend$_setPeerOperatingSystemVersion:
+ _objc_msgSend$_setPeerPublicIdentifier:
+ _objc_msgSend$_setPeerRole:
+ _objc_msgSend$_setPeerRoomName:
+ _objc_msgSend$_setPeerServiceTypes:
+ _objc_msgSend$_setPeerSessionPairingIdentifier:
+ _objc_msgSend$_setPeerSiriInfo:
+ _objc_msgSend$_setPeerSourceVersion:
+ _objc_msgSend$_setPeerStatusFlags:
+ _objc_msgSend$_setPeerVerifiedIdentity:
+ _objc_msgSend$_setStatusFlags:
+ _objc_msgSend$_signpostBeginClientResponse:requestID:
+ _objc_msgSend$_signpostBeginSendRequest:requestID:length:linkType:highPriority:
+ _objc_msgSend$_signpostEndClientResponse:length:linkType:highPriority:
+ _objc_msgSend$_signpostEndSendRequest:rtt:requestSize:responseSize:
+ _objc_msgSend$_signpostEndSendRequestTimeout:
+ _objc_msgSend$_sourceVersionString
+ _objc_msgSend$_startEventMessageMetrics:length:
+ _objc_msgSend$_startReceivingFrames
+ _objc_msgSend$_startRequestMessageMetrics:length:
+ _objc_msgSend$_startResponseMessageMetrics:
+ _objc_msgSend$_statusFlagsAccessFlagsMask
+ _objc_msgSend$_statusFlagsAuthenticatedMask
+ _objc_msgSend$_statusFlagsMeDeviceIsMe
+ _objc_msgSend$_statusFlagsString
+ _objc_msgSend$_statusFlagsSyncedMask
+ _objc_msgSend$_stringToOSVersion:
+ _objc_msgSend$_submitEventMetrics:length:
+ _objc_msgSend$_updateBonjourFlagsOnPeerDevice:
+ _objc_msgSend$_updateIdentity:withSEPPrivateKey:
+ _objc_msgSend$_updateIdentity:withSecretKey:
+ _objc_msgSend$_updateSessionPairedIdentityWithVerifiedIdentity:model:name:
+ _objc_msgSend$abortRequestsWithError:
+ _objc_msgSend$abortSendEntry:withError:
+ _objc_msgSend$activateCalled
+ _objc_msgSend$activatedTicks
+ _objc_msgSend$appID
+ _objc_msgSend$appInfoSelf
+ _objc_msgSend$bleClientUseCase
+ _objc_msgSend$bleConnection
+ _objc_msgSend$bleConnectionPSM
+ _objc_msgSend$blePeerIdentifier
+ _objc_msgSend$bonjourPeerDevice
+ _objc_msgSend$btPipe
+ _objc_msgSend$buildSystemInfo
+ _objc_msgSend$clientConnectCompleted:
+ _objc_msgSend$clientConnectStart
+ _objc_msgSend$clientConnectStartBLE
+ _objc_msgSend$clientConnectStartBTPipe
+ _objc_msgSend$clientConnectStartTCP
+ _objc_msgSend$clientError:
+ _objc_msgSend$clientMode
+ _objc_msgSend$clientNetworkError:label:
+ _objc_msgSend$clientPairSetupCompleted:
+ _objc_msgSend$clientPairSetupStart
+ _objc_msgSend$clientPairSetupWithData:
+ _objc_msgSend$clientPairVerifyCompleted:
+ _objc_msgSend$clientPairVerifyStart
+ _objc_msgSend$clientPairVerifyWithData:
+ _objc_msgSend$clientPreAuthResponseWithData:
+ _objc_msgSend$clientPreAuthStart
+ _objc_msgSend$clientRetryFired
+ _objc_msgSend$clientRetryStart
+ _objc_msgSend$clientRun
+ _objc_msgSend$clientStartSession
+ _objc_msgSend$clientStarted
+ _objc_msgSend$configureForSessionPairing:
+ _objc_msgSend$configurePairingHandler
+ _objc_msgSend$destinationString
+ _objc_msgSend$doubleValue
+ _objc_msgSend$flowControlWriteChangedHandler
+ _objc_msgSend$forcedPeerIdentity
+ _objc_msgSend$forcedSelfIdentity
+ _objc_msgSend$hidePasswordHandler
+ _objc_msgSend$highPriorityStream
+ _objc_msgSend$homeKitIdentityIdentifier
+ _objc_msgSend$homeKitIdentitySignature
+ _objc_msgSend$homeKitUserIdentifierHandler
+ _objc_msgSend$identifierOverride
+ _objc_msgSend$identityKeyData
+ _objc_msgSend$identitySignature
+ _objc_msgSend$identityVerified
+ _objc_msgSend$initWithBool:
+ _objc_msgSend$initWithDouble:
+ _objc_msgSend$initWithInt:
+ _objc_msgSend$initWithInteger:
+ _objc_msgSend$initWithUnsignedInt:
+ _objc_msgSend$initWithUnsignedInteger:
+ _objc_msgSend$initWithUnsignedLongLong:
+ _objc_msgSend$initiator
+ _objc_msgSend$internalState
+ _objc_msgSend$invalidateCalled
+ _objc_msgSend$invalidateDone
+ _objc_msgSend$keepAliveSeconds
+ _objc_msgSend$localDeviceInfo
+ _objc_msgSend$mainStream
+ _objc_msgSend$pairSetupACL
+ _objc_msgSend$pairSetupFlags
+ _objc_msgSend$pairSetupInvalidate
+ _objc_msgSend$pairSetupSession
+ _objc_msgSend$pairVerifyAuthType
+ _objc_msgSend$pairVerifyCompleted
+ _objc_msgSend$pairVerifyCompletion
+ _objc_msgSend$pairVerifyFailed
+ _objc_msgSend$pairVerifyFlags
+ _objc_msgSend$pairVerifyInvalidate
+ _objc_msgSend$pairVerifySession
+ _objc_msgSend$pairVerifySign:flags:error:
+ _objc_msgSend$pairVerifyUsedIdentity
+ _objc_msgSend$pairVerifyVerifySignature:data:flags:error:
+ _objc_msgSend$passwordType
+ _objc_msgSend$peerAddrStr
+ _objc_msgSend$peerDeviceInfo
+ _objc_msgSend$peerHKUserID
+ _objc_msgSend$peerIdentifier
+ _objc_msgSend$peerUpdatedHandler
+ _objc_msgSend$preAuthEnabled
+ _objc_msgSend$preferredIdentityType
+ _objc_msgSend$present
+ _objc_msgSend$processSendsUsingConnection:
+ _objc_msgSend$promptForPasswordHandler
+ _objc_msgSend$pskData
+ _objc_msgSend$pskPrepareWithIsClient:
+ _objc_msgSend$receivedEvent:length:moreComing:
+ _objc_msgSend$receivedEventHandler
+ _objc_msgSend$receivedFrameCountCurrent
+ _objc_msgSend$receivedFrameCountLast
+ _objc_msgSend$receivedObject:length:moreComing:
+ _objc_msgSend$receivedRequest:length:moreComing:
+ _objc_msgSend$receivedRequestHandler
+ _objc_msgSend$receivedResponse:length:moreComing:
+ _objc_msgSend$receivedSystemInfo:xid:
+ _objc_msgSend$requestable
+ _objc_msgSend$requests
+ _objc_msgSend$retryCount
+ _objc_msgSend$sendArray
+ _objc_msgSend$serverAccept
+ _objc_msgSend$serverAcceptBLE
+ _objc_msgSend$serverAcceptBTPipe
+ _objc_msgSend$serverAcceptTCP
+ _objc_msgSend$serverError:
+ _objc_msgSend$serverNetworkError:label:
+ _objc_msgSend$serverPairSetupCompleted:
+ _objc_msgSend$serverPairSetupWithData:start:
+ _objc_msgSend$serverPairVerifyCompleted:
+ _objc_msgSend$serverPairVerifyWithData:start:
+ _objc_msgSend$serverPreAuthRequestWithData:
+ _objc_msgSend$serverRun
+ _objc_msgSend$serverStarted
+ _objc_msgSend$serviceType
+ _objc_msgSend$sessionStartHandler
+ _objc_msgSend$setActivateCalled:
+ _objc_msgSend$setActivatedTicks:
+ _objc_msgSend$setAppID:
+ _objc_msgSend$setBleConnection:
+ _objc_msgSend$setHighPriorityStream:
+ _objc_msgSend$setHomeKitIdentityIdentifier:
+ _objc_msgSend$setHomeKitIdentitySignature:
+ _objc_msgSend$setIdentityKeyData:
+ _objc_msgSend$setIdentitySignature:
+ _objc_msgSend$setInitiator:
+ _objc_msgSend$setInternalState:
+ _objc_msgSend$setInvalidateCalled:
+ _objc_msgSend$setInvalidateDone:
+ _objc_msgSend$setMainStream:
+ _objc_msgSend$setPairSetupSession:
+ _objc_msgSend$setPairVerifyAuthType:
+ _objc_msgSend$setPairVerifyCompleted:
+ _objc_msgSend$setPairVerifyFailed:
+ _objc_msgSend$setPairVerifySession:
+ _objc_msgSend$setPeerAddrStr:
+ _objc_msgSend$setPeerHKUserID:
+ _objc_msgSend$setReceivedFrameCountCurrent:
+ _objc_msgSend$setReceivedFrameCountLast:
+ _objc_msgSend$setRequestable:
+ _objc_msgSend$setRequests:
+ _objc_msgSend$setRetryCount:
+ _objc_msgSend$setRetryTicks:
+ _objc_msgSend$setSelfAddrString:
+ _objc_msgSend$setSendArray:
+ _objc_msgSend$setSessionStartHandler:
+ _objc_msgSend$setShowPasswordCalled:
+ _objc_msgSend$setStartTimeoutSeconds:
+ _objc_msgSend$setStepDone:
+ _objc_msgSend$setStepError:
+ _objc_msgSend$setXidLast:
+ _objc_msgSend$showPasswordCalled
+ _objc_msgSend$showPasswordHandler
+ _objc_msgSend$startTimeoutSeconds
+ _objc_msgSend$stateChangedHandler
+ _objc_msgSend$stepDone
+ _objc_msgSend$stepError
+ _objc_msgSend$updateExternalState
+ _objc_msgSend$xidLast
+ _objectdestroy.114Tm
+ _objectdestroy.146Tm
+ _objectdestroy.212Tm
+ _objectdestroy.220Tm
+ _objectdestroy.24Tm
+ _objectdestroy.84Tm
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastClass
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_n
+ _swift_retain_n
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain_n
+ _swift_unknownObjectUnownedDestroy
+ _swift_unknownObjectUnownedInit
+ _swift_unknownObjectUnownedLoadStrong
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $sSY
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic SDy_____ypGSg s11AnyHashableV
+ _symbolic Say_____G 10Foundation4UUIDV
+ _symbolic Sd
+ _symbolic Si
+ _symbolic So10RPIdentityCSg
+ _symbolic So11RPSendEntryC
+ _symbolic So12NSDictionaryCSgACSo7NSErrorCSgIeyByyy_
+ _symbolic So12RPConnectionC
+ _symbolic So12RPConnectionCSgXw
+ _symbolic So12RPConnectionCSgXwz_Xx
+ _symbolic So12RPConnectionCXo
+ _symbolic So14CUWriteRequestCIegg_
+ _symbolic So14CUWriteRequestCSgXw
+ _symbolic So14CUWriteRequestCSgXwz_Xx
+ _symbolic So14NSMutableArrayC
+ _symbolic So14RPRequestEntryC
+ _symbolic So15CUBLEConnectionC
+ _symbolic So15CUPairingStreamCSg
+ _symbolic So15CUTCPConnectionC
+ _symbolic So16CUPairingSessionCSg
+ _symbolic So19NSMutableDictionaryCSg
+ _symbolic So7NSErrorC
+ _symbolic So7NSErrorCSg
+ _symbolic So7NSErrorCSgIegg_
+ _symbolic So7NSErrorCSgIeyBy_
+ _symbolic So8NSNumberC
+ _symbolic _____ 7Rapport16RPConnectionCoreC
+ _symbolic _____ 7Rapport21RPConnectionConstantsO
+ _symbolic _____ 7Rapport25RPConnectionInternalStateO
+ _symbolic _____ So14RPIdentityTypeV
+ _symbolic _____ So20RPAuthenticationTypeV
+ _symbolic _____ s5Int32V
+ _symbolic _____ s6UInt32V
+ _symbolic _____ s6UInt64V
+ _symbolic _____Iegy_Sg s6UInt32V
+ _symbolic _____IeyBy_ s6UInt32V
+ _symbolic _____SSIegyg_Sg s6UInt32V
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____SgXw 7Rapport16RPConnectionCoreC
+ _symbolic _____SgXwz_Xx 7Rapport16RPConnectionCoreC
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
+ _symbolic _____So8NSStringCIeyByy_ s6UInt32V
+ _symbolic _____XDXMT 7Rapport16RPConnectionCoreC
+ _symbolic __________Iegyy_ s6UInt32V s5Int32V
+ _symbolic __________IeyByy_ s6UInt32V s5Int32V
+ _symbolic ______pSg So22CUReadWriteRequestableP
+ _symbolic ______pSg s5ErrorP
+ _symbolic ______pSgIegg_Sg s5ErrorP
+ _symbolic ______ypt s11AnyHashableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _symbolic _____yyp_yptG s23_ContiguousArrayStorageC
+ _symbolic yXlSg
+ _symbolic yXlSgz_Xx
+ _symbolic ypSg
+ _symbolic ypypSpy_____GIgnny_ 10ObjectiveC8ObjCBoolV
- -[RPConnection _isEligibleToSendWithOptions:]
- -[RPConnection logConnectionInformation:options:]
- GCC_except_table140
- GCC_except_table151
- GCC_except_table156
- _OBJC_IVAR_$_RPConnection._activateCalled
- _OBJC_IVAR_$_RPConnection._activatedTicks
- _OBJC_IVAR_$_RPConnection._highPriorityAuthTagLength
- _OBJC_IVAR_$_RPConnection._highPriorityStream
- _OBJC_IVAR_$_RPConnection._homeKitIdentityIdentifier
- _OBJC_IVAR_$_RPConnection._homeKitIdentitySignature
- _OBJC_IVAR_$_RPConnection._identityKeyData
- _OBJC_IVAR_$_RPConnection._identitySignature
- _OBJC_IVAR_$_RPConnection._identityVerified
- _OBJC_IVAR_$_RPConnection._initiator
- _OBJC_IVAR_$_RPConnection._internalState
- _OBJC_IVAR_$_RPConnection._invalidateCalled
- _OBJC_IVAR_$_RPConnection._invalidateDone
- _OBJC_IVAR_$_RPConnection._mainAuthTagLength
- _OBJC_IVAR_$_RPConnection._mainStream
- _OBJC_IVAR_$_RPConnection._pairSetupAuthType
- _OBJC_IVAR_$_RPConnection._pairSetupSession
- _OBJC_IVAR_$_RPConnection._pairVerifyAuthType
- _OBJC_IVAR_$_RPConnection._pairVerifyCompleted
- _OBJC_IVAR_$_RPConnection._pairVerifyFailed
- _OBJC_IVAR_$_RPConnection._pairVerifyIdentityType
- _OBJC_IVAR_$_RPConnection._pairVerifySession
- _OBJC_IVAR_$_RPConnection._pairVerifyUsedIdentity
- _OBJC_IVAR_$_RPConnection._peerAddrString
- _OBJC_IVAR_$_RPConnection._peerHomeKitUserIdentifier
- _OBJC_IVAR_$_RPConnection._receivedFrameCountCurrent
- _OBJC_IVAR_$_RPConnection._receivedFrameCountLast
- _OBJC_IVAR_$_RPConnection._requestable
- _OBJC_IVAR_$_RPConnection._requests
- _OBJC_IVAR_$_RPConnection._retryCount
- _OBJC_IVAR_$_RPConnection._retryFired
- _OBJC_IVAR_$_RPConnection._retryTicks
- _OBJC_IVAR_$_RPConnection._selfAddrString
- _OBJC_IVAR_$_RPConnection._sendArray
- _OBJC_IVAR_$_RPConnection._showPasswordCalled
- _OBJC_IVAR_$_RPConnection._startTimeoutSeconds
- _OBJC_IVAR_$_RPConnection._stepDone
- _OBJC_IVAR_$_RPConnection._stepError
- _OBJC_IVAR_$_RPConnection._xidLast
- _RPFrameTypeToString
- __StateToString
- ___104-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]_block_invoke
- ___29-[RPConnection _serverAccept]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_3
- ___33-[RPConnection _clientRetryStart]_block_invoke
- ___35-[RPConnection _clientStartSession]_block_invoke
- ___37-[RPConnection _clientPairSetupStart]_block_invoke
- ___37-[RPConnection _receivedRequest:ctx:]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_2
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_3
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_2
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_3
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_4
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke
- ___40-[RPConnection _abortRequestsWithError:]_block_invoke
- ___40-[RPConnection _clientConnectCompleted:]_block_invoke
- ___40-[RPConnection _receivedSystemInfo:xid:]_block_invoke
- ___41-[RPConnection _clientConnectStartBTPipe]_block_invoke
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_2
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_3
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_2
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_3
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_4
- ___66-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]_block_invoke
- ___77-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]_block_invoke
- ___88-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]_block_invoke
- ___block_descriptor_40_e8_32s_e19_v20?0I8"NSData"12l
- ___block_descriptor_40_e8_32s_e21_v20?0I8"NSString"12l
- ___block_descriptor_40_e8_32s_e31_"NSData"28?0I8"NSData"12^20l
- ___block_descriptor_40_e8_32s_e34_B36?0I8"NSData"12"NSData"20^28l
- ___block_descriptor_44_e8_32s_e19_v20?0I8"NSData"12l
- ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8l
- ___block_descriptor_48_e8_32s40bs_e11_v16?0I8i12l
- ___block_descriptor_48_e8_32s40s_e29_B32?0"CUPairedPeer"8Q16^24l
- ___block_descriptor_48_e8_32s40s_e31_"CUPairingIdentity"24?0Q8^16l
- ___block_descriptor_48_e8_32s40s_e41_v32?0"NSNumber"8"RPRequestEntry"16^B24l
- ___block_descriptor_48_e8_32s40s_e43_"CUPairedPeer"32?0"CUPairedPeer"8Q16^24l
- ___block_descriptor_60_e8_32s40s48s_e5_v8?0l
- ___block_descriptor_66_e8_32s40s48s56s_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24l
- _objc_msgSend$_clientConnectStart
- _objc_msgSend$_clientConnectStartBLE
- _objc_msgSend$_clientConnectStartBTPipe
- _objc_msgSend$_clientConnectStartTCP
- _objc_msgSend$_clientNetworkError:label:
- _objc_msgSend$_clientPairSetupCompleted:
- _objc_msgSend$_clientPairSetupStart
- _objc_msgSend$_clientPairVerifyCompleted:
- _objc_msgSend$_clientPairVerifyStart
- _objc_msgSend$_clientPreAuthStart
- _objc_msgSend$_clientRetryStart
- _objc_msgSend$_clientRun
- _objc_msgSend$_clientStartSession
- _objc_msgSend$_clientStarted
- _objc_msgSend$_isEligibleToSendWithOptions:
- _objc_msgSend$_pairVerifySignData:flags:error:
- _objc_msgSend$_pairVerifyVerifySignature:data:flags:error:
- _objc_msgSend$_pskPrepare:
- _objc_msgSend$_receivedEvent:ctx:
- _objc_msgSend$_receivedRequest:ctx:
- _objc_msgSend$_receivedResponse:ctx:
- _objc_msgSend$_receivedSystemInfo:xid:
- _objc_msgSend$_serverAccept
- _objc_msgSend$_serverAcceptBLE
- _objc_msgSend$_serverAcceptBTPipe
- _objc_msgSend$_serverAcceptTCP
- _objc_msgSend$_serverNetworkError:label:
- _objc_msgSend$_serverPairSetupCompleted:
- _objc_msgSend$_serverPairVerifyCompleted:
- _objc_msgSend$_serverRun
- _objc_msgSend$_serverStarted
- _objc_msgSend$_systeminfo
- _objc_msgSend$_updateExternalState
- _objc_msgSend$dictionaryWithObjectsAndKeys:
- _objc_msgSend$fixedPIN
- _objc_msgSend$logConnectionInformation:options:
CStrings:
+ "### Abort queued ID '%{public}s': %{public}@"
+ "### Abort request XID 0x%{public}s: %{public}@"
+ "### Client error: %{public}@"
+ "### Connect failed: %{public}@"
+ "### Failed to get self identity: %{public}@"
+ "### Ignoring call to send event ID '%{public}s' when invalidating"
+ "### Ignoring received PreAuthResponse when not expected: %@"
+ "### Ignoring response to requestID '%{public}s' after invalidation"
+ "### Ignoring send request ID '%{public}s' when invalidating"
+ "### PSK prepare failed: %{public}@"
+ "### PairSetup client completion failed: %{public}@"
+ "### PairSetup server completion failed: %{public}@"
+ "### PairSetup server receive failed: %{public}@"
+ "### PairVerify client completion failed: %{public}@"
+ "### PairVerify client failed: %{public}@"
+ "### PairVerify server completion failed: %{public}s, %{public}@"
+ "### PairVerify server receive failed: %{public}@"
+ "### PairVerifyVerify failed: %{public}@"
+ "### PreAuthRequest decode failed"
+ "### PreAuthRequest failed, unexpected state"
+ "### PreAuthResponse decode failed: %{public}d"
+ "### Process unsupported request"
+ "### Received event with no ID from %s"
+ "### Received event with no content from %s"
+ "### Received request XID 0x%{public}s with no ID from %s"
+ "### Received request with no XID from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s with no content from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s, from %s with no handler"
+ "### Received response XID 0x%{public}s with no content from %s"
+ "### Received response XID 0x%{public}s with no request from %s"
+ "### Received response XID 0x%{public}s, error %{public}@, from %s, %{public}llu ms"
+ "### Received response with no XID from %s"
+ "### Request timeout '%{public}s' not found, %{public}f seconds"
+ "### Request timeout '%{public}s', %{public}f seconds"
+ "### Request timeout XID 0x%{public}s, %{public}f seconds"
+ "### Send encrypted data (%{public}ld bytes) failed: '%{public}s', %{public}@"
+ "### Send encrypted requestID '%{public}s' failed: %{public}@"
+ "### Send encrypted response XID 0x%{public}s failed: %{public}@"
+ "### Send frame 0x%{public}s encode failed: %{public}d"
+ "### Send frame type 0x%{public}s failed: %{public}@"
+ "### Sending response XID 0x%{public}s, error: %{public}@"
+ "### Server error: %{public}@"
+ "### Timeout for XID 0x%{public}s with no request"
+ "### Unknown message type: %{public}d"
+ "### Unsupported send attempt"
+ "%#ll{flags}"
+ "%#{flags}"
+ "-[RPConnection _startReceivingFrames]"
+ "@\"_TtC7Rapport16RPConnectionCore\""
+ "@24@0:8Q16"
+ "@28@0:8C16Q20"
+ "@28@0:8i16^@20"
+ "@32@0:8d16@?24"
+ "@36@0:8@16@24i32"
+ "@40@0:8{?=qqq}16"
+ "@44@0:8@16@24I32^@36"
+ "AirPlay restrictions ignored"
+ "B28@0:8@16B24"
+ "B44@0:8i16q20q28q36"
+ "BLE client connection invalidated"
+ "BLE client connection with bundleID: %s and clientUseCase: %{public}ld"
+ "BLE server connection invalidated"
+ "Backwards compatibility authType -> sessionPaired"
+ "Backwards compatibility change authType sessionPaired -> rpIdentity"
+ "CUReadWriteRequestable"
+ "Client PairSetup retry"
+ "Client connect start: %@"
+ "Client immediate non-RPIdentity retry"
+ "Client state: %{public}s -> %{public}s"
+ "Configuring for session pairing"
+ "Enabling FitnessPairing"
+ "External state changed: %{public}s -> %{public}s"
+ "Failed to open main stream"
+ "Find paired peer handler for peer %@ options %llu"
+ "I28@0:8I16I20I24"
+ "In use processes updated to: %{public}s"
+ "Large Frame: Send frame 0x%{public}s, (%{public}ld bytes)"
+ "Large Frame: Send request ID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "Large Frame: Send response XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "Large Frame: SendEventID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "OnDemand connection failed, invalidating"
+ "PairSetup completed client."
+ "PairSetup next (%ld bytes)"
+ "PairSetup response error: '"
+ "PairSetup server rejecting when not allowed"
+ "PairSetup server rejecting when not allowing non-Home devices"
+ "PairVerify completed client %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify completed server: %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify next (%ld bytes)"
+ "PairVerify start client: AT %{public}s, CF %{public}s, FL %{public}s, PWT %{public}s"
+ "PairVerifySign success: CF %{public}s, AF %{public}s"
+ "PairVerifySign: Not using RPI"
+ "PairVerifySign: Not using RPI: CF %{public}s, AF %{public}s"
+ "PairVerifyVerify resolve identity failed"
+ "PairVerifyVerify success: %{public}d, CF %{public}s, AF %{public}s"
+ "PairVerifyVerify: Not using RPI"
+ "PairVerifyVerify: Not using RPI: CF %{public}s, AF %{public}s"
+ "Peer appears missing, invalidating"
+ "Peer appears present, retrying"
+ "Peer is blocking access, invalidating"
+ "Peer may be unreachable, sending reachability probe (%{public}s)"
+ "Peer missing after retry timer, invalidating"
+ "Q40@0:8Q16Q24Q32"
+ "Queuing send event ID '%{public}s', XID 0x%{public}s (%{public}ld send(s) pending)"
+ "Queuing send request ID '%{public}s' (%{public}ld send(s) pending)"
+ "Rapport.RPConnectionCore"
+ "Received PreAuthRequest"
+ "Received PreAuthResponse: %@"
+ "Received SharedHome identity: ID '%s'"
+ "Received client service type %{public}s"
+ "Received event ID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received identity from IDS '%s'"
+ "Received requestID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received response XID 0x%{public}s, %{public}ld keys, from %s, %{public}llu ms request size %{public}ld response size %{public}llu"
+ "Rejected in unexpected state"
+ "Retrying delayed: %.*f seconds"
+ "Retrying immediately: %lds since last retry"
+ "Retrying immediately: first retry"
+ "Save paired peer handler for peer %@ options %llu"
+ "Send PreAuthRequest: %@"
+ "Send PreAuthResponse"
+ "Send SharedHome identity"
+ "Send encrypted event failed: '%{public}s', %{public}@"
+ "Send encrypted requestID '%{public}s' failed: %{public}@"
+ "Send frame 0x%{public}s, (%{public}ld bytes)"
+ "Send identity"
+ "Send request ID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Send response XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s%{public}s"
+ "SendEventID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Sending client service type %{public}s"
+ "Server state: %{public}s -> %{public}s"
+ "T@\"<CUReadWriteRequestable>\",N,&,Vrequestable"
+ "T@\"CUPairingSession\",N,&,VpairSetupSession"
+ "T@\"CUPairingSession\",N,&,VpairVerifySession"
+ "T@\"CUPairingStream\",N,&,VhighPriorityStream"
+ "T@\"CUPairingStream\",N,&,VmainStream"
+ "T@\"NSData\",N,C"
+ "T@\"NSError\",N,&,VstepError"
+ "T@\"NSMutableArray\",N,&,VsendArray"
+ "T@\"NSMutableDictionary\",N,&,Vrequests"
+ "T@\"NSString\",N,C"
+ "T@\"NSString\",R,D,N"
+ "T@\"NSUUID\",&,N,V_registrationID"
+ "T@\"RPIdentity\",N,&,VidentityVerified"
+ "T@\"RPIdentity\",R,D,N"
+ "TB,N,VactivateCalled"
+ "TB,N,VinvalidateCalled"
+ "TB,N,VinvalidateDone"
+ "TB,N,VpairVerifyCompleted"
+ "TB,N,VpairVerifyFailed"
+ "TB,N,VpairVerifyUsedIdentity"
+ "TB,N,VretryFired"
+ "TB,N,VshowPasswordCalled"
+ "TB,N,VstepDone"
+ "TB,R,N,GisGuest"
+ "TCP client connection invalidated"
+ "TCP server connection invalidated"
+ "TI,N,VxidLast"
+ "TQ,N,VactivatedTicks"
+ "TQ,N,VreceivedFrameCountCurrent"
+ "TQ,N,VreceivedFrameCountLast"
+ "TQ,N,VretryTicks"
+ "Td,N,VstartTimeoutSeconds"
+ "Ti,N,VinternalState"
+ "Ti,N,VpairSetupAuthType"
+ "Ti,N,VpairVerifyAuthType"
+ "Ti,N,VpairVerifyIdentityType"
+ "Ti,N,VretryCount"
+ "Ti,R,D,N"
+ "Too many retries, invalidating: retries %d, %@"
+ "Tq,N,VhighPriorityAuthTagLength"
+ "Tq,N,VmainAuthTagLength"
+ "Transferring event ID %{public}s to connection %{public}s"
+ "Transferring request ID %{public}s to connection %{public}s with timeout %{public}f"
+ "Unsupported password type or auth type"
+ "Using AdHocPaired identifier for connection: %s"
+ "^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}24@0:8@16"
+ "_TtC7Rapport16RPConnectionCore"
+ "__swift_objectForKeyedSubscript:"
+ "__swift_setObject:forKeyedSubscript:"
+ "_addInUseProcess:"
+ "_addSelfIdentityInfoToMessage:flags:"
+ "_addSharedHomeIdentityWithMessage:"
+ "_bonjourFlagsFromLocalDeviceFlags"
+ "_btPipeHighPriorityConnected"
+ "_btPipeHighPriorityRequestable"
+ "_btPipeSelfIdentifier"
+ "_buildFrameHeaderData:length:"
+ "_callAuthCompletionHandler:"
+ "_callPairVerifyCompletion:"
+ "_canPeerDecode128bit:major:minor:patch:"
+ "_cloudDaemonIDSDeviceIDSelf"
+ "_cloudDaemonOSVersionForID:"
+ "_companionLinkFlagsString"
+ "_companionLinkFlagsSyncedMask"
+ "_completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:"
+ "_completeSendMetrics:error:"
+ "_controlFlagsString"
+ "_controlFlagsSyncedMask"
+ "_core"
+ "_createBleConnectTimer"
+ "_createOneShotTimer:handler:"
+ "_createRetryTimerWithDelay:"
+ "_createServerStartTimer"
+ "_createStartTimer"
+ "_decodeNSError:"
+ "_deviceCapabilitiesFlagsSyncedMask"
+ "_disableResolvedIdentityForSeconds:"
+ "_encodeNSError:intoDict:"
+ "_eventIDIsChatty:"
+ "_forgetBleConnectTimer"
+ "_forgetRetryTimer"
+ "_forgetStartTimer"
+ "_generatePeerIdentifierIfNeeded"
+ "_gestaltDeviceClassForModel:"
+ "_gestaltUserAssignedDeviceName"
+ "_getCanDecode128bit"
+ "_getCompanionLinkFlags"
+ "_getPeerStatusFlags"
+ "_getStatusFlags"
+ "_hasBtPipe"
+ "_hasBtPipeHighPriority"
+ "_hasIdentityDaemon"
+ "_homeKitIdentityIdentifierFromDaemon"
+ "_identityDaemonAddSessionPairedIdentity:"
+ "_identityDaemonIdentitiesOfType:error:"
+ "_identityDaemonIdentityOfSelfAndReturnError:"
+ "_identityDaemonResolveIdentityForSignature:data:typeFlags:error:"
+ "_identityDaemonSessionPairingIdentifier"
+ "_inUseProcessesToString"
+ "_insertBits32:newBits:mask:"
+ "_insertBits64:newBits:mask:"
+ "_isLocalDeviceCommunal"
+ "_linkTypeString"
+ "_localDeviceInfoPassword"
+ "_logRequestMetricsOnLinkType:length:rtt:"
+ "_logSendMetricsForLength:"
+ "_makeIdentityWithPublicKey:identifier:type:"
+ "_osVersionToString:"
+ "_pairingAppFlagsString:"
+ "_peerDeviceInfoSetTransportFlag:"
+ "_registrationID"
+ "_reportLargeSendContext:process:length:"
+ "_requestIDIsHighVolume:messageIsChatty:"
+ "_saveIdentityWithIDSDeviceID:message:"
+ "_scrubPskData"
+ "_sendFrameBodyImpl:body:"
+ "_sendFrameObjectImpl:unencryptedObject:"
+ "_sendFrameType:bodyObject:"
+ "_sendFrameType:dictionaryObject:"
+ "_sepPrivateKeyOfPairingIdentity:"
+ "_setAppInfoPeer:"
+ "_setCanDecode128bit:"
+ "_setCompanionLinkFlags:"
+ "_setPairingIdentity:sepPrivateKey:"
+ "_setPeerAccountAltDSID:"
+ "_setPeerAccountID:"
+ "_setPeerActiveUserAltDSID:"
+ "_setPeerActivityLevel:"
+ "_setPeerCompanionLinkFlags:"
+ "_setPeerDeviceCapabilityFlags:"
+ "_setPeerDeviceColor:"
+ "_setPeerHomeKitIdentifier:"
+ "_setPeerIDSCorrelationIdentifier:"
+ "_setPeerIDSDeviceIdentifier:"
+ "_setPeerListeningPort:"
+ "_setPeerMediaRemoteIdentifier:"
+ "_setPeerMediaRouteIdentifier:"
+ "_setPeerMediaSystemIdentifier:"
+ "_setPeerMediaSystemName:"
+ "_setPeerMediaSystemRole:"
+ "_setPeerMediaSystemState:"
+ "_setPeerModel:"
+ "_setPeerName:"
+ "_setPeerOperatingSystemVersion:"
+ "_setPeerPublicIdentifier:"
+ "_setPeerRole:"
+ "_setPeerRoomName:"
+ "_setPeerServiceTypes:"
+ "_setPeerSessionPairingIdentifier:"
+ "_setPeerSiriInfo:"
+ "_setPeerSourceVersion:"
+ "_setPeerStatusFlags:"
+ "_setPeerVerifiedIdentity:"
+ "_setStatusFlags:"
+ "_signpostBeginClientResponse:requestID:"
+ "_signpostBeginSendRequest:requestID:length:linkType:highPriority:"
+ "_signpostEndClientResponse:length:linkType:highPriority:"
+ "_signpostEndSendRequest:rtt:requestSize:responseSize:"
+ "_signpostEndSendRequestTimeout:"
+ "_sourceVersionString"
+ "_startEventMessageMetrics:length:"
+ "_startReceivingFrames"
+ "_startRequestMessageMetrics:length:"
+ "_startResponseMessageMetrics:"
+ "_statusFlagsAccessFlagsMask"
+ "_statusFlagsAuthenticatedMask"
+ "_statusFlagsMeDeviceIsMe"
+ "_statusFlagsString"
+ "_statusFlagsSyncedMask"
+ "_stringToOSVersion:"
+ "_submitEventMetrics:length:"
+ "_updateBonjourFlagsOnPeerDevice:"
+ "_updateIdentity:withSEPPrivateKey:"
+ "_updateIdentity:withSecretKey:"
+ "_updateSessionPairedIdentityWithVerifiedIdentity:model:name:"
+ "abortRequestsWithError:"
+ "abortSendEntry:withError:"
+ "activateCalled"
+ "activatedTicks"
+ "buildSystemInfo"
+ "clientConnectCompleted:"
+ "clientConnectStart"
+ "clientConnectStartBLE"
+ "clientConnectStartBTPipe"
+ "clientConnectStartTCP"
+ "clientError:"
+ "clientNetworkError:label:"
+ "clientPairSetupCompleted:"
+ "clientPairSetupStart"
+ "clientPairSetupWithData:"
+ "clientPairVerifyCompleted:"
+ "clientPairVerifyStart"
+ "clientPairVerifyWithData:"
+ "clientPreAuthResponseWithData:"
+ "clientPreAuthStart"
+ "clientRetryFired"
+ "clientRetryStart"
+ "clientRun"
+ "clientStartSession"
+ "clientStarted"
+ "configureForSessionPairing:"
+ "connection"
+ "doubleValue"
+ "highPriorityAuthTagLength"
+ "highPriorityStream"
+ "homeKitIdentityIdentifier"
+ "homeKitIdentitySignature"
+ "i24@0:8@16"
+ "identityKeyData"
+ "identitySignature"
+ "initWithBool:"
+ "initWithDouble:"
+ "initWithInt:"
+ "initWithInteger:"
+ "initWithUnsignedInt:"
+ "initWithUnsignedInteger:"
+ "initWithUnsignedLongLong:"
+ "internalState"
+ "invalidateCalled"
+ "invalidateDone"
+ "isGuest"
+ "mainAuthTagLength"
+ "mainStream"
+ "pairSetupAuthType"
+ "pairSetupInvalidate"
+ "pairSetupSession"
+ "pairVerifyCompleted"
+ "pairVerifyFailed"
+ "pairVerifyIdentityType"
+ "pairVerifyInvalidate"
+ "pairVerifySession"
+ "pairVerifySign:flags:error:"
+ "pairVerifyUsedIdentity"
+ "pairVerifyVerifySignature:data:flags:error:"
+ "peerAddrStr"
+ "peerHKUserID"
+ "pskPrepareWithIsClient:"
+ "receivedEvent:length:moreComing:"
+ "receivedFrameCountCurrent"
+ "receivedFrameCountLast"
+ "receivedObject:length:moreComing:"
+ "receivedRequest:length:moreComing:"
+ "receivedResponse:length:moreComing:"
+ "receivedSystemInfo:xid:"
+ "registrationID"
+ "requestable"
+ "requests"
+ "retryCount"
+ "retryFired"
+ "retryTicks"
+ "selfAddrString"
+ "sendArray"
+ "serverAccept"
+ "serverAcceptBLE"
+ "serverAcceptBTPipe"
+ "serverAcceptTCP"
+ "serverError:"
+ "serverNetworkError:label:"
+ "serverPairSetupCompleted:"
+ "serverPairSetupWithData:start:"
+ "serverPairVerifyCompleted:"
+ "serverPairVerifyWithData:start:"
+ "serverPreAuthRequestWithData:"
+ "serverRun"
+ "serverStarted"
+ "setActivateCalled:"
+ "setActivatedTicks:"
+ "setHighPriorityAuthTagLength:"
+ "setHighPriorityStream:"
+ "setHomeKitIdentityIdentifier:"
+ "setHomeKitIdentitySignature:"
+ "setIdentityKeyData:"
+ "setIdentitySignature:"
+ "setIdentityVerified:"
+ "setInitiator:"
+ "setInternalState:"
+ "setInvalidateCalled:"
+ "setInvalidateDone:"
+ "setMainAuthTagLength:"
+ "setMainStream:"
+ "setPairSetupAuthType:"
+ "setPairSetupSession:"
+ "setPairVerifyAuthType:"
+ "setPairVerifyCompleted:"
+ "setPairVerifyFailed:"
+ "setPairVerifyIdentityType:"
+ "setPairVerifySession:"
+ "setPairVerifyUsedIdentity:"
+ "setPeerAddrStr:"
+ "setPeerHKUserID:"
+ "setReceivedFrameCountCurrent:"
+ "setReceivedFrameCountLast:"
+ "setRegistrationID:"
+ "setRequestable:"
+ "setRequests:"
+ "setRetryCount:"
+ "setRetryFired:"
+ "setRetryTicks:"
+ "setSelfAddrString:"
+ "setSendArray:"
+ "setShowPasswordCalled:"
+ "setStartTimeoutSeconds:"
+ "setStepDone:"
+ "setStepError:"
+ "setValue:forUndefinedKey:"
+ "setXidLast:"
+ "showPasswordCalled"
+ "startTimeoutSeconds"
+ "stepDone"
+ "stepError"
+ "updateExternalState"
+ "updatePairVerifyFlags"
+ "v24@0:8@\"CUReadRequest\"16"
+ "v24@0:8@\"CUWriteRequest\"16"
+ "v32@0:8@16^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}24"
+ "v32@?0@8@16^B24"
+ "v36@0:8@16Q24B32"
+ "v36@0:8I16Q20i28B32"
+ "v40@0:8@16@24Q32"
+ "v44@0:8@16Q24Q32B40"
+ "v44@0:8I16@20Q28i36B40"
+ "v44@0:8I16Q20Q28Q36"
+ "valueForUndefinedKey:"
+ "xidLast"
+ "{?=qqq}24@0:8@16"
- "### Abort queued ID '%@': %{error}\n"
- "### Abort request XID 0x%X: %{error}\n"
- "### Client error: %{error}\n"
- "### Connect failed: %{error}\n"
- "### Failed to get self identity: %@\n."
- "### Ignoring call to send event ID '%@' when invalidating\n"
- "### Ignoring received PreAuthResponse when not expected: %##@\n"
- "### Ignoring response to requestID '%@' from %@ after invalidation\n"
- "### Ignoring send request ID '%@' when invalidating\n"
- "### PSK prepare failed: %{error}\n"
- "### PairSetup client completion failed: %{error}\n"
- "### PairSetup client receive failed: %{error}\n"
- "### PairSetup server completion failed: %s, %{error}\n"
- "### PairSetup server receive failed: %{error}\n"
- "### PairVerify client completion failed: %{error}\n"
- "### PairVerify client failed: %{error}\n"
- "### PairVerify client receive failed: %{error}\n"
- "### PairVerify server completion failed: %s, %{error}\n"
- "### PairVerify server receive failed: %{error}\n"
- "### PairVerifySign failed: %{error}\n"
- "### PairVerifySign get self identity failed: %{error}\n"
- "### PairVerifyVerify failed: %{error}\n"
- "### PreAuthRequest bad type\n"
- "### PreAuthRequest decode failed: %#m\n"
- "### PreAuthResponse bad type\n"
- "### PreAuthResponse decode failed: %#m\n"
- "### Process unsupported request\n"
- "### Received event with no ID from %@: %#m\n"
- "### Received event with no content from %@: %#m\n"
- "### Received request XID 0x%X with no ID from %@: %#m\n"
- "### Received request with no XID from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X with no content from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X, from %@ with no handler\n"
- "### Received response XID 0x%X with no content from %@: %#m\n"
- "### Received response XID 0x%X with no request from %@\n"
- "### Received response XID 0x%X, error %{error}, from %@, %llu ms\n"
- "### Received response with no XID from %@: %#m\n"
- "### Request timeout '%@' not found, %.3f seconds\n"
- "### Request timeout '%@', %.3f seconds\n"
- "### Request timeout XID 0x%X, %.3f seconds\n"
- "### Send %s encode failed: %#m\n"
- "### Send encrypted data (%zu bytes) failed: '%@', %{error}\n"
- "### Send encrypted requestID '%@' failed: %{error}\n"
- "### Send encrypted response XID 0x%X failed: %{error}\n"
- "### Send frame type 0x%X failed: %{error}\n"
- "### Sending response XID 0x%X, error: %{error}\n"
- "### Server error: %{error}\n"
- "### Timeout for XID 0x%X with no request\n"
- "### Unknown message type: %d\n"
- "### Unsupported send attempt\n"
- "%@ Using IP transport over wireless or wired ethernet"
- "%@ Using P2P transport over BLE"
- "%@ Using P2P transport over WiFi"
- "%@ Using unknown transport"
- "(HK)"
- "(RPI-?)"
- "(RPI-AdHocPaired)"
- "(RPI-Family)"
- "(RPI-Friend)"
- "(RPI-Owner)"
- "(RPI-SessionPaired)"
- "(RPI-SharedTVUser)"
- "-[RPConnection _abortRequestsWithError:]_block_invoke"
- "-[RPConnection _abortSendEntry:withError:]"
- "-[RPConnection _clientConnectCompleted:]"
- "-[RPConnection _clientConnectStartBLE]"
- "-[RPConnection _clientConnectStartBLE]_block_invoke"
- "-[RPConnection _clientConnectStartTCP]_block_invoke_3"
- "-[RPConnection _clientConnectStart]"
- "-[RPConnection _clientError:]"
- "-[RPConnection _clientPairSetupCompleted:]"
- "-[RPConnection _clientPairSetupStart]"
- "-[RPConnection _clientPairSetupWithData:]"
- "-[RPConnection _clientPairVerifyCompleted:]"
- "-[RPConnection _clientPairVerifyStart]"
- "-[RPConnection _clientPairVerifyWithData:]"
- "-[RPConnection _clientPreAuthResponseWithData:]"
- "-[RPConnection _clientPreAuthStart]"
- "-[RPConnection _clientRetryFired]"
- "-[RPConnection _clientRetryStart]"
- "-[RPConnection _clientRun]"
- "-[RPConnection _clientStartSession]"
- "-[RPConnection _configureForSessionPairing:]"
- "-[RPConnection _configureForSessionPairing:]_block_invoke"
- "-[RPConnection _pairVerifySignData:flags:error:]"
- "-[RPConnection _pairVerifyVerifySignature:data:flags:error:]"
- "-[RPConnection _processSends]"
- "-[RPConnection _pskPrepare:]"
- "-[RPConnection _receivedEvent:ctx:]"
- "-[RPConnection _receivedObject:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]_block_invoke"
- "-[RPConnection _receivedResponse:ctx:]"
- "-[RPConnection _receivedSystemInfo:xid:]"
- "-[RPConnection _receivedSystemInfo:xid:]_block_invoke"
- "-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]"
- "-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]"
- "-[RPConnection _sendFrameType:body:]"
- "-[RPConnection _sendFrameType:unencryptedObject:]"
- "-[RPConnection _serverAcceptBLE]_block_invoke_2"
- "-[RPConnection _serverAcceptBTPipe]"
- "-[RPConnection _serverAcceptTCP]_block_invoke_3"
- "-[RPConnection _serverError:]"
- "-[RPConnection _serverPairSetupCompleted:]"
- "-[RPConnection _serverPairSetupWithData:start:]"
- "-[RPConnection _serverPairVerifyCompleted:]"
- "-[RPConnection _serverPairVerifyWithData:start:]"
- "-[RPConnection _serverPreAuthRequestWithData:]"
- "-[RPConnection _serverRun]"
- "-[RPConnection _systeminfo]"
- "-[RPConnection _timeoutForSendEntry:]"
- "-[RPConnection _timeoutForXID:]"
- "-[RPConnection _updateExternalState]"
- "-[RPConnection logConnectionInformation:options:]"
- "-[RPConnection processSendsUsingConnection:]"
- "-[RPConnection sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]"
- "-[RPConnection sendReachabilityProbe:]"
- "AirPlay restrictions ignored\n"
- "BLE client connection invalidated\n"
- "BLE client connection with bundleID: %@ and clientUseCase: %@\n"
- "BLE server connection invalidated\n"
- "Backwards compatibility authType (%s) -> (%s)"
- "Backwards compatibility change authType (%s) -> (%s)"
- "Bad PairSetup request object type %@"
- "Bad PairVerify request object type %@"
- "Client PairSetup retry\n"
- "Client connect start: %@\n"
- "Client error"
- "Client immediate non-RPIdentity retry\n"
- "Client state: %s -> %s\n"
- "Configuring for session pairing\n"
- "Connect failed"
- "Enabling FitnessPairing \n"
- "External state changed: %s -> %s\n"
- "Find paired peer handler for peer %@ options %lu\n"
- "Frame too big (%zu vs %u)"
- "In use processes updated to: %@\n"
- "Large Frame: Send frame 0x%02X (%s), <%.16@> (%zu bytes)\n"
- "Large Frame: Send request ID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s\n"
- "Large Frame: Send response XID 0x%X, <%.16@> (%zu bytes) on link type %s, %#m\n"
- "Large Frame: SendEventID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s\n"
- "No PairSetup client session"
- "No PairVerify client session"
- "OnDemand connection failed, invalidating\n"
- "PairSetup completed client.\n"
- "PairSetup completed server: %s\n"
- "PairSetup next (%d bytes)\n"
- "PairSetup response error: '%@'"
- "PairSetup server rejecting when not allowed\n"
- "PairSetup server rejecting when not allowing non-Home devices\n"
- "PairVerify completed client %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify completed server: %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify next (%d bytes)\n"
- "PairVerify start client: AT %s, CF %#ll{flags}, FL %#{flags}, PWT %s\n"
- "PairVerifySign success: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifySign: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify success: %s, CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "Peer appears missing, invalidating\n"
- "Peer appears present, retrying\n"
- "Peer is blocking access, invalidating\n"
- "Peer may be unreachable, sending reachability probe (%s)\n"
- "Peer missing after retry timer, invalidating\n"
- "Queuing send event ID '%@', XID 0x%X (%d send(s) pending)\n"
- "Queuing send request ID '%@' (%d send(s) pending)\n"
- "Received PreAuthRequest: %##@\n"
- "Received PreAuthResponse: %##@\n"
- "Received SharedHome identity: ID '%.8@'\n"
- "Received client service type %@\n"
- "Received event ID '%@', XID 0x%X, %d keys, from %@\n"
- "Received identity from IDS '%.8@'\n"
- "Received msgID '%@' from %@ with %s\n"
- "Received msgID '%@', XID 0x%X, %d keys, from %@\n"
- "Received requestID '%@', XID 0x%X, %d keys, from %@\n"
- "Received response XID 0x%X, %d keys, from %@, %llu ms request size %llu response size %llu\n"
- "Requested password type: %s auth type: %s\n"
- "Retrying delayed: %.3f seconds\n"
- "Retrying immediately: %{dur} since last retry\n"
- "Retrying immediately: first retry\n"
- "Save paired peer handler for peer %@ options %lu\n"
- "Send PreAuthRequest: %##@\n"
- "Send PreAuthResponse: %##@\n"
- "Send SharedHome identity\n"
- "Send encrypted event failed: '%@', %{error}\n"
- "Send encrypted requestID '%@' failed: %{error}\n"
- "Send frame 0x%02X (%s), <%.16@> (%zu bytes)\n"
- "Send identity\n"
- "Send request ID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Send response XID 0x%X, <%.16@> (%zu bytes) on link type %s%s, %#m\n"
- "SendEventID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Sending client service type %@\n"
- "Server state: %s -> %s\n"
- "SystemInfo"
- "T@\"NSString\",R,N,V_peerAddrString"
- "T@\"NSString\",R,N,V_peerHomeKitUserIdentifier"
- "T@\"RPIdentity\",R,N,V_identityVerified"
- "TCP client connection invalidated\n"
- "TCP server connection invalidated\n"
- "Ti,R,N,V_pairVerifyAuthType"
- "Too many retries, invalidating: retries %d, %@\n"
- "Transferring event ID %@ to connection %@"
- "Transferring request ID %@ to connection %@ with timeout %f\n"
- "Using AdHocPaired identifier for connection: %@"
- "_aaltDSID"
- "_accAltDSID"
- "_accID"
- "_actLvl"
- "_activatedTicks"
- "_appInfo"
- "_auTy"
- "_bf"
- "_btHP"
- "_c"
- "_cf"
- "_cht"
- "_clFl"
- "_clSrv"
- "_dC"
- "_dCapF"
- "_forcedRole"
- "_highPriorityAuthTagLength"
- "_hkID"
- "_hkUID"
- "_homeKitIdentityIdentifier"
- "_homeKitIdentitySignature"
- "_identityKeyData"
- "_identitySignature"
- "_identityVerified"
- "_idsCID"
- "_inUseProc"
- "_lP"
- "_mRtID"
- "_mainAuthTagLength"
- "_mrID"
- "_msId"
- "_msNm"
- "_msRo"
- "_msSt"
- "_osV"
- "_pairSetupAuthType"
- "_pairVerifyIdentityType"
- "_pairVerifyUsedIdentity"
- "_pd"
- "_peerAddrString"
- "_peerHomeKitUserIdentifier"
- "_ping"
- "_pubID"
- "_pwTy"
- "_rP"
- "_rT"
- "_receivedFrameCountCurrent"
- "_receivedFrameCountLast"
- "_requestable"
- "_retryFired"
- "_retryTicks"
- "_selfAddrString"
- "_sf"
- "_spID"
- "_stA"
- "_sv"
- "_t"
- "_x"
- "com.apple.admin"
- "dictionaryWithObjectsAndKeys:"
- "fixedPIN"
- "hipri"
- "ids-message"
- "logConnectionInformation:options:"
- "main"
- "public"
- "sendFrameType"
- "v32@?0@\"NSNumber\"8@\"RPRequestEntry\"16^B24"
```
