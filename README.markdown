THE SILENT HISTORY

To make a fat library for debug and release.

Build the library for a debug target and a device in turn, then combine the two libraries.

`lipo -create lib_arm.a lib_i386.a -output lib_universal.a`

**This project is deprecated in favor of the [Mapbox iOS SDK](https://www.mapbox.com/ios-sdk/)**

See [the old readme](README-old.markdown) for the old project details.
