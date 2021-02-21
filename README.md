# pbf3-min

Update your pbf3.0.5.min.to 3.2.1!


# Info about changes
3.2.1 (Oct 11, 2019)

 - Significantly improved performance when decoding large strings in the browser.

3.2.0 (Mar 11, 2019)

 - Improved decoding to be able to parse repeated fields even if they were specified as packed, and vise versa.
 - Improved packed encoding to skip empty arrays (previously, it would write a tag).
 - Fixed an off-by-one data corruption bug when writing a message larger than 0x10000000 bytes.

3.1.0 (Sep 27, 2017)

 - Added support for Protocol Buffer 3 maps to proto compiler.
