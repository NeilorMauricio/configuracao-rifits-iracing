# Configuração RifitS iRacing 😉

Minha configuração para usar o RiftS no simulador iRacing de forma satisfatória 🤞

## app.in

[Audio]
allowHardwareStreams=1                  	; DirectSound: try to use hardware streams if available
channelMaskToStereo=1                   	; Promote mono sounds to stereo when particular speaker is selected
devLFEAPI=1                             	; 0 = None, 1 = DirectSound
devLFEDefault=0                         	; 0 = use specified device, 1 = use default device
devLFEId={EB0EFFA2-CD05-4F68-95FE-A53292659806}	; Identifier for the selected sound device
devLFEName=Fones de ouvido (2- Rift S)  	; Name of the sound device
devMicrophoneAPI=1                      	; 0 = None, 1 = DirectSound
devMicrophoneDefault=0                  	; 0 = use specified device, 1 = use default device
devMicrophoneDevName=Microfone do Headset (3- Logitech F540 Headset)	; Name of the sound device
devMicrophoneDxDefault=0                	; DirectSound: 0 = specified device, 1 = default device
devMicrophoneDxId={303E809C-4A6A-45BD-B567-C7E7F3EE105A}	; DirectSound: Identifier for the seleted sound device
devMicrophoneId={D5F993B8-70B8-4BCA-9E3D-7DAA5168CC88}	; Identifier for the selected sound device
devMicrophoneName=Microfone do Headset (Rift S)	; Name of the sound device
devSPCCAPI=1                            	; 0 = None, 1 = DirectSound
devSPCCDefault=0                        	; 0 = use specified device, 1 = use default device
devSPCCDevName=Fone de ouvido do headset (3- Logitech F540 Headset)	; Name of the sound device
devSPCCDxDefault=0                      	; DirectSound: 0 = specified device, 1 = default device
devSPCCDxId={99AF2833-71C2-4926-868C-A55B51636296}	; DirectSound: Identifier for the seleted sound device
devSPCCId={D4915D14-C8BA-417B-B90B-89D22C033249}	; Identifier for the selected sound device
devSPCCName=Fones de ouvido (Rift S)    	; Name of the sound device
devSpeakerAPI=2                         	; 0 = None, 1 = DirectSound, 2 = XAudio2
devSpeakerDefault=0                     	; 0 = use specified device, 1 = use default device
devSpeakerDevName=Fone de ouvido do headset (3- Logitech F540 Headset)	; Name of the sound device
devSpeakerDxDefault=0                   	; DirectSound: 0 = specified device, 1 = default device
devSpeakerDxId={99AF2833-71C2-4926-868C-A55B51636296}	; DirectSound: Identifier for the seleted sound device
devSpeakerId={0.0.0.00000000}.{eb0effa2-cd05-4f68-95fe-a53292659806}	; Identifier for the selected sound device
devSpeakerName=Fones de ouvido (2- Rift S)	; Name of the sound device
devVoiceChatAPI=1                       	; 0 = None, 1 = DirectSound
devVoiceChatDefault=0                   	; 0 = use specified device, 1 = use default device
devVoiceChatDevName=Fone de ouvido do headset (3- Logitech F540 Headset)	; Name of the sound device
devVoiceChatDxDefault=0                 	; DirectSound: 0 = specified device, 1 = default device
devVoiceChatDxId={99AF2833-71C2-4926-868C-A55B51636296}	; DirectSound: Identifier for the seleted sound device
devVoiceChatId={EB0EFFA2-CD05-4F68-95FE-A53292659806}	; Identifier for the selected sound device
devVoiceChatName=Fones de ouvido (2- Rift S)	; Name of the sound device
dimensions=3                            	; 1 = mono, 2 = stereo, 3 = surround
forceStreamToSurround=1                 	; DirectSound: force voice chat and spotter to surround if enabled
loudnessAmbient=0.000000                	; Volume adjustment for ambient noise in dB
loudnessCrash=-9.900000                 	; Volume adjustment for scrapes and crashes in dB
loudnessEngine=0.000000                 	; Volume adjustment for engines in dB
loudnessIncar=0.000000                  	; Volume adjustment for incar sounds in dB
loudnessLFE=-15.000000                  	; Volume adjustment for LFE noise in dB
loudnessReplay=0.000000                 	; Volume adjustment for overall replay volume versus driving volume in dB
loudnessSPCC=-15.000000                 	; Volume adjustment for spotter noise in dB
loudnessTires=0.000000                  	; Volume adjustment for tires in dB
loudnessVoiceChat=-15.000000            	; Volume adjustment for voice chat noise in dB
loudnessWind=-10.300000                 	; Volume adjustment for wind in dB
masterVolumedB=-15.100000               	; Master volume adjustment in dB, range is -40 dB to 0 dB
micAlwaysActive=1                       	; Set this to 0 if your graphics stutter when a microphone is configured, but doing so may cause worse stutters while recording for voice chat
mute_WhenFocusLost=0                    	; set this to 0 to hear sim sounds when another program has the keyboard focus
numSoundStreams=-1                      	; Maximum number of audible sounds
overrideSpccRate=0                      	; If set to 1, the spotter sounds will be resampled to play back at the general sample rate.  This is a compatibility fix for sound cards with limited playback rates and is not recommended for general use.
overrideVoiceChatRate=0                 	; If set to 1, void chat will be resampled to play back at the general sample rate.  This is a compatibility fix for sound cards with limited playback rates and is not recommended for general use.
radioScriptsEnabled=1                   	; Run startup, start/stop driving, and start/stop spotting radio scripts in documents\iracing\scripts\radio.
rotateWithHeadset=1                     	; 0 = no, 1 = rotate microphone with VR headset movement
sampleRate=22050                        	; sample rate to run sound system at
stereoStreamInSurroundBalance=0.200000  	; DirectSound: stereo streams (the engine) in surround mode need a system specific adjustment to match volume with surround streams
voiceChatEnabled=1                      	; Enable or Disable Voice Chat.
voiceChatEnabledWhileDriving=0          	; Enable voice chat while driving.
voiceChatMuted=0                        	; Mute voice chat - overrides voiceChatVolume.
voiceChatNotificationStyle=2            	; Voice chat notification style.
voiceChatSaveToReplay=2                 	; 0=All channels, 1=All but user-created channels, 2=All but user-created and @TEAM, 3=None
xa2_mixToLFE=1                          	; Send xaudio sound to LFE channel in addition to normal channels

