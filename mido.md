AncientOS v3.9

Source Changelogs:
• July security patch (r40)
• Removed selinux switch
• Improve fod
• Swipe up on keyguard to use FU
• Fixed edit tile keep pressed while not expanded
• Fixed double tap to check phone
• Fixed SystemUI crash with custom volume panel
• Change default scale animations
• Improved gaming mode
• Disable notification vibration
• Improve edge lightning from ion OS
• Update interval weather
• Live data usage
• Added option for selecting SBC HD codec by default
• Added option for a2dp codec priority
• Added fod pressed
• Added Quick QS brightness slider
• Added Color OS 7 FP animations
• Added realme pressed
• Added Ancient FOS
• Added Pattern 4x4 - 6x6
• Added toogle for gradient QS Background
• Added QS Tile Styles (also add ancient tiles)
• Added QS Clock Style
• Added QS Analog Style
• Added QS Themes
• Added Settings Style
• Added statusbar height for dual row
• Added Settings dashboard icons
• Added slim recents
• Added Switch Styles
• Added QS Label options (accent, gradient)
• Added new QS tint
• Added disable quick settings on LS
• Added Quick settings pulldown
• Added Smart Pulldown
• Added LiveDisplay
• Added sensor block package list
• Added QS tint mode (random, disco)
• Added toogle to hide lock icon on LS
• Added Ancient Widget Clock
• Added longpress power to toogle torch
• Added allow VPN Tethering
• Added Notifications ticker
• More


Device Changelogs:
• Update Display, Media and Audio hals from LA.UM.8.6.2.r1-07800-89xx.0
• XiaomiParts: Nuke all non working stuff ( TCP Congestion, LKM Profiles, Charging LED, Camera Flash Yellow )
• Update Graphics blobs OpenGL-V@474.0
• Checkout init.qcom.post_boot.sh to LA.UM.8.6.2.r1-07800-89xx.0
• Compiled with latest Proton Clang 12
• Update Vulkan 1.1.128 drivers
• XiaomiParts: Fix Vibration Strength node
• Enable Vibration & Haptic strength
• Update qti-telephony-manager from Vsmart Casuari
• Disable vendor mismatch warning
• Updated GCam Go to v2
• Set thermal profile on boot
• Make WiFi channel selection range wider
• Compile HWUI for Better Performance
• Place a copy of updated libprocessgroup.so
• Bring back LiveDisplay
• Battery Health Overlays
• Add Call Recording overlay ( For Vanilla Version only )
• Open /sdcard instead of Downloads by default
• Add Custom Doze Support
• Hide unsupported color effects entry of Snap
• Restart preview for additional camera onPictureTaken
• Update auto/screen brightness overlay from Daisy
• Enable Wired/BT headset focus mode
• Revert "mido: props: Enable zygote preforking"
• Use opensource btconfigstore
• Remove KPI marker at ADSP start
• Remove more deprecated display flags
• Remove left-over c2 codecs reference
• Update qcom-sh service user permission
• Drop display calibration
• Increase max bss count
• Disable BSS flush
• Enable Fast BSS Transition
• Increase maximum number of BSS in memory
• Enable IWLAN overlays
• Enable IMS feature flags for supported carriers
• Revert "mido: Enable GL comp backpressure"
• XiaomiParts: Fixed Settings restore on boot
• Disable vsync for cpu rendered apps
• Misc. audio i/o improvements
• Fixed & Updated many sepolicy denials issues
• Update and resolve additional denials ( Adjust for 4.9 )
• Many under the hood improvements

Note:
- Some features of XiaomiParts are removed because those weren't working, I'll add them back if i find a fix for it...
