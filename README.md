# Facebook Aperture Exporter

## About
This is a simple exporter plugin for <a href="http://www.apple.com/aperture/">Apple's Aperture</a>. I wasn't happy with the built-in syncing Aperture 3 has, and the existing export plugin for Facebook wouldn't work for me. Plus, that author wasn't returning my emails to try and get it to work. So I wrote my own.

## Current Features
* Logging in and out of a Facebook account
* Album creation with privacy and selection (where to upload the photos to)
* High resolution photo uploads to Facebook
* Enabled by uploading large versions to Facebook (choose an export preset that will create 2048 pixels along the largest side)
* Option to use IPTC headline instead of caption as photo title (<a href="https://github.com/streeter/facebook-aperture-exporter/issues/9">Issue #9</a>)
* Sparkle updating
* Growl notifications

## Known Limitations and Issues
* <del>The preferences button does nothing. Eventually it will show the preferences window.</del>
* The export progress information in the Activity panel is pretty much broken. At least you know it is still exporting.
* The caption for a created Facebook album is not set. Still figuring out why that is the case.
* <del>The open album when upload is complete checkbox does not work</del>
* <del>The Sparkle update framework only runs when the plugin is closed.</del>
* <del>The Sparkle framework doesn't reopen Aperture after updating the plugin. This
means you need to open Aperture manually.</del>

## Nice Features to Have
* Choose whether to use the Title or Description from each photo to use as the photo's caption on Facebook (currently uses the title).
* Add a tag to all uploaded photos

## Usage and Installation
1. You need OS X 10.7 (Lion) to use the latest plugin.
2. Download the <a href="https://github.com/streeter/facebook-aperture-exporter/downloads">plugin from github</a>.
3. After downloading, put the plugin in the directory `~/Library/Application Support/Aperture/Plug-Ins/Export`. If the `Plug-Ins` and / or `Export` directories do not exist, create them.
4. If Aperture is running, restart it.
5. Select the versions to export, choose `File -> Export -> FacebookExporter...`

## Screenshot

<a href="https://github.com/streeter/facebook-aperture-exporter/raw/master/screenshot.png"><img width="600" style="width: 600px" src="https://github.com/streeter/facebook-aperture-exporter/raw/master/screenshot.png" /></a>

## Authors
* <a href="http://www.chrisstreeter.com">Chris Streeter</a>
* <a href="https://github.com/alinx">Alex Brand</a> (contributor)
* Some code is taken from <a href="https://github.com/facebook/facebook-ios-sdk">Facebook's iOS Library</a> (why don't they have a desktop SDK!)
* Inspiration from the <a href="http://code.google.com/p/aperture-picasa-plugin/">Aperture to Picasa Plugin</a>