[Autochat Messages]
AutoChatStr1=Stay greenFlag for start!$ 	; Auto chat message, use $ at the end to auto transmit without hitting enter
AutoChatStr10=Shut up, crazy fool!$     	; Auto chat message
AutoChatStr11=#lf rf lr rr ws fuel 500g$	; Auto chat message
AutoChatStr12=#rf rr$                   	; Auto chat message
AutoChatStr13=#lf rf lr rr$             	; Auto chat message
AutoChatStr14=#fuel 2g$                 	; Auto chat message
AutoChatStr15=#fuel 10g$                	; Auto chat message
AutoChatStr2=You're not a racing driver, you're a *$	; Auto chat message,
AutoChatStr3=Beep-Beep!!!$              	; Auto chat message
AutoChatStr4=GO!GO!GO! MUSTANG$         	; Auto chat message
AutoChatStr5=Sorry!$                    	; Auto chat message
AutoChatStr6=Thanks!$                   	; Auto chat message
AutoChatStr7=You're welcome$            	; Auto chat message
AutoChatStr8=plz more pratice$          	; Auto chat message
AutoChatStr9=Quit yo Jibber-jabber!$    	; Auto chat message

[BassShaker]
enableGameEffects=1                     	; Enable game audio based vibrations for bass shakers
enablePysEffects=1                      	; Enable physics based vibrations for bass shakers
freqGameLowpass_Hz=200.000000           	; Set the cuttoff frequency in Hz of the game audio lowpass filter
LFEEnabled=0                            	; Enable or Disable LFE bass shaker effect.
LFESpeakerID=0                          	; ID of the current speaker channel for LFE sound output
volGameMaster_dB=-5.000000              	; How much to duck or raise volume of the game audio bass shaker effect, in Decibels
volPhysCarBodyAccel_dB=0.000000         	; How much to duck or raise volume of the car body acceleration bass shaker effects, in Decibels
volPhysEngineRPM_dB=-20.000000          	; How much to duck or raise volume of the engine rpm bass shaker effects, in Decibels
volPhysGearChange_dB=0.000000           	; How much to duck or raise volume of the gear change bass shaker effects, in Decibels
volPhysMaster_dB=0.000000               	; How much to duck or raise volume of all physics based bass shaker effects, in Decibels
volPhysRevLimit_dB=-3.000000            	; How much to duck or raise volume of the rev limit bass shaker effects, in Decibels
volPhysRumbleStrip_dB=-6.000000         	; How much to duck or raise volume of the rumble strip bass shaker effects, in Decibels
volPhysWheelSlip_dB=-2.000000           	; How much to duck or raise volume of the wheel slip bass shaker effects, in Decibels

[CamTool]
autoShotSelection=1                     	; Automatically switch cameras based on shot quality
camTempEdit=0                           	; don't save edits to cameras, useful for 'live' edits
ctrlIncAccel=1                          	; use acceleration when adjusting cameras
ctrlIncScalar=10.000000                 	; scalar to use when selecting fast move mode
ctrlIncScalarAll=0                      	; Apply fast move mode (10x) to all adjustments, or just movements
ctrlIncScalarApply=0                    	; enable fast move mode (10x)
ctrlIncVal=1.029940                     	; step size when adjusting cameras
focusIncALin=6.000000                   	; adjust linearity of analog focus controls, 1 == linear, 6 == very nonlinear
focusIncAScalar=10.000000               	; adjust focus adjustment speed for analog controls
fovIncALin=4.000000                     	; adjust linearity of analog FOV controls, 1 == linear, 6 == very nonlinear
fovIncAScalar=20.000000                 	; adjust FOV adjustment speed for analog controls
linearPanBlend=0.000000                 	; 0.0 - pan slows down with increased zoom, 1.0 - pan remains constant
miscIncALin=4.000000                    	; adjust linearity of analog misc camera controls, 1 == linear, 6 == very nonlinear
miscIncAScalar=4.000000                 	; adjust misc camera tool adjustment speed for analog controls
mouseAimRemainOnPlatform=1              	; Leave camear attached to platform (blimp, etc) when opening mouse aim mode.
mouseAimUpdateOnExit=0                  	; Update base camera with position and orientation when closing mouse aim mode.
rotIncALin=4.000000                     	; adjust linearity of analog rotation (yaw,pitch,roll) controls, 1 == linear, 6 == very nonlinear
rotIncAScalar=4.000000                  	; adjust rotation (yaw,pitch,roll) adjustment speed for analog controls
showCamMode=0                           	; display cameras in world, 0-Live, 1-Wide, 2-Front, 3-Side, 4-Top
transIncALin=4.000000                   	; adjust linearity of analog translation (x,y,z) controls, 1 == linear, 6 == very nonlinear
transIncAScalar=4.000000                	; adjust translation (x,y,z) adjustment speed for analog controls

[Commercial]
SkipInvalidResults=0                    	; In looping qualify, skip over results display if no valid lap time

[Drive Screen]
blackBox=2                              	; Which black box to display
blackBoxPitStop=2                       	; Which pit stop black box to display
resetCanExitCar=1                       	; Does pressing <reset> exit the car while in the pit stall?
showRadioControls=0                     	; Display the radio channel control while driving?
showSpeedGearControls=1                 	; Display the Speed / Gear / Pedals / Wheel black box?
showVideoTimer=0                        	; Display a clock on the screen that can be used to syncronize live video with a replay
UIOffsetBottomPct=0                     	; Shift bottom of UI up by specified percent
VirtualMirrorSize=1                     	; Size of virtual mirror, 0-large, 1-med, 2-small, 3-extra small

[External_Displays]
arxDisplayPack=ir_hud                   	; What display to show on the Logitech ARX client.
colorLEDHotKeysByType=1                 	; Set to 0 to color all hotkey indicators the same color
enableLCDDisplay=1                      	; Animate the LCD display on some wheels
enableLEDFlags=1                        	; Set to 0 to turn off the flag animations
enableLEDHotKeys=1                      	; Set to 0 to turn off the keyboard hotkey indicators
enableLEDShiftLights=1                  	; Set to 0 to turn off the rpm shift indicator animations
enableLogitechARX=0                     	; Enable Logitech ARX client to create a digital dash on your smartphone
enableLogitechLED=0                     	; Animate the backlights on RGB gaming keyboards
phoneCanSteer=0                         	; Allow phone device to act as a steering wheel

