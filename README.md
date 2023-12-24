![](https://raw.githubusercontent.com/mhtvsSFrpHdE/contact-me/master/AboutIssue.svg)

# Grayfox

Firefox, but so gray.

For people don't want those colors surround font edge.

Removes RGB subpixel font antialiasing on Firefox UI by using `userChrome.css`,  
and an extra `userContent.css` to do the same all over the web.

## Install

See https://github.com/mhtvsSFrpHdE/Tibetanfox#install

## Behind

The idea is a community discover that when `opacity` apply to web elements,  
RGB antialiasing will be replaced by grayscale antialiasing,  
with basically no quality lose on modern FHD displays.

Grayscale is far better than RGB if monitor is not LCD RGB (OLED),  
or screen is rotated.

This hack also allows using grayscale font antialiasing while keep hardware acceleration remains enabled.

More discuss on internet:  
https://github.com/snowie2000/mactype/issues/873  
https://github.com/microsoft/PowerToys/issues/25595  
https://github.com/snowie2000/mactype/issues/932
