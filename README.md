# Android-ROM

Planning for android rom development

This respository is useless for literally everyone except me as I am not a rom developer. 

Previously had a Pixel with GrapheneOS, loved everthing except the difficulty in rooting it. Had to use Kitsune Mask but I believe this has not been abandoned. 
Now I have a Sony Xperia 1V XQ-DQ72

Device Philosophy:
- If I buy it, I own it
- Bootloader unlocking fully supported by OEM, ideally without a code provided by the manufacturer
- Buy phones second hand so I care less about whether this violates warranty
- Parts should be available and not difficult replace
- Expandable storage is mandatory.
- USB-C video out is mandatory 

ROM Philosophy:
- Privacy and functionality over physical-access security
    - Minimize tracking, google services use
- Google services / Apps as needed in sandbox is okay
- No bloat
- Root is good
    - This is the only way to reliably get call recording in Canada as google refuses to allow it despite being entirely legal across the Country.
    - Proper device backups
    - Potentially there will be a workaround to install apps that require installation via Play Store (new Android 15 'feature')
  

Rough plan: 
- LineageOS vs AOSP vs AOSPA base
- Integrate GMScompat from GrapheneOS for sandboxed google play vs
- Starting point: https://github.com/Paranoid-Xperia

What available codebases are there?
- AOSP
- CLO (CodeLinaro, formerly CAF [CodeAuroraForums]?) - https://git.codelinaro.org/clo
- LineageOS