[Force Feedback]
allowXBoxOneOnWindows10=1               	; Set to 1 to talk to xbox one game pads on windows 10, warning the driver is buggy
alwaysRestartFX=0                       	; Always restart force when updating it, set to true if wheel goes limp after a while
calibUsingRawData=0                     	; Use raw joystick position over windows calibration data when detecting new joysticks
centerSpringPct=-1                      	; Percent (0-100) of static centering spring force to apply, -1 is off.  Not reccomended for use.
damperMode=0                            	; Set damper effect type 0 = Damper 1 = Inertia 2 = Friction
damperSaturation=10000                  	; Set damper saturation from 0 to 10000
dampingSliderSetsFriction=0             	; True if damping slider adjust friction effect, false to adjust wheels built in damping effect
debounceSeq_Ms=80                       	; Add delay in Milliseconds to sequential shifter to reduce double shifts
disableAutoCenter=1                     	; Turn auto center off on all force feedback devices
displayLinearInNm=0                     	; Display the force level in peak Nm when using the linear mode
enableHotPlug=1                         	; Set to 0 to turn off usb hot plugging in case you have usb disconnect issues
enableWheelDisplay=0                    	; Enable the use of steering wheel displays
enableWheelDisplayBlink=1               	; Enable the display lights to blink when at the rev limit
FFBAlwaysReset=0                        	; Reset the force feedback every time you enter your car, may help with some wheels.
FFBUseForceLimiter=1                    	; 1 - limit force of impacts and oscillations
FFBUseSimpleMinForce=0                  	; 0 - Use smoothed min force, 1 - use old sharp min force
forceNoiseSuppression=0                 	; Remove noisy joystick axis, even if they are calibrated by hand
forceResetBeforeStartup=0               	; Force a reset of the whole FFB system every time we create or destroy a FFB effect
initialMoveThreshold=30                 	; Minimal amount of motion needed to detect initial movement of a joystick when calibr
initOnlyNewDevices=1                    	; Set to 0 to force all devices to reinitialize when a device change is detected
invertFFBForce=0                        	; Reverse the force feedback effects, if your wheel is spinning the wrong way
joyEnableVibrateAllXInputWithPedal=0    	; Vibrate all XInput devies when pedals vibrate, or just the one used to steer
joyEnableVibratePedal=0                 	; Enable physics based vibrations in some pedals
joyEnableVibratePedalBinary=0           	; Use a digital on/off mode when vibrating pedals, default is to continuously change v
joyEnableVibrateThrottleWithPedal=1     	; Enables throttle vibration when brake pedals vibrate
joyEnableVibrateWheelWithPedal=1        	; Enables wheel vibration when pedals vibrate
joyEnableVibrateXInputWithPedal=1       	; Enables XInput controller vibration when pedals vibrate
joyVibratePedalMaxPct=90                	; Maximum threshold of lockup when pedal vibrates at 100%.
joyVibratePedalMinPct=10                	; Minimum threshold of lockup before pedal starts to vibrate.
reinitFanatecWheelDisplay=0             	; reinitialize the fanatec wheel display when reconnecting devices this may cause issues
resetWhenFFBLost=1                      	; Attempt to reset device when force feedback interrupted by SteamVR or another application, may cause a momentary loss in steering
seperateXBox360Triggers=1               	; Set to 1 to seperate the XBox 360 joystick triggers into there own axes
steerAverageSteeringTorque=0            	; True averages 360 Hz data down to 60 Hz, false uses last sample
steeringBumpStop_Deg=15.000000          	; degrees into bump stop before max force
steeringDampingFactor=0.050000          	; Damping factor adjust down if damping becomes unstable, defautlt to 0.05
steeringDampingMaxPercent=0.000000      	; Maximum amount of damping to apply, adjust this to set damping level, values between 0.05 and 0.2 are best, overriden by damping slider
steeringDampingParkedMaxPercent=0.200000	; Maximum amount of damping to apply when parked, adjust this to reduce wheel oscilation when parked, values between 0.05 and 0.30 are best
steeringFFBSmooth=1.000000              	; Percent of current FFB force to use vs average force, 1.0 = no average 0.001 = max average
steeringForceParkedPct=0.500000         	; Reduce FFB force by percent when parked, to help reduce oscilations
trueForceEnabled=1                      	; Enable TrueForce API in Logitech TrueForce wheels
trueForceVibeEnable=1                   	; Enable vibrations in Logitech TrueForce wheels
trueForceVibeGain_dB=10.000000          	; Adjust volume of true force vibration effects
trueForceVibePhysics=0                  	; 1 - use physics to generate vibrations, 0 - use game audio with Logitech TrueForce wheels

[Graphics]
DriveUIFullScreen=0                     	; Let triple headed driving UI expand to fill full display
DriveUITransparency=1.000000            	; Adjust driving UI transparency up or down
forceCrowdVisible=0                     	; Force the crowd in the grandstand to show up on practice and qualify sessions.
forceVisibleWhenMove=1                  	; Force all movable controls to become visible when moving UI elements
hideCarNum=0                            	; Hide car numbers and other decals in test sessions, so you can paint your own versions.
KeepUIHiddenOnFocus=0                   	; If set to 1 then the UI can only be enabled with the space bar and not a mouse click
maxParticleThreads=6                    	; #workers (0 to 6)
NotifyOfDirtRequirements=0              	; Should the Session screen notify about too-low graphics settings?
particleThreadPriorityAdjust=0          	; belowNormal=-1 normal=0 aboveNormal=1
reduceFramerate_WhenFocusLost=0         	; set this to 0 to maintain full framerate when another program has the keyboard focus
serverTransmitMaxCars=63                	; Limit number of cars transmitted to client (values from 10 to 64)
SessionUIFullScreen=0                   	; Let triple headed session UI expand to fill full display
SessionUITransparency=1.000000          	; Adjust session UI transparency up or down

