AncientOS 3.8 | Primeval | Koshiki | 25 July 2020

 Source CL :


====================
     07-25-2020
====================


   * frameworks/base
0e2519b [3/4] Port face unlock feature
ead91d7 Home wake up: Enable home button wake

   * hardware/qcom-caf/msm8998/audio
a6e7400 Merge tag 'LA.UM.8.4.r1-05800-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio

   * manifest
800d006 manifest: tracker own fork power hals
ec60264 manifest: tracker own fork Bluetooth

   * packages/apps/Settings
edd92dd Settings: Merge extra strings in one file
78eccf3 [4/4] Port face unlock feature

   * vendor/pixelstyle
d435b9d pixelstyle: new wall

   * vendor/qcom/opensource/power
301fcfb power: Ignore interaction boost sequence in a short period
5d096b6 power: Add the custom set_feature lib as whole static library
a383d98 Add Powerhal support for bengal
f8a79f3 Power: Add Camera Powerhal settings for Bitra
be53c3c qvr powerhints

====================
     07-24-2020
====================


   * frameworks/base
eb24e82 Bluetooth: Add APTX-Adaptive and APTX-TWS+ entries for summaries too
8135d7b BT: Add switch to select SBC HD by default [1/3]
531b204 Bluetooth: Avoid reentrant lock in getService method
fe45953 Add missing strings for SBC Dual Channel
b8f8d50 Add CHANNEL_MODE_DUAL_CHANNEL constant
0bde846 Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
5ec5130 Allow SBC as HD audio codec in Bluetooth device configuration
3f98701 BT: A2DP codec priority [1/3]

   * packages/apps/AncientSettings
65db18c AncientSettings: Add Ancient logo FOD icons [2/2]
2ee3178 AncientSettings: Add Realme white FOD pressed state icon [2/2]
e2397f9 AncientSettings: Add riva maintainer
22b51ab AncientSettings: Dropped maintainer
4675d1b AncientSettings: disable old brightness

   * packages/apps/Bluetooth
671119a Add switch to select SBC HD by default [2/3]
85b17e4 Disable Dual channel for SBC by default
6ee7dc9 A2DP codec priority [2/3]
5858d86 Assume optional codecs are supported if were supported previously
dbe747f SBC Dual Channel (SBC HD Audio) support
4ec227a Check Null-safeness when switching optional-codecs state

   * packages/apps/Settings
c6544bf Settings: BT: Add switch to select SBC HD by default [3/3]
5d0f95f Settings: Add Dual Channel into Bluetooth Audio Channel Mode developer options
18c74b0 Settings: BT: A2DP codec priority [3/3]

   * system/bt
48fd34e Allow using alternative (higher) SBC HD bitrates with a property
7c29f1b Explicit SBC Dual Channel (SBC HD) support
43a53d2 Increase maximum Bluetooth SBC codec bitrate for SBC HD
e618681 bt_target.h: Update MTU size for Amiibo support
15261da NULL pointer handling in btif_a2dp_get_codec_configuration
d79007a Increase the attempts to open the a2dp socket

   * vendor/pixelstyle
3a28f04 pixelstyle: statusbar height
eacfcdc pixelstyle: nuked few Settings overlay
a2242fb pixelstyle: update few overlay
578c3e5 pixelstyle: remove Oxygen tiles
a708cd2 pixelstyle: Add AncientStyles

   * vendor/qcom/opensource/commonsys/bluetooth_ext
adfb892 Fix compilation with SBC Dual Channel suport

   * vendor/qcom/opensource/commonsys/packages/apps/Bluetooth
7f5dd8c Add switch to select SBC HD by default [2/3]
b4f0649 Disable Dual channel for SBC by default
349d4f6 A2DP codec priority [2/3]
4e10693 Assume optional codecs are supported if were supported previously
1048c5a SBC Dual Channel (SBC HD Audio) support
07425d1 Check Null-safeness when switching optional-codecs state

   * vendor/qcom/opensource/commonsys/system/bt
