<h1>FFmpeg XCFrameworks</h1>

This repository contains pre-built FFmpeg XCFrameworks for iOS, ready to integrate into Xcode projects without additional compilation.

<br> </br>

<h2>📦 Included Frameworks</h2>

The repository provides the following XCFrameworks:

+ ffmpegkit.xcframework
+ libavcodec.xcframework
+ libavdevice.xcframework
+ libavfilter.xcframework
+ libavformat.xcframework
+ libavutil.xcframework
+ libswresample.xcframework
+ libswscale.xcframework

These libraries enable advanced audio/video processing, encoding, decoding, muxing, demuxing, filtering, scaling, and device I/O operations.

<br> </br>


<h2>🔧 Installation</h2>

+ Clone or download this repository.
+ Drag the .xcframework folders into your Xcode project’s Frameworks folder.
+ In the import dialog, enable: Copy items if needed
+ Mark them as Embed & Sign in your Target -> General -> Frameworks, Libraries, and Embedded Content section