[Graphics DX11]
border=0                                	; window border?
browserForceWindowedMode=1              	; force the browser windowed (if sim sessions are full-screen)
browserIsMaximized=0                    	; browser Window is maximized in windowed mode
browserScale=-1.000000                  	; browser UI Scale value (0.5 to 2.0)
browserWindowedHeight=864               	; Browser windowed mode height
browserWindowedWidth=1536               	; Browser windowed mode width
browserWindowedXPos=192                 	; Browser Window top left corner in windowed mode
browserWindowedYPos=108                 	; Browser Window top left corner in windowed mode
deviceIdx=0                             	; which adapter
displayRotateMode=1                     	; 0-auto, 1-landscale, 2-landscape inv, 3-portrait, 4-portrait inv
EnableHiddenLoadMode=1                  	; Allows the BetaUI to display the sim's loading screens
fullScreen=0                            	; fullscreen?
fullScreenDepth=32                      	; Color depth
fullScreenHeight=768                    	; full screen Window's height
fullScreenWidth=1024                    	; full screen Window's width
HDRFormat=0                             	; 0=8 bit color (SDR)  1=HDR10 or HDR16F (depends on fullScreenDepth 32/64 bit)
ModeScaling=0                           	; 0=unspecified 1=centered 2=stretched
pixelRatio=1.000000                     	; Full screen mode - Adjust for displays with non-square pixels
pixelRatioWindowed=1.000000             	; Windowed mode - Adjust for displays with non-square pixels
RefreshRate=60.004002                   	; Refresh Rate
uiSafeMode=0                            	; iRacingUI: Disable advanced graphics?   0=auto   1=yes   2=no
UseCoherentUI=0                         	; Use Coherent UI?
windowedAlignment=0                     	; windowed mode alignment: 0 - none, 1 - center, 2 - top left
windowedHeight=1080                     	; windowed mode height
windowedMaximized=1                     	; Window is maximized in windowed mode
windowedWidth=1920                      	; windowed mode width
windowedXPos=-7                         	; Window top left corner in windowed mode
windowedYPos=-7                         	; Window top left corner in windowed mode

[Locale]
dateFormat=0                            	; Ordering of month, day, year
systemOfMeasurement=1                   	; System of measurement used

[Main Screen]
blackBox=-1                             	; Which black box to display

[Misc]
excludeIPv6OnFarms=                     	; Comma-separated list of 0 or more of farms to not race using IPv6: (bosrace,sydrace,amstrace)
garageAutoApply=1                       	; automatically hit the apply button after five seconds of inactivity.
irsdkAutoLogDisk=0                      	; Automatically log disk telemetry when you enter your car, this can fill up your disk!
irsdkEnableDisk=1                       	; enable disk based telemetry
irsdkEnableMem=1                        	; enable memory based telemetry
irsdkLimitFileSize=0                    	; Keep .ibt files under 100 mb in size
irsdkLog360Hz=0                         	; Log some telemetry at 360 Hz rather than at 60 Hz
irsdkLogSetup=1                         	; Log the current setup to telemetry
showIncidentMessagesWhileDriving=1      	; Show Incident messages while driving
showJoinLeave=0                         	; Show player join/leave messages
showSysMessagesWhileDriving=0           	; Show system messages while driving
showUserMessagesWhileDriving=0          	; Show user chat messages while driving

[Overlay]
EnableTicker=0                          	; set to 1 to turn on ticker when session UI is disabled

[Pit Service]
autoResetFastRepair=1                   	; Automatically request fast repair service once your vehicle exits pit road
autoResetPitBox=1                       	; Automatically request full pit service once your vehicle exits pit road

[Replay]
askToSaveOnQuit=0                       	; Ask to save the replay before quitting via the [Quit] button??
CPUUsageAtWhichToReducePlaybackRate=0   	; Realtime thread CPU usage at/above which to reduce play speed (0 disables)
CPUVsPlaySpeedCheckPeriod=2             	; Number of seconds between checks to see if play speed is chewing up too much CPU
DefaultReplayChatReviewState=0          	; Upon entering the Replay/Session screen, default 'replay voice chat review' state (0=off, 1=on).
leavePlaybackAloneAtSessionEnd=0        	; Leave playback in its current state between sessions?
maxFramesToSearchPerUpdate=2048         	; Maximum # of frames to search per update
noRpyCtrlsOnNumpad=0                    	; Remove all default replay controls mapped to number pad
pauseReplayOnExit=1                     	; Pause replay when exiting your car.
playSecondsFromReplayEndOnCarExitNonTeam=20	; Number of seconds to back up from the end when exiting the car in a non-team session (0=min,60=max)
playSecondsFromReplayEndOnCarExitTeamEvt=20	; Number of seconds to back up from the end when exiting the car in a team session (0=min,60=max)
repeatedSearchDelay=0                   	; Min milliseconds betweeen successful long-search completions
replayPatchRemoteCars=1                 	; update remote car positions in replay based on server data
spoolingEnabled=0                       	; enable replay spooling?
spoolOnlyIfDiskFreeMB=1024              	; 0=don't check, otherwise must have this many MB free disk or spooling won't enable
spoolRecordingToDiry=                   	; If spooling recording, write tmp file into this directory
spoolTapeSizePct=25                     	; % of allowed memory to use for the spool buffer (0=min,100=max)
spoolTmpFilesNamed=0                    	; use different file names for each spooled .tmp file?

[SetupAutoLoad]
audi90gto=0
audir18=1
audirs3lms=0
bmwm4gt3=1
bmwm4gt4=0
bmwm8gte=0
bmwz4gt3=1
c6r=0
c8rvettegte=1
cadillacctsvr=0
dallara=1
dallaradw12=1
dallaraf3=1
dirtstreetstock=1
ferrari488gt3=0
fordfiestarswrc=0
fordgt=0
fordgt_gt3=0
fordv8sc=1
formulamazda=0
formularenault35=1
formulavee=1
fr500s=0
hpdarx01c=0
jettatdi=0
kiaoptima=0
lamborghinievogt3=0
legends_dirtford34c=1
mclaren570sgt4=0
mclarenmp4=0
mx5_cup=0
mx5_mx52016=0
porsche718gt4=0
porsche911cup=0
protrucks_pro2lite=0
protrucks_pro2truck=1
protrucks_pro4truck=0
radical_sr8=0
rileydp=0
rufrt12r_rwd=0
rufrt12r_track=0
rufrt12r_track_cspec=0
solstice=0
specracer=0
subaruwrxsti=0
trucks_silverado=1
v8supercars_fordmustanggt=0
vwbeetlegrc=0
vwbeetlegrc_lite=1
williamsfw31=0

[SPCC]
carLowHiAtStart=0                       	; If true enable car low_high calls as soon as green flag is out
carLowHiPadding=0.250000                	; How much clearance, front and back in meters, to give a car before reporting it as clear
enabled=0                               	; Is the spotter enabled at all?
muteSpotterIfLive=1                     	; Mute your spotter if you have a live spotter already spotting for you
reduceVerbosityIfLive=1                 	; Reduce the spotters chattiness if you have a live spotter already spotting for you
reportLapsEnabled=0                     	; Enable spotter calls out lap times
reportLapsMinute=1                      	; Call out the minute when calling the time
reportLapsMode_n=0                      	; Spotter calls out lap times, 0 - time, 1 - avg speed
reportLapsPrecision=3                   	; How much precision to display lap times with
text=0                                  	; Does the spotter display text messages?
topic_mask=0
verbosity=2                             	; How chatty is the spotter?
voice=1                                 	; Does the spotter talk to you?
voicePack=chrisWheeler                  	; Voice pack for spotter, leave blank for default spotter