65b6ca3 Allow using alternative (higher) SBC HD bitrates with a property
918da54 Explicit SBC Dual Channel (SBC HD) support
be355e6 Increase maximum Bluetooth SBC codec bitrate for SBC HD

====================
     07-23-2020
====================


   * frameworks/base
0c284ce SystemUI: Add Ancient logo FOD icons [1/2]
3c64bc7 SystemUI: Add Realme white FOD pressed state icon [1/2]
4311358 SystemUI: adapt to brightness Quick QS
adddd92 SystemUI: FOD Animations: convert to webp icons
9ee5f7c8 Implement quick QS brightness slider [1/2]
f811102 Backup brightness

   * packages/apps/AncientSettings
3457244 AncientSettings: Implement quick QS brightness slider [2/2]
ce8f93a AncientSettings: Add ColorOS7 recognizing FP animations [2/2]
2405eb3 AncientSettings: Add new FOD pressed state icons [2/2]

   * packages/apps/Settings
cd6cc51 Settings: VolumePanel: fix showing notification volume slider when unlinked
fff8d3e Settings: Add switch for linked ring and media notification volumes

   * vendor/ancient
8936727 vendor: 3.9

====================
     07-22-2020
====================


   * frameworks/base
20dfa81 frameworks: Add unlinked ringtone and notification volumes
57c7c7c SystemUI: Add ColorOS7 recognizing FP animations [1/2]
57b940b SystemUI: Add new FOD pressed state icons [1/2]
f83ecf2 Settings: Add FOD icon picker settings values to backup
f417405 FODCircleView: FOD pressed state [1/2]
225a1e2 Settings dashboard icons: Fix theme for external icons on 10 [1/2]
7c39e3b Theme settings dashboard icons [1/3]
cece0a2 Selectable statusbar height [1/2]
8ecb120 Revert "fwb: core: enable LiveDisplay by defaults"

   * packages/apps/AncientSettings
d3b213c AncientSettings: FOD pressed state [2/2]
00171f1 AncientSettings: Add OnePlus dashboard icons [2/2]
37673d4 AncientSettings: Dashboard Icons: get Random Color dashboard icons [2/2]
2366432 AncientSettings: Theme settings dashboard icons [3/3]
fcab56b AncientSettings: Selectable statusbar height [2/2]
0ac9d81 AncientSettings: move dual row to interfaces

   * packages/apps/Settings
4abc86a Settings: Add OnePlus dashboard icons [1/2]
5f7a1b0 Settings: Dashboard Icons : get Random Color for dashboard icons [1/2]
8cae284 Settings: dashboard icons: Fix theme for external icons on 10 [2/2]
ccb068d Settings: Theme settings dashboard icons [2/3]

====================
     07-21-2020
====================


   * frameworks/base
260c5ab base: VolumePluginManager: Add default constructor
b3b974b Revert "Revert "fwb: Implement VolumePluginManager""
f473879 Revert "Revert "fwb: Allow using plugins even on production""
507f3ca SystemUI: change QS Background color to transparant
59ed309 QsBgNew : Make it toggleable for new gradient QS [1/2]

   * manifest
8ca8ef0 Revert "Revert "manifest: Track plugin packages""

   * packages/apps/AncientSettings
26b9055 AncientSettings: POSP Vol panel styles[2/2]

   * packages/apps/OmniJaws
2010737 OmniJaws: add more minutes times

   * packages/apps/Plugins
b8f39f9 Plugins: nuke AospPanel

   * packages/apps/Settings
239bda9 Settings: Update searchbar

   * vendor/ancient
7350dd9 Revert "Revert "vendor: packages: include plugins packages""

   * vendor/prebuilts
3728cab prebuilts: Add AncientClockWidget

====================
     07-20-2020
====================


   * frameworks/base
