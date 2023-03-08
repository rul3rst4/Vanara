﻿![Vanara](https://raw.githubusercontent.com/dahall/Vanara/master/docs/icons/VanaraHeading.png)
### **Vanara.PInvoke.CoreAudio NuGet Package**
[![Version](https://img.shields.io/nuget/v/Vanara.PInvoke.CoreAudio?label=NuGet&style=flat-square)](https://github.com/dahall/Vanara/releases)
[![Build status](https://img.shields.io/appveyor/build/dahall/vanara?label=AppVeyor%20build&style=flat-square)](https://ci.appveyor.com/project/dahall/vanara)

PInvoke API (interfaces, methods, structures and constants) imported from Windows Core Audio Api.

### **What is Vanara?**

[Vanara](https://github.com/dahall/Vanara) is a community project that contains various .NET assemblies which have P/Invoke functions, interfaces, enums and structures from Windows libraries. Each assembly is associated with one or a few tightly related libraries.

### **Issues?**

First check if it's already fixed by trying the [AppVeyor build](https://ci.appveyor.com/nuget/vanara-prerelease).
If you're still running into problems, file an [issue](https://github.com/dahall/Vanara/issues).

### **Included in Vanara.PInvoke.CoreAudio**

Functions | Enumerations | Structures | Interfaces
--- | --- | --- | ---
ActivateAudioInterfaceAsync                                                                                                             | APO_BUFFER_FLAGS AUDIO_CURVE_TYPE AMBISONICS_CHANNEL_ORDERING AMBISONICS_NORMALIZATION AMBISONICS_TYPE AUDCLNT_BUFFERFLAGS AUDCLNT_STREAMOPTIONS AUDIO_DUCKING_OPTIONS AUDIO_EFFECT_STATE AUDIOCLIENT_ACTIVATION_TYPE PROCESS_LOOPBACK_MODE ENDPOINT_RESET APO_CONNECTION_BUFFER_TYPE APO_FLAG AUDIO_FLOW_TYPE EAudioConstriction AE_POSITION_FLAGS EndpointConnectorType APO_LOG_LEVEL APO_NOTIFICATION_TYPE AUDIO_SYSTEMEFFECT_STATE DEVICE_ORIENTATION_TYPE UDIOMEDIATYPE_EQUAL AudioSessionDisconnectReason AUDCLNT_SESSIONFLAGS AUDCLNT_SHAREMODE AUDCLNT_STREAMFLAGS AUDIO_STREAM_CATEGORY AudioSessionState ChannelMapping ConnectorType DataFlow EPcxConnectionType EPcxGenLocation EPcxGeoLocation EPxcPortConnection JackCapabilities KSJACK_SINK_CONNECTIONTYPE PartType ENDPOINT_HARDWARE_SUPPORT AUDIO_SYSTEMEFFECTS_PROPERTYSTORE_TYPE DEVICE_STATE EDataFlow EndpointFormFactor ERole AudioObjectType SPATIAL_AUDIO_STREAM_OPTIONS SpatialAudioHrtfDirectivityType SpatialAudioHrtfDistanceDecayType SpatialAudioHrtfEnvironmentType SpatialAudioMetadataCopyMode SpatialAudioMetadataWriterOverflowMode                                                          | APO_CONNECTION_PROPERTY AMBISONICS_PARAMS AUDIO_EFFECT AudioClientProperties AUDIOCLIENT_ACTIVATION_PARAMS AUDIOCLIENT_PROCESS_LOOPBACK_PARAMS APO_CONNECTION_DESCRIPTOR APO_REG_PROPERTIES APOInitBaseStruct APOInitSystemEffects APOInitSystemEffects2 AudioFXExtensionParams AE_CURRENT_POSITION AUDIO_ENDPOINT_SHARED_CREATE_PARAMS APO_NOTIFICATION_DESCRIPTOR APOInitSystemEffects3 AUDIO_ENDPOINT_PROPERTY_CHANGE_APO_NOTIFICATION_DESCRIPTOR AUDIO_ENDPOINT_PROPERTY_CHANGE_NOTIFICATION AUDIO_ENDPOINT_VOLUME_APO_NOTIFICATION_DESCRIPTOR AUDIO_ENDPOINT_VOLUME_CHANGE_NOTIFICATION AUDIO_ENDPOINT_VOLUME_CHANGE_NOTIFICATION2 AUDIO_MICROPHONE_BOOST_APO_NOTIFICATION_DESCRIPTOR AUDIO_MICROPHONE_BOOST_NOTIFICATION AUDIO_SYSTEMEFFECT AUDIO_SYSTEMEFFECTS_PROPERTY_CHANGE_APO_NOTIFICATION_DESCRIPTOR AUDIO_SYSTEMEFFECTS_PROPERTY_CHANGE_NOTIFICATION AUDIO_VOLUME_NOTIFICATION_DATA2 UNCOMPRESSEDAUDIOFORMAT KSJACK_DESCRIPTION KSJACK_DESCRIPTION2 KSJACK_SINK_INFORMATION AUDIO_VOLUME_NOTIFICATION_DATA DIRECTX_AUDIO_ACTIVATION_PARAMS SpatialAudioClientActivationParams SpatialAudioObjectRenderStreamActivationParams SpatialAudioObjectRenderStreamActivationParams2 SpatialAudioHrtfActivationParams SpatialAudioHrtfActivationParams2 SpatialAudioHrtfDirectivity SpatialAudioHrtfDirectivityCardioid SpatialAudioHrtfDirectivityCone SpatialAudioHrtfDirectivityUnion SpatialAudioHrtfDistanceDecay SpatialAudioHrtfOrientation SpatialAudioMetadataItemsInfo SpatialAudioObjectRenderStreamForMetadataActivationParams SpatialAudioObjectRenderStreamForMetadataActivationParams2                                                               | IAcousticEchoCancellationControl IAudioAmbisonicsControl IAudioCaptureClient IAudioClient IAudioClient2 IAudioClient3 IAudioClientDuckingControl IAudioClock IAudioClock2 IAudioClockAdjustment IAudioEffectsChangedNotificationClient IAudioEffectsManager IAudioRenderClient IAudioStreamVolume IAudioViewManagerService IChannelAudioVolume ISimpleAudioVolume IAudioEndpointFormatControl IApoAcousticEchoCancellation IApoAuxiliaryInputConfiguration IApoAuxiliaryInputRT IAudioProcessingObject IAudioProcessingObjectConfiguration IAudioProcessingObjectRT IAudioProcessingObjectVBR IAudioSystemEffects IAudioSystemEffects2 IAudioSystemEffectsCustomFormats IAudioDeviceEndpoint IAudioEndpoint IAudioEndpointControl IAudioEndpointLastBufferControl IAudioEndpointOffloadStreamMeter IAudioEndpointOffloadStreamMute IAudioEndpointOffloadStreamVolume IAudioEndpointRT IAudioInputEndpointRT IAudioLfxControl IAudioOutputEndpointRT IHardwareAudioEngineBase IAudioProcessingObjectLoggingService IAudioProcessingObjectNotifications IAudioProcessingObjectNotifications2 IAudioProcessingObjectRTQueueService IAudioSystemEffects3 IAudioMediaType IAudioSessionControl IAudioSessionControl2 IAudioSessionEnumerator IAudioSessionEvents IAudioSessionManager IAudioSessionManager2 IAudioSessionNotification IAudioVolumeDuckNotification IAudioAutoGainControl IAudioBass IAudioChannelConfig IAudioInputSelector IAudioLoudness IAudioMidrange IAudioMute IAudioOutputSelector IAudioPeakMeter IAudioTreble IAudioVolumeLevel IConnector IControlChangeNotify IControlInterface IDeviceSpecificProperty IDeviceTopology IKsFormatSupport IKsJackDescription IKsJackDescription2 IKsJackSinkInformation IPart IPartsList IPerChannelDbLevel ISubunit IAudioEndpointVolume IAudioEndpointVolumeCallback IAudioEndpointVolumeEx IAudioMeterInformation IActivateAudioInterfaceAsyncOperation IActivateAudioInterfaceCompletionHandler IMMDevice IMMDeviceCollection IMMDeviceEnumerator IMMEndpoint IMMNotificationClient IAudioFormatEnumerator ISpatialAudioClient ISpatialAudioClient2 ISpatialAudioObject ISpatialAudioObjectBase ISpatialAudioObjectRenderStream ISpatialAudioObjectRenderStreamBase ISpatialAudioObjectRenderStreamNotify ISpatialAudioObjectForHrtf ISpatialAudioObjectRenderStreamForHrtf ISpatialAudioMetadataClient ISpatialAudioMetadataCopier ISpatialAudioMetadataItems ISpatialAudioMetadataItemsBuffer ISpatialAudioMetadataReader ISpatialAudioMetadataWriter ISpatialAudioObjectForMetadataCommands ISpatialAudioObjectForMetadataItems ISpatialAudioObjectRenderStreamForMetadata 