[spectator]
defaultShotMode=3                       	; default target to focus on when spectating
ShowSpotterUIForSpectators=0            	; Present the Start/Stop spotting functionality if you are a Spectator in the session.

[SplitsDeltas]
comparisonLapFileName=                  	; User specified split delta file used for comparison
deltaBarDisplayDeltabar=1               	; Show the delta bar when displaying split time or ghost car
deltaBarDisplayLaps=2                   	; Reference lap to compare against while driving, 0 disables the reference lap.
deltaBarDisplayLapsTA=2                 	; Reference lap to compare against while driving in Time Attack, 0 disables the reference lap.
deltaBarDisplayRefCar=0                 	; If 1 display a reference car on track that you can race against. This may not be enabled in all sessions.
deltaBarRangeOval=0.500000              	; delta bar range as +/- N seconds when at an oval
deltaBarRangeRoad=2.000000              	; delta bar range as +/- N seconds when at a road course
disableAtRaceStart=1                    	; If 1 disable the split time at start of race, you can manually enable it again later.
fadeGhostCarWhenClose=1                 	; If 1 then increase the ghost car transparency as you drive near it.
ghostCarOffsetSec=0.000000              	; How many seconds to offset the ghost car by.
ghostCarTransp=0.350000                 	; Set level of transparency for ghost car (reference lap car).

[System Meters]
2=text)
meterTypeAudio=0                        	; If FPS is displayed, include the Audio Performance meters (0=hidden, 1=graphics, 2=text)
meterTypeGraphics=2                     	; If FPS is displayed, include the Graphics Performance meters (0=hidden, 1=graphics, 2=text)
meterTypeNetwork=1                      	; If FPS is displayed, include the Network meters (0=hidden, 1=graphics, 2=text)
meterTypeSteering=1                     	; If FPS is displayed, include the Force Feedback meter (0=hidden, 1=graphics, 2=text)
meterTypeSystem=2                       	; If FPS is displayed, include the System Performance meters (0=hidden, 1=graphics, 2=text)
showFPSAndOtherMeters=1                 	; Display the FPS indicator, along with whichever of network/system/graphics/force-feedback meters are enabled?

[TiltDrive]
tiltInvertX=0                           	; Invert the tilt steering axis
tiltInvertY=0                           	; Invert the tilt gas/brake axis
tiltMaxAngleX=120.000000                	; changes tilt sensitivity for the steering axis
tiltMaxAngleY=30.000000                 	; changes tilt sensitivity for the gas/brake axis
tiltSensorEnable=1                      	; Set to false to stop detection of tilt sensors
useOrientationSensor=1                  	; Choose between the orientation sensor or the accelerometer

[TouchDrive]
enableMouseWhileDriving=1               	; Enable the mouse controls in the driving screen
touchCenterOnFirstTouchX=0              	; Center x of control set by first touch
touchCenterOnFirstTouchY=1              	; Center y of control set by first touch
touchComboHeight=0.150000               	; Height, as a percent of screen width, of the center combination touch drive input
touchComboUseSingleCursor=1             	; use a single cursor on the x/y combo control
touchComboWidth=0.400000                	; Width, as a percent of screen width, of the center combination touch drive input
touchFalloff=0.016000                   	; How fast the touch control will return to its neutral setting once released
touchLockMouseOnClick=1                 	; click once to activate mouse driving control, click again to release it
touchSideEdgeOffset=0.020000            	; How close to the edge of the display are the left/right touch driving input, when using a horizontal orientation
touchSideGasIsVertical=1                	; Orient the (right) gas/brake input zone vertically or horizontally
touchSideHeight=0.150000                	; Height, as a percent of screen width, of the left/right touch drive inputs, when using vert orientation
touchSideHideOnMouse=1                  	; hide the side controls when touch not active
touchSideSteeringIsVertical=0           	; Orient the (left) steering input zone vertically or horizontally
touchSideWidth=0.200000                 	; Width, as a percent of screen width, of the left/right touch drive inputs, when using a horizontal orientation
touchUseMouseRelativeMode=1             	; If true, then use a relative mouse mode, otherwise use absolute

[UIOffsetPos]
Fulldrv_Flags_X=-10
Fulldrv_Flags_Y=2
Fulldrv_VirtualMirror_X=-12
Fulldrv_VirtualMirror_Y=33
IDC_FULLDRV_DELTABAR_X=0
IDC_FULLDRV_DELTABAR_Y=0
IDC_FULLDRV_INFO_X=-26
IDC_FULLDRV_INFO_Y=8
IDC_FULLDRV_LASTSEC_X=-18
IDC_FULLDRV_LASTSEC_Y=-3
IDC_FULLDRV_PACEINFO_X=-3
IDC_FULLDRV_PACEINFO_Y=-31
IDC_FULLDRV_PITINFO_X=0
IDC_FULLDRV_PITINFO_Y=-12

[Video]
screenshotFileFormat=0                  	; Screenshot file format, 0 = png, 1 = jpg, 2 = bmp
vidCaptureEnable=0                      	; Set to 0 to disable loading of video capture module
videoCaptureMic=0                       	; Set to 1 to capture audio from your microphone
videoFileFormat=1                       	; Video encoder container, 0 = mp4, 1 = wmv, 2 = avi2, 3 = avi
videoFileFrmt=0                         	; Video encoder container, 0 = mp4, 1 = wmv, 2 = avi2, 3 = avi
videoFramerate=1                        	; Video framerate, 0 = 60 fps, 1 = 30 fps
videoImgSize=2                          	; Video max dimensions, 0 = auto, 1=1920x1080, 2=1280x720, 3=854x480

[View]
cockpitLookAngle=65.000000              	; Angle in degrees to rotate head when looking left/right
cockpitLookDeadZone=0.050000            	; 0-1 value for deadzone. 0 is no deadzone.
cockpitLookDownAngle=20.000000          	; Angle in degrees to tilt head when looking down
cockpitLookInstant=1                    	; does digital look left/right/up/down switch instantly, or transition smoothly?
cockpitLookSmoothingTime=0.055556       	; Time value (secs) used in joystick smoothing
cockpitLookUpAngle=15.000000            	; Angle in degrees to tilt head when looking up
DriverHeadHorizon=0.900000              	; Percent to allow the drivers head to stay level with the horizon when the car tilts.
DriverHeadNoPitch=0.900000              	; Percent to allow the drivers head to stay level with the horizon when the car pitches.
DriverHeadWobble=0.000000               	; Percent to allow the drivers head to wobble when going over bumps.
driverHeightAdj=0.000000                	; Range -0.050m to 0.050m  (approx. +/- 2 in.)
DriverRotateHead=0.000000               	; Percent to rotate drivers head with slip angle. 0 to 1 with 1 being 100%
drivingCamFOV=110.000000                	; driving camera field of view
DrivingVanishY=0.120000                 	; Shift the driving view up/down to make it easier to see the dash.
virtualMirrorFOV=45.000000              	; virtual mirror field of view