172c430 SystemUI: kill Ambient edge pulse animation on hide
84845b6 SystemUI: Ambient lights don't hide AOD content when user has enabled AOD
3574520 SystemUI: Ambeint Edge Pulse layout [1/2]
c6bb9ea SystemUI: Ambient pulse animation [1/2]
5282d61 SystemUI: Repeat edge light animation on all doze wake [1/2]
34db3cf SystemUI: Improve edge pulse
16e9879 SystemUI: Edge Pulse Accent Color [1/2]
9525217 base: Add an option to pulse edge light for all doze triggers [1/2]
703bb66 SystemUI: only call  showAodContent(true) if we are still on the keyguard
02f2d91 SystemUI: use ROWS_HIGH_PRIORITY for active notification pulse check
7f5d5f3 SystemUI: kill any leftover notification pulse on new pulse start

   * packages/apps/AncientSettings
1888e05 AncientSettings: QsBgNew : Make it toggleable for new gradient QS [2/2]
9747883 AncientSettings: re-arrange interfaces
93d283c AncientSettings: GamingMode: change Preference for notifications
4f48825 AncientSettings: Ambient Edge Pulse: Remove AOD options if device doesn't have AOD
b108f41 AncientSettings: Ambient Edge Pulse Layout [2/2]
fb18d5f AncientSettings: Ambient edge pulse animation [2/2]
ac18a8a AncientSettings: Repeat edge light animation on all doze wake [2/2]
87e6b65 AncientSettings; Edge Pulse Accent color [2/2]
c04292f AncientSettings: Add an option to pulse edge light for all doze triggers [2/2]
05fbcc0 AncientSettings: ambient light settings
2ffa254 AncientSettings: Pulse and Ambient notification bars [2/2]
5776fc7 AncientSettings: Ambient Edge Pulse Customizations [2/2]
b1f5343 AncientSettings: Fix edge lighting colorpicker showing wrong colorhex in summary
4cb0709 AncientSettings: Add ambient pulse notification [2/2]
bc42e01 [SQUASH] revert ambient light
3ff3b91 AncientSettings: Disable Notifications vibration [2/2]
e62d27b AncientSettings: GamingMode: Option to disable notification feedback [2/2]
1835e56 AncientSettings: GamingMode: option to disabe all headsup notifications [2/2]
e8bf16e AncientSettings: add more ancient QS tile style
ba59c38 AncientSettings: disco dingo the qs [2/2]

====================
     07-19-2020
====================


====================
     07-18-2020
====================


   * frameworks/base
0285d39 SystemUI: add Ambient Lights always on hide aod content option
8f4dc8b SystemUI: trigger pulse light only for notifications
993d8fb SystemUI: replace pulse light drawable with our own vector
377823f SystemUI: add Pulse and Ambient notification bars [1/2]
c5b3d1e Ambient Edge Pulse Customizations [1/2]
c4a601b Disable Notifications vibration [1/2]
5f2b8a1 GamingMode: Option to disable notification feedback [1/2]
3174b88 base: Use MD2 drawables for Gaming mode
54aa1cb GamingMode: option to disabe all headsup notifications [1/2]
41b0068 Forward port CM Screen Security settings (1/2)
077adfb fwb: core: enable LiveDisplay by defaults

   * manifest
878c900 manifest: tracker livedisplay

   * packages/apps/Settings
2e5d719 Settings: Forward port pattern visibility settings (2/2)
d8683ea Settings: Forward port lock pattern grid size (2/2)
4657efb Settings: Move custom dp settings under Display
5cbd604 Settings: Configurable 0, 90, 180 and 270 degree rotation [2/2]
de12bb6 Settings: LiveDisplaySettings: Hide Reading Mode if wellbeing app is enabled
6b20f5f Settings: remove LiveDisplay if not supported
6653f29 Settings: LiveDisplaySettings: Hide automatic outdoor mode preference on HWC2
028d2d6 Settings: LiveDisplaySettings: Reenable display mode preference for outdoor mode
c07c967 Settings: Don't index display mode and color temperature on HWC2
09fd95a Settings: LiveDisplaySettings: Fix outdoor mode preference on hwc2
49c35f3 Settings: livedisplay: Don't show display mode and color tempertature on HWC2
86d5255 Settings: LiveDisplay: Add illustration into picture and color adjustment
eed0eb6 Settings: Changes for LiveDisplay

====================
     07-17-2020
====================


   * frameworks/base
