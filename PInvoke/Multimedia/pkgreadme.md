﻿![Vanara](https://github.com/dahall/Vanara/raw/master/docs/icons/VanaraHeading.png)
### Vanara.PInvoke.Multimedia NuGet Package
[![Version](https://img.shields.io/nuget/v/Vanara.PInvoke.Multimedia?label=NuGet&style=flat-square)](https://github.com/dahall/Vanara/releases)
[![Build status](https://img.shields.io/appveyor/build/dahall/vanara?label=AppVeyor%20build&style=flat-square)](https://ci.appveyor.com/project/dahall/vanara)

PInvoke API (methods, structures and constants) imported from Windows Multimedia (avicap32.dll, avifil32.dll, msacm32.dll, msvfw32.dll, winmm.dll).

### What is Vanara?

[Vanara](https://github.com/dahall/Vanara) is a community project that contains various .NET assemblies which have P/Invoke functions, interfaces, enums and structures from Windows libraries. Each assembly is associated with one or a few tightly related libraries.

### Issues?

First check if it's already fixed by trying the [AppVeyor build](https://ci.appveyor.com/nuget/vanara-prerelease).
If you're still running into problems, file an [issue](https://github.com/dahall/Vanara/issues).

### Included in Vanara.PInvoke.Multimedia

Functions | Enumerations | Structures | Interfaces
--- | --- | --- | ---
acmDriverAdd<br>acmDriverClose<br>acmDriverDetails<br>acmDriverEnum<br>acmDriverID<br>acmDriverMessage<br>acmDriverOpen<br>acmDriverPriority<br>acmDriverRemove<br>acmFilterChoose<br>acmFilterDetails<br>acmFilterEnum<br>acmFilterTagDetails<br>acmFilterTagEnum<br>acmFormatChoose<br>acmFormatDetails<br>acmFormatEnum<br>acmFormatSuggest<br>acmFormatTagDetails<br>acmFormatTagEnum<br>acmGetVersion<br>acmMetrics<br>acmStreamClose<br>acmStreamConvert<br>acmStreamMessage<br>acmStreamOpen<br>acmStreamPrepareHeader<br>acmStreamReset<br>acmStreamSize<br>acmStreamUnprepareHeader<br>auxGetDevCaps<br>auxGetNumDevs<br>auxGetVolume<br>auxOutMessage<br>auxSetVolume<br>AVIBuildFilter<br>AVIClearClipboard<br>AVIFileAddRef<br>AVIFileCreateStream<br>AVIFileEndRecord<br>AVIFileExit<br>AVIFileGetStream<br>AVIFileInfo<br>AVIFileInit<br>AVIFileOpen<br>AVIFileReadData<br>AVIFileRelease<br>AVIFileWriteData<br>AVIGetFromClipboard<br>AVIMakeCompressedStream<br>AVIMakeFileFromStreams<br>AVIMakeStreamFromClipboard<br>AVIPutFileOnClipboard<br>AVISave<br>AVISaveOptions<br>AVISaveOptionsFree<br>AVISaveV<br>AVIStreamAddRef<br>AVIStreamBeginStreaming<br>AVIStreamCreate<br>AVIStreamEndStreaming<br>AVIStreamFindSample<br>AVIStreamGetFrame<br>AVIStreamGetFrameClose<br>AVIStreamGetFrameOpen<br>AVIStreamInfo<br>AVIStreamLength<br>AVIStreamOpenFromFile<br>AVIStreamRead<br>AVIStreamReadData<br>AVIStreamReadFormat<br>AVIStreamRelease<br>AVIStreamSampleToTime<br>AVIStreamSetFormat<br>AVIStreamStart<br>AVIStreamTimeToSample<br>AVIStreamWrite<br>AVIStreamWriteData<br>capCreateCaptureWindow<br>capGetDriverDescription<br>CloseDriver<br>CreateEditableStream<br>DefDriverProc<br>DrawDibBegin<br>DrawDibChangePalette<br>DrawDibClose<br>DrawDibDraw<br>DrawDibEnd<br>DrawDibGetBuffer<br>DrawDibGetPalette<br>DrawDibOpen<br>DrawDibProfileDisplay<br>DrawDibRealize<br>DrawDibSetPalette<br>DrawDibStart<br>DrawDibStop<br>DrawDibTime<br>DriverCallback<br>DrvDefDriverProc<br>DrvGetModuleHandle<br>EditStreamClone<br>EditStreamCopy<br>EditStreamCut<br>EditStreamPaste<br>EditStreamSetInfo<br>EditStreamSetName<br>GetDriverModuleHandle<br>GetOpenFileNamePreview<br>GetSaveFileNamePreview<br>ICClose<br>ICCompress<br>ICCompressorChoose<br>ICCompressorFree<br>ICDecompress<br>ICDraw<br>ICDrawBegin<br>ICGetDisplayFormat<br>ICGetInfo<br>ICImageCompress<br>ICImageDecompress<br>ICInfo<br>ICInstall<br>ICLocate<br>ICOpen<br>ICOpenFunction<br>ICRemove<br>ICSendMessage<br>ICSeqCompressFrame<br>ICSeqCompressFrameEnd<br>ICSeqCompressFrameStart<br>joyConfigChanged<br>joyGetDevCaps<br>joyGetNumDevs<br>joyGetPos<br>joyGetPosEx<br>joyGetThreshold<br>joyReleaseCapture<br>joySetCapture<br>joySetThreshold<br>MCIWndCreate<br>MCIWndRegisterClass<br>midiConnect<br>midiDisconnect<br>midiInAddBuffer<br>midiInClose<br>midiInGetDevCaps<br>midiInGetErrorText<br>midiInGetID<br>midiInGetNumDevs<br>midiInMessage<br>midiInOpen<br>midiInPrepareHeader<br>midiInReset<br>midiInStart<br>midiInStop<br>midiInUnprepareHeader<br>midiOutCacheDrumPatches<br>midiOutCachePatches<br>midiOutClose<br>midiOutGetDevCaps<br>midiOutGetErrorText<br>midiOutGetID<br>midiOutGetNumDevs<br>midiOutGetVolume<br>midiOutLongMsg<br>midiOutMessage<br>midiOutOpen<br>midiOutPrepareHeader<br>midiOutReset<br>midiOutSetVolume<br>midiOutShortMsg<br>midiOutUnprepareHeader<br>midiStreamClose<br>midiStreamOpen<br>midiStreamOut<br>midiStreamPause<br>midiStreamPosition<br>midiStreamProperty<br>midiStreamRestart<br>midiStreamStop<br>mixerClose<br>mixerGetControlDetails<br>mixerGetDevCaps<br>mixerGetID<br>mixerGetLineControls<br>mixerGetLineInfo<br>mixerGetNumDevs<br>mixerMessage<br>mixerOpen<br>mixerSetControlDetails<br>mmioAdvance<br>mmioAscend<br>mmioClose<br>mmioCreateChunk<br>mmioDescend<br>mmioFlush<br>mmioGetInfo<br>mmioInstallIOProc<br>mmioOpen<br>mmioRead<br>mmioRename<br>mmioSeek<br>mmioSendMessage<br>mmioSetBuffer<br>mmioSetInfo<br>mmioStringToFOURCC<br>mmioWrite<br>OpenDriver<br>PlaySound<br>SendDriverMessage<br>sndOpenSound<br>sndPlaySound<br>StretchDIB<br>timeBeginPeriod<br>timeEndPeriod<br>timeGetDevCaps<br>timeGetSystemTime<br>timeGetTime<br>waveInAddBuffer<br>waveInClose<br>waveInGetDevCaps<br>waveInGetErrorText<br>waveInGetID<br>waveInGetNumDevs<br>waveInGetPosition<br>waveInMessage<br>waveInOpen<br>waveInPrepareHeader<br>waveInReset<br>waveInStart<br>waveInStop<br>waveInUnprepareHeader<br>waveOutBreakLoop<br>waveOutClose<br>waveOutGetDevCaps<br>waveOutGetErrorText<br>waveOutGetID<br>waveOutGetNumDevs<br>waveOutGetPitch<br>waveOutGetPlaybackRate<br>waveOutGetPosition<br>waveOutGetVolume<br>waveOutMessage<br>waveOutOpen<br>waveOutPause<br>waveOutPrepareHeader<br>waveOutReset<br>waveOutRestart<br>waveOutSetPitch<br>waveOutSetPlaybackRate<br>waveOutSetVolume<br>waveOutUnprepareHeader<br>waveOutWrite<br> | JOY_BUTTON<br>JOYCAPSF<br>JOYINFOEXF<br>JOY_ISCAL<br>JOY_POVVAL<br>AUX_CAPS<br>MHDR<br>MIDI_CACHE<br>MIDI_CAPS<br>MIDIPROP<br>MOD<br>MIXER_OBJECTF<br>MIXERCONTROL_CONTROLF<br>MIXERCONTROL_CT<br>MIXERLINE_COMPONENTTYPE<br>MIXERLINE_LINEF<br>WAVE_OPEN<br>WAVECAPS<br>WHDR<br>DCB<br>DRV<br>MMIO<br>MMIOCLOSE<br>MMIOCONV<br>MMIOCREATE<br>MMIODESC<br>MMIOFLUSH<br>MMIOINST<br>MMIOM<br>WAVE_FORMAT<br>CALLBACK_FLAGS<br>MMPRODID<br>MMRESULT<br>MMTIME_TYPE<br>SND<br>ACM_DRIVERADDF<br>ACM_DRIVERENUMF<br>ACM_DRIVERPRIORITYF<br>ACM_FILTERDETAILSF<br>ACM_FILTERENUMF<br>ACM_FILTERTAGDETAILSF<br>ACM_FORMATDETAILSF<br>ACM_FORMATENUMF<br>ACM_FORMATSUGGESTF<br>ACM_FORMATTAGDETAILSF<br>ACM_METRIC<br>ACM_STREAMCONVERTF<br>ACM_STREAMOPENF<br>ACM_STREAMSIZEF<br>ACMDRIVERDETAILS_SUPPORTF<br>ACMFILTERCHOOSE_STYLEF<br>ACMFORMATCHOOSE_STYLEF<br>ACMSTREAMHEADER_STATUSF<br>AVICOMPRESSF<br>AVIFILECAPS<br>AVIFILEINFOF<br>AVIIF<br>AVISTREAMINFOF<br>AVSTREAMMASTER<br>FINDF<br>ICMF_CHOOSE<br>VHDR<br>capMessage<br>CONTROLCALLBACK<br>VHDR<br>MCI<br>MCI_FORMAT<br>MCI_MODE<br>MCIMessage<br>MCIWNDF<br>MCIWNDOPENF<br>DDF<br>ICCOMPRESSF<br>ICCOMPRESSFRAMESF<br>ICDECOMPRESSF<br>ICDRAWF<br>ICERR<br>ICINSTALL<br>ICM_Message<br>ICMF_CHOOSE<br>ICMF_COMPVARS<br>ICMODE<br>VIDCF<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> | JOYCAPS<br>JOYINFO<br>JOYINFOEX<br>JOYPOS<br>JOYRANGE<br>JOYREGHWVALUES<br>MDEVICECAPSEX<br>MIDIOPENDESC<br>MIDIOPENSTRMID<br>AUXCAPS<br>HMIDI<br>HMIDIIN<br>HMIDIOUT<br>HMIDISTRM<br>MIDIEVENT<br>MIDIHDR<br>MIDIINCAPS<br>MIDIOUTCAPS<br>MIDIPROPTEMPO<br>MIDIPROPTIMEDIV<br>MIDISTRMBUFFVER<br>HMIXER<br>HMIXEROBJ<br>MIXERCAPS<br>MIXERCONTROL<br>MIXERCONTROLDETAILS<br>MIXERCONTROLDETAILS_BOOLEAN<br>MIXERCONTROLDETAILS_LISTTEXT<br>MIXERCONTROLDETAILS_SIGNED<br>MIXERCONTROLDETAILS_UNSIGNED<br>MIXERLINE<br>MIXERLINECONTROLS<br>HWAVEIN<br>HWAVEOUT<br>WAVEFORMATEX<br>WAVEFORMATEXTENSIBLE<br>WAVEHDR<br>WAVEINCAPS<br>WAVEOUTCAPS<br>DRVCONFIGINFO<br>HDRVR<br>HMMIO<br>MMCKINFO<br>MMIOINFO<br>PCMWAVEFORMAT<br>WAVEFILTER<br>WAVEFORMAT<br>MMTIME<br>TIMECAPS<br>ACMDRIVERDETAILS<br>ACMFILTERCHOOSE<br>ACMFILTERDETAILS<br>ACMFILTERTAGDETAILS<br>ACMFORMATCHOOSE<br>ACMFORMATDETAILS<br>ACMFORMATTAGDETAILS<br>ACMSTREAMHEADER<br>HACMDRIVER<br>HACMDRIVERID<br>HACMOBJ<br>HACMSTREAM<br>AVICOMPRESSOPTIONS<br>AVIFILEINFO<br>AVISTREAMINFO<br>CAPDRIVERCAPS<br>CAPINFOCHUNK<br>CAPSTATUS<br>CAPTUREPARMS<br>DRAWDIBTIME<br>VIDEOHDR<br>CAPDRIVERCAPS<br>CAPINFOCHUNK<br>CAPSTATUS<br>CAPTUREPARMS<br>VIDEOHDR<br>COMPVARS<br>DRAWDIBTIME<br>HDRAWDIB<br>HIC<br>ICCOMPRESS<br>ICCOMPRESSFRAMES<br>ICDECOMPRESS<br>ICDECOMPRESSEX<br>ICDRAW<br>ICDRAWBEGIN<br>ICDRAWSUGGEST<br>ICINFO<br>ICOPEN<br>ICSETSTATUSPROC<br>BOUNDS<br>METRICS<br>TARGET<br>SAMPLES<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> | IAVIEditStream<br>IAVIFile<br>IAVIStream<br>IAVIStreaming<br>IGetFrame<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>