[XXX Dev Use Only]
AutoCPUMeter=1                          	; Force the system performance meters on if it seems like Skew is being induced by an overtaxed BG?
dbgTextBG=                              	; r,g,b[,a]
dbgTextFG=                              	; r,g,b[,a]
ForceCrashForFPUExceptionBG=0           	; 1=Kill sim w/crash log (realtime)
ForceCrashForFPUExceptionFG=0           	; 1=Kill sim w/crash log (graphics)
MaskFPUExceptionsBG=0                   	; 1=mask floating point errors (realtime)
MaskFPUExceptionsFG=0                   	; 1=mask floating point errors (graphics)
maxAllowedHangTimeSecondsBG=0           	; 0=disable  (realtime)
maxAllowedHangTimeSecondsFG=0           	; 0=disable  (renderering)
RunTireTestsOnStartup=0                 	; 1=run the full set of tire test sweeps on startup
xHeight=1600                            	;  
xTilesAcross=1                          	; mosaic
xWidth=2048                             	; must be multiple of 4*xTilesAcross!





## rendererDX11



[AutoCfg]
AutoCfgCompleted=1                              	; 0=need to run 3D autocfg at startup
Version=1                                       	; Version of this file

[Graphics Options]
LowQualityTrees=1                               	; 0=off, 1=on
EnableWRS=0                                     	; 0=off, 1=on
AutoExposure=1                                  	; 0=off, 1=on  (only functions when HDR is also enabled)
SkyRefreshRate=0                                	; 0=low update rate, 1=med update rate, 2=high update rate
BrightnessAdj=0                                 	; Adjusts scene intensity: -6 to +6 
GammaAdj=0                                      	; Adjusts gamma encoding: -6 to +6 
AllowTSOSelfShadows=0                           	; 0=off, 1=more self-shadowing objects when shadow mapping
DNSMFilter=0                                    	; 0= none 1= Fetch4 2= PCF4 3= PCF4P 4= PCF8P 5= PCF16P
DNSMShadowFadeTime=25                           	; 0 to # = time to fade in night shadows in 100ths of a sec (5 default)
DNSMNumLights=3                                 	; 0 to 128 = Max number of shadow mapped lights at night
DNSMHeadlightsCastShadows=1                     	; 0=off 1=car headlights cast shadows
DNSMWallsCastShadows=1                          	; 0= off 1=track walls cast shadows
DNSMTSOsCastShadows=0                           	; 0= off 1=track objects cast shadows
DNSMDownsampleFirst=0                           	; 0=per-AA-sample shadows 1=per-pixel shadow
DNSMEnable=0                                    	; 0=off 1=dynamic night shadow maps
TwoPassTrees=0                                  	; 0=off, 1=render trees with higher quality in two passes
NumFixedCubemaps=0                              	; number of fixed cubemaps to render per frame(100 = 1/frame)
NumDynamicCubemaps=0                            	; number of dynamic cubemaps to render per frame(100 = 1/frame)
ReplayRenderModes=0                             	; 0=off, 1=Replay Render Modes enabled
Distortion=0                                    	; 0=off, 1=Distortion enabled
SharpeningClamp=9                               	; sharpening clamp (0=min, 10=default, 100=max)
SharpeningAmount=125                            	; sharpening strength (10=min, 125=default, 300=max)
FXAAQualityEdgeThreshold=125                    	; 333=too little(fast),250=lowqual,166=default,125=highqual,63=overkill(slow)
FXAAQualitySubPix=50                            	; aliasing amt (100=soft,75=default,50=sharp,25=low,0=0ff)
FXAA=0                                          	; 0=off, 1=FXAA enabled
Sharpening=1                                    	; 0=off, 1=sharpening enabled
MotionBlurBroadcastCams=1                       	; 0=disabled, 1=enabled
MotionBlurDrivingCams=1                         	; 0=disabled, 1=enabled
MotionBlurStrength=0                            	; motion blur strength: 0=off, 1=low, 2=med, 3=high
HeatHaze=0                                      	; 0=off, 1=heat haze enabled
DepthOfField=0                                  	; 0=off, 1=depth of field blurs enabled
ShadowMapType=2                                 	; map onto: 0=off, 1=track, 2=track\cars, 3=track\cars\tso
DynamicShadowFilters=7                          	; 1=cockpit only, 7=all)
DynamicShadowMaps=0                             	; 0=off 1=dynamic shadow maps for cars, etc. (Day only!)
ShadowDetail=0                                  	; 0=fewer shadows, 1=maximum shadows
VirtualMirrors=1                                	; 0=off, 1=virtual mirrors enabled
MaxCockpitMirrors=0                             	; Maximum number of cockpit mirrors to enable (0 to 4)
MirrorDetail=1                                  	; 0=low detail, 1=high detail in mirrors
ParticlesSoft=0                                 	; soft particles: 0=off, 1=on
ParticlesFullRes=1                              	; full resolution particles: 0=off, 1=on
ParticleDetail=2                                	; particle detail: 0=low, 1=med, 2=high
WeekendDetail=1                                 	; event detail: 0=low, 1=med, 2=high
ObjectDetail=2                                  	; object population 0=low, 1=med, 2=high
GrandstandDetail=0                              	; 0=low, 1=med, 2=high
CrowdDetail=0                                   	; 0=off, 1=low, 2=med, 3=high
PitObjectDetail=2                               	; 0=off, 1=low, 2=med, 3=high
CarDetail=2                                     	; 0=low, 1=med, 2=high
Trilinear=1                                     	; 0=off, 1=improved texture quality
LODPctDynoMirrorsMax=100                        	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMirrorsMin=100                        	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctDynoMax=100                               	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMin=100                               	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMirrorsMax=100                            	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMirrorsMin=100                            	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMax=100                                   	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMin=100                                   	; below 100% decreases FPS and increases LOD (25 to 500)
LODMinFPSTarget=81                              	; Reduce LODs (see LODPct* settings) when FPS is below target. 
MaxPitObjsToDrawInMirrors=8                     	; 0 to 192: Max number of pit objs to render per mirror camera
MaxPitObjsToDraw=20                             	; 0 to 192: Max number of pit objs to render per camera
MaxCarsToDrawInMirrors=12                       	; 4 to 64: Max number of cars to render per mirror camera
MaxCarsToDraw=30                                	; 10 to 64: Max number of cars to render per camera
MaxAniso=16                                     	; 1=off, or 2, 4, 8, 16 - improved edge-on textures
FarTerrain=1                                    	; 0=no far terrain, 1=far terrain in separate pass
DriverHands=1                                   	; Show driver hands? 0=no, 1=yes
SteeringWheel=1                                 	; Show steering wheel? 0=no, 1=yes, 2=fixed, 3=show only if has display
EnableSPS=1                                     	; 0=off 1=Use Single Pass Stereo VR (nvidia Pascal/Turing)
EnableTireMarks=1                               	; 0=Disable Tire marks 1=Enable tire marks
DynamicCubemapType=0                            	; 0=RGB8, 1=RGBE, 2=RGB16
EnableHDR=0                                     	; 0=LDR rendering, 1=HDR rendering
EnableSwayTrees=1                               	; 0=normal trees, 1=trees sway with wind
TrackDisplacementEnable=1                       	; 0=render without displacement, 1=render using track displacement shaders
DNSMMaxLightsPerPass=3                          	; 0- 6 = Shadowing lights per-fullscreen pass
DynamicShadowRes=1                              	; (For 3 maps! So, x3) 0 = 512x512 1 = 1024x1024 2 = 2048x2048 3 = 4096x4096
DynamicTireRendering=1                          	; 0=render without dynamic tires, 1=render with dynamic tires
DynamicTrackTextureUpdateRate=2                 	; 0=min, 1=low, 2=med, 3=high frequency of dynamic track texture updates
DynamicTrackDataRendering=1                     	; 0=render without dynamic track data, 1=render with Dynamic Track Data
ShaderQuality=3                                 	; 0=low, 1=med, 2=high, 3=max
HeadlightLevel=0                                	; 0=low quality, 1=medium, 2=high quality. *** -1=disabled ***
ParallelSorting=1                               	; 0=disabled 1=multithreaded scene sort
MonochromeHeadlights=0                          	; 0=color headlights 1=all white (less blotches/banding)
HeadlightsInMirrors=0                           	; 0=off 1= headlights illuminate track surface in mirrors
LoadTexturesWhenDriving=1                       	; 0=only load when out of car
NumMultiGPUs=1                                  	; Number of GPUs in Crossfire/SLI (1=off to 4). Set low as works.
CompressTexturesSuits=1                         	; 0=uncompressed   1=block compress (recommended)
CompressTexturesHelmets=1                       	; 0=uncompressed   1=block compress (recommended)
CompressTexturesCars=1                          	; 0=uncompressed (warning! no!!)   1=block compress (highly recommended)
CompressedVertices=1                            	; 0=off  1=Use compressed vertices
ReduceCockpitFlicker=1                          	; 0=off  1=enabled
CarPaint2048x2048=1                             	; 0=1024x1024 car textures res,  1=2048x2048 car texture res (max)
CacheSwap3HighResCars=0                         	; 0=shrink to fit  1=cache swap higher res for nearest cars
WorldNearPlaneDistance=10                       	; In 1/10 meters, min=1(0.1m) max=30(3m), helps z-fighting but may clip track.
VisibilityFrameDelay=0                          	; Number of frames to wait before re-testing object visibility. 0 = no delay
AAQuality=0                                     	; 0=low - 0=max (GPU & AASamples specific)
AASamples=4                                     	; 1=off, 2, or 4 - num samples
MipLODBias=0                                    	; % bias texture lookup 100 is a mip level, positive is blurry, negative sharp
OcclusionCull=1                                 	; 0=disable occlusion culling, 1=enabled (usually best)
LimitFrameRate=0                                	; 0=no limit, 1=use DesiredFPSLimit
DesiredFPSLimit=81                              	; Enabled when LimitFrameRate=1 and on ext. power
MaxPreRenderedFrames=1                          	; 1=normal  0=disabled/multi-gpu
VerticalSync=0                                  	; 0=allow tearing, 1=lock FPS to refresh rate
TwoBackBuffers=0                                	; 0=1 back buffer, 1=try to create 2 back buffers
MaxWorkingSetMB_64Bit=8192                      	; (64-bit) 1024 to 8192 MB - Lower to reduce page faults!
VidMemMB=6000                                   	; Maximum GPU video memory to consume (MB)
UIScalePct=100                                  	; User Interface Size