e829036 Utils: Add isPackageAvailable method
0e0844f ReadingModeTile: Go away if wellbeing app is enabled
f51deb9 fwb:core: make LiveDisplay optional
0e0270e QSTileHost: Recreate tiles when LiveDisplay gets initialized
f643ca8 base: Disable LiveDisplay low power consumption by default
cf4a819 LiveDisplayTile: Fixup modes cycling for aosp implementation
74e3e20 LiveDisplayTile: import missing settings provider
aaa2927 LiveDisplayManager: Perform null check in getConfig()
e2160b5 OutdoorModeController: Unconditionally enable auto mode on HWC2
ce525e5 OutdoorModeController: Advertise MODE_AUTO
b4174e6 LiveDisplayService: Properly disable ColorTemperature
9e7d486 LiveDisplayTile: Refresh state after livedisplay initialization
3d79a49 LiveDisplayTile: Enable for outdoor mode and skip night display on HWC2
0e9803b LiveDisplayService: Notify SystemUI after initialization finished
a2ce7f1 LiveDisplayService: Disable ColorTemperature when NightDisplay is available
7771019 LiveDisplay: Use Google's algorithm to convert color temperature to RGB
5fdd9b7 LiveDisplay: Change night/day mode transition behavior
8aeb013 LiveDisplay: Disable by default
250b1f0 LiveDisplay: don't start services if phone is encrypted
e98cc58 SystemUI: Add reading mode tile
60f4cdc SystemUI: Add LiveDisplay tile
6ede36d Introduce LiveDisplay from Lineage
40ee9cf build: Don't check for fingerprint mismatch
43d6b46 Configurable 0, 90, 180 and 270 degree rotation
bb1265a add more Ancient QS tile style

   * manifest
96b0b80 manifest: tracker slimrecent

   * packages/apps/AncientSettings
ab90ea9 AncientSettings: Random Qs Tint: tint active QS Tiles with random colors [2/2]
abfb238 AncientSettings: Introduce QS Setting Styles [2/2]
e506fe5 AncientSettings: Introduce QS Analog Styles [2/2]
f8fefb1 AncientSettings: Add toggle to hide lock icon on lockscreen [2/2]
23c9570 AncientSettings: Status bar notification ticker [2/2]
a073423 AncientSettings: Introduce QS Clock Styles [2/2]

   * vendor/ancient
c3e3b1e vendor: Add back livedisplay permissions

====================
     07-16-2020
====================


   * frameworks/base
bbb4cff StichImageUtility: allow taking screenshot on home screen
8bd79a7 QsTileStyle: adapt for gradient & our tinting options
a7de593 SystemUI: remove int newtint
cc76b0a QS Tile : fix the issue of icons disappearing
203a68f QSTileBaseView: Make QS Tile Disco a bit more random
39e26dc disco dingo the qs [1/2]
b9c75ba Random Qs Tint: tint active QS Tiles with random colors [1/2]
707de76 ColorUtils: Allow overriding Random seeds
7080734 base: Disco mode!
925319a base: add and fix @hide javadocs
5441a10 Introduce Settings style picker [1/2]
e33ea01 Introduce QS Analog style picker [1/2]
97f2e9e SystemUI: hide lock icon while dozing
e69a93d Add toggle to hide lock icon on lockscreen [1/2]
aabddd8 Status bar notification ticker [1/2]
32c7eea Set Assistant UID of the current user.
c70d928 Process: Use audio-app cpuset if available
0990622 Introduce QS Clock style picker [1/2]



Device Changelog:

 • Update Perf/Iop blobs from LA.UM.8.6.2.r1-04400-89xx
 • Import Graphics (HDR) from LA.UM.8.6.r1-04400-89xx.0
 • wifi: enable QPower and Deep sleep at the same time
 • Enable Make WiFi Calling preference editable for Jio 
(India)
 • Increase in-call earpiece volume
 • Add call recording Overlay
 • Add Smoother from ScreenRecord
 • Use cpusets for services
 • Update post boot from LA.UM.8.6.r1-04600-89xx.0
 • enable zygote preforking
 • Set zRam disk size to 50% of RAM size.
 • Fixed Radio
