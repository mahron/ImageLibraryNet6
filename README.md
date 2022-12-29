# .Net Image Library

.NET library for easy image handling like:
  * Filters
  * Cropping
  * Thumbnail creation
  * Saving as JPG/GIF/PNG files or streams
  * Opening images from streams or URLs

You'll find information on how to get started at http://kaliko.com/image-library/get-started/ and full API documentation at http://kaliko.com/image-library/api/

<a href="https://www.nuget.org/packages/ImageLibrary/">Get .Net Image Library from NuGet</a>

Using only safe code making this library possible to use on web hosts with medium trust.

When having access to full trust make sure to use ImageLibrary.FastFilters to greatly improve performance!

Current build contains the following filters:
  * Gaussian blur filter
  * Unsharpen mask filter
  * Chroma key filter
  * Contrast filter
  * Brightness filter
  * Invert filter
  * Desaturnation filter

If you plan using this library with WPF or simular, read this post on <a href="http://labs.kaliko.com/2011/03/convert-to-bitmapimage.html">how to convert an KalikoImage object to System.Windows.Media.Imaging.BitmapImage and System.Windows.Controls.Image</a>.

## History


**1.0.0**
  * recompiled with net6