[MonitorSetup]
MonitorType=0                                   	; 0=flat or 1=curved
RadiusOfCurvature=1000                          	; (mm) Radius of screen's curvature (ignored if type is flat)
ViewingDist=0                                   	; (mm) Distance from eyes to center of monitor
BezelProtectionPct=7                            	; 0-10: % of screen width to keep UI elements away from bezels
Min3ViewZoomDistortion=1                        	; 0=off 1=when cameras zoom in alot, relax screen angles
NumMonitors=1                                   	; 1 or 3
EnableSMPSurround=0                             	; 0=off 1=Enable Simultaneous Multi-Projection via GPU
RenderViewPerMonitor=0                          	; 0=off 1=separate view on each monitor (less distortion)
MonitorWidth=609                                	; (mm) total width of each monitor (screen + bezels)
ScreenWidth=558                                 	; (mm) usable width of each screen (no bezels)
ScreenAngles=27                                 	; (deg) side monitor angle, 10=slight, 65=max

[Debug]
Renderer=?                                      	; Driver DLL - Don't Edit This!
Version=0                                       	; Driver Version - Don't Edit This!
Vendor=?                                        	; Driver Vender - Don't Edit This!

[Laser Scan]
PointSizeMM=80                                  	; desired physical point size width (mm): 1 to 120
PointSizeMin=1                                  	; min point size in screen pixels (1 to 256)
PointSizeMax=1                                  	; max point size in screen pixels (1 to 256)
MaxLaserScanVidMem=192                          	; Max scan density to load into vidmem 128-768 (MB)

