A fork of Drew Diller's fantastic [DD_belatedPNG](http://www.dillerdesign.com/experiment/DD_belatedPNG/) IE6 PNG fix.

### Changes

Forked from [v0.0.8a](http://www.dillerdesign.com/experiment/DD_belatedPNG/#download).

There are a couple of differences in this version:

- **Cache busted PNGs are supported.** We encountered an issue where PNG files with URLs like *.png?12345 weren't being fixed.
- **Resized images are supported.** This fork allows you to use an img tag and display the image at a different size. Previously a resized image would be displayed at its original size after the fix was applied.