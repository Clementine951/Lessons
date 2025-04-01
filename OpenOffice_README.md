<p align="center"><em>What if you could write, edit, and manage documents with power, flexibility, and freedom… all in one open-source suite?</em></p>
<p align="center">
  <img style="height:200px" src="https://www.openoffice.org/ui/VisualDesign/gifs/Images/OOo24_splashscreen.png" />
</p>

<p align="center">
  <a href="#license--usage">License & Usage</a> •
  <a href="#system-requirements">System Requirements</a> •
  <a href="#installation">Installation</a> •
  <a href="#issues--workarounds">Issues & Workarounds</a> •
  <a href="#accessibility">Accessibility</a> •
  <a href="#customization">Customization</a> •
  <a href="#registration--feedback">Registration & Feedback</a> •
  <a href="#support">Support</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#legal">Legal</a>
</p>

<hr>

# OpenOffice.org 2.4

A full-featured, free, and open-source office suite. Developed by the community, for the community.

Learn more → [Introduction to OpenOffice.org](http://www.openoffice.org/about_us/introduction.html)  
Latest updates → [Release Notes](http://www.openoffice.org/welcome/readme.html)

## What’s New in 2.4
- **Improved Performance:** Faster startup and document loading
- **Enhanced Compatibility:** Better support for Microsoft Office formats
- **New Features:**  
  - Improved PDF export options
  - Enhanced spreadsheet functions
  - New templates and wizards
- **Bug Fixes:** Over 100 issues resolved, including:
  - Improved stability
  - Better handling of large documents
  - Enhanced printing options
- **User Interface Improvements:**
  - Updated icons and themes
  - Streamlined menus and toolbars
  - Enhanced accessibility features
- **Security Enhancements:**
  - Improved document encryption
  - Enhanced macro security
  - Better handling of external links

## License & Usage
OpenOffice.org is 100% free to use for:
- Government
- Businesses
- Educational institutions
- Personal users

See the [full license](http://www.openoffice.org/license.html).



## System Requirements
- **OS:** Windows 98/ME/NT (SP6+)/2000/XP  
- **CPU:** Pentium-compatible  
- **RAM:** 64 MB minimum  
- **Disk Space:** 250 MB+ (500 MB post-install)  
- **Display:** 800x600 resolution, 256+ colors



## Installation
1. Close all programs before starting
2. Accept Administrator rights

> Java install on Windows 98 may request a reboot

## Issues & Workarounds
- **Startup issues:** Update graphics drivers; disable OpenGL via:
  `Tools → Options → OpenOffice.org → View`
- **Clipboard issues:** Use `Edit → Paste Special` if pasting fails
- **Multiple versions:** You can install 2.4 alongside older versions; run installer > Repair if needed
- **Email issues:** Some systems crash when using `File → Send`; refer to Microsoft's MAPI info



## Accessibility
### Touchpad Scrolling (ALPS/Synaptics)
Add this to `SynTPEnh.ini` and restart:
```
[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000
```

### ZoomText Support
ZoomText version 7.11+ required (downloaded after June 12, 2002).



## Customization
### Keyboard Shortcuts
- Conflicts may occur with OS-defined shortcuts
- Customize via `Tools → Customize → Keyboard`



## Registration & Feedback
### Product Registration
Optional, but helps us improve. Register any time at:  
[Registration Page](http://www.openoffice.org/welcome/registration-site.html)

### User Survey
Help shape future releases. Anonymous data, strict privacy policy.



## Support
- FAQ: [user-faq.openoffice.org](http://user-faq.openoffice.org/)
- Mailing Lists: [Mailing Info](http://www.openoffice.org/mail_list.html)
- Ask the community: users@openoffice.org



## Contributing
You don't need to be a developer! Help by:
- Translating/localizing
- Editing documentation
- Testing and reporting bugs
- Promoting OpenOffice.org

Start here: [Join a Project](http://www.openoffice.org)



## Legal
- Portions © 1998–1999 James Clark
- Portions © 1996–1998 Netscape Communications Corporation



Thank you for using OpenOffice.org 2.4 — we hope you’ll join our community!