[Oculus Rift]
MirrorViewVerticalShiftPct=0                    	; -30 to +30 percent - shifts the mirror image up/down (if clipped)
RiftEnabled=1                                   	; Enable Oculus Rift Support
PixelsPerDisplayPixel=100                       	; (50% to 300%): 125%=1.25,  over 100% may hurt performance!
TwoStageAA=1                                    	; Repeat AA after the UI draws (note: consumes more vid mem)
FullyWaitForSync=1                              	; Improves timing/lag below refresh rate, but costs a little all of the time
AutoSelect=0                                    	; Use Rift, if detected, without prompting
AutoCenter=0                                    	; Re-center the HMD pose when health/safety warning disappears
PrevVirtualMirrorWidth=1152                     	; System use only -> do not edit...
PrevVirtualMirrorHeight=220                     	; System use only -> do not edit...

[OpenVR]
FixGetProjectionRawBug=0                        	; Might help fix vertical eye alignment issues
OpenVREnabled=1                                 	; Enable OpenVR Support
TwoStageAA=1                                    	; Repeat AA after the UI draws (note: consumes more vid mem)
AlignmentFix=2                                  	; 0=off, 1=simple (SPS), 2=simple (always), 3=advanced (SPS)
MirrorViewVerticalShiftPct=0                    	; -30 to +30 percent - shifts the mirror image up/down (if clipped)
PredictionMode=1                                	; 0=off, 1=dynamic, 2=fixed
FullyWaitForSync=1                              	; Improves timing/lag below refresh rate, but costs a little all of the time
AutoSelect=0                                    	; Use OpenVR without prompting (note: Oculus has priority if enabled)
AutoCenter=0                                    	; Re-center the HMD pose when health/safety warning disappears

[Replay Graphics]
AutoExposure=1                                  	; 0=off, 1=on  (only functions when HDR is also enabled)
SkyRefreshRate=2                                	; 0=low update rate, 1=med update rate, 2=high update rate
AllowTSOSelfShadows=1                           	; 0=off, 1=more self-shadowing objects when shadow mapping
DNSMFilter=2                                    	; 0= none 1= Fetch4 2= PCF4 3= PCF4P 4= PCF8P 5= PCF16P
DNSMShadowFadeTime=25                           	; 0 to # = time to fade in night shadows in 100ths of a sec (5 default)
DNSMNumLights=3                                 	; 0 to 128 = Max number of shadow mapped lights at night
DNSMHeadlightsCastShadows=1                     	; 0=off 1=car headlights cast shadows
DNSMWallsCastShadows=1                          	; 0= off 1=track walls cast shadows
DNSMTSOsCastShadows=0                           	; 0= off 1=track objects cast shadows
DNSMDownsampleFirst=0                           	; 0=per-AA-sample shadows 1=per-pixel shadow
DNSMEnable=1                                    	; 0=off 1=dynamic night shadow maps
TwoPassTrees=1                                  	; 0=off, 1=render trees with higher quality in two passes
NumFixedCubemaps=0                              	; number of fixed cubemaps to render per frame(100 = 1/frame)
NumDynamicCubemaps=0                            	; number of dynamic cubemaps to render per frame(100 = 1/frame)
ReplayRenderModes=1                             	; 0=off, 1=Replay Render Modes enabled
Distortion=1                                    	; 0=off, 1=Distortion enabled
SharpeningClamp=9                               	; sharpening clamp (0=min, 10=default, 100=max)
SharpeningAmount=125                            	; sharpening strength (10=min, 125=default, 300=max)
FXAAQualityEdgeThreshold=166                    	; 333=too little(fast),250=lowqual,166=default,125=highqual,63=overkill(slow)
FXAAQualitySubPix=75                            	; aliasing amt (100=soft,75=default,50=sharp,25=low,0=0ff)
FXAA=1                                          	; 0=off, 1=FXAA enabled
Sharpening=1                                    	; 0=off, 1=sharpening enabled
MotionBlurBroadcastCams=0                       	; 0=disabled, 1=enabled
MotionBlurDrivingCams=0                         	; 0=disabled, 1=enabled
MotionBlurStrength=0                            	; motion blur strength: 0=off, 1=low, 2=med, 3=high
HeatHaze=1                                      	; 0=off, 1=heat haze enabled
DepthOfField=1                                  	; 0=off, 1=depth of field blurs enabled
ShadowMapType=3                                 	; map onto: 0=off, 1=track, 2=track\cars, 3=track\cars\tso
DynamicShadowFilters=7                          	; 1=cockpit only, 7=all)
DynamicShadowMaps=1                             	; 0=off 1=dynamic shadow maps for cars, etc. (Day only!)
ShadowDetail=0                                  	; 0=fewer shadows, 1=maximum shadows
VirtualMirrors=1                                	; 0=off, 1=virtual mirrors enabled
MaxCockpitMirrors=4                             	; Maximum number of cockpit mirrors to enable (0 to 4)
MirrorDetail=1                                  	; 0=low detail, 1=high detail in mirrors
ParticlesSoft=1                                 	; soft particles: 0=off, 1=on
ParticlesFullRes=1                              	; full resolution particles: 0=off, 1=on
ParticleDetail=2                                	; particle detail: 0=low, 1=med, 2=high
WeekendDetail=2                                 	; event detail: 0=low, 1=med, 2=high
ObjectDetail=2                                  	; object population 0=low, 1=med, 2=high
GrandstandDetail=2                              	; 0=low, 1=med, 2=high
CrowdDetail=3                                   	; 0=off, 1=low, 2=med, 3=high
PitObjectDetail=3                               	; 0=off, 1=low, 2=med, 3=high
CarDetail=2                                     	; 0=low, 1=med, 2=high
Trilinear=1                                     	; 0=off, 1=improved texture quality
LODPctDynoMirrorsMax=500                        	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMirrorsMin=100                        	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctDynoMax=400                               	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMin=100                               	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMirrorsMax=500                            	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMirrorsMin=100                            	; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMax=400                                   	; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMin=100                                   	; below 100% decreases FPS and increases LOD (25 to 500)
LODMinFPSTarget=60                              	; Reduce LODs (see LODPct* settings) when FPS is below target. 
MaxPitObjsToDrawInMirrors=4                     	; 0 to 192: Max number of pit objs to render per mirror camera
MaxPitObjsToDraw=30                             	; 0 to 192: Max number of pit objs to render per camera
MaxCarsToDrawInMirrors=8                        	; 4 to 64: Max number of cars to render per mirror camera
MaxCarsToDraw=30                                	; 10 to 64: Max number of cars to render per camera
MaxAniso=8                                      	; 1=off, or 2, 4, 8, 16 - improved edge-on textures
FarTerrain=1                                    	; 0=no far terrain, 1=far terrain in separate pass
DriverHands=1                                   	; Show driver hands? 0=no, 1=yes
SteeringWheel=1                                 	; Show steering wheel? 0=no, 1=yes, 2=fixed, 3=show only if has display







