A fork of Drew Diller's fantastic [DD_belatedPNG](http://www.dillerdesign.com/experiment/DD_belatedPNG/) IE6 PNG fix.

### Changes

There are a couple of differences in this version, compared to [v0.0.8a](http://www.dillerdesign.com/experiment/DD_belatedPNG/#download).

- Cache busted PNGs are supported. We encountered an issue where PNG files with URLs like *.png?12345 weren't being fixed.
- Resized images are supported. We encountered some issues with PNG images that were being displayed at a smaller size than the file's dimensions. After the PNG was applied to the file, the VML image within the fix was the original size rather than the resize. Currently this is supported in a fairly hacky way by adding rel="size_75px-62px" (size_&lt;width&gt;px-&lt;height&gt;px) to the image being fixed.
