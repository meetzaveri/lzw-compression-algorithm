# lzw-compression-algorithm
LZW data compression method implemented using c++

# Todo
 - Fix  this issue - a 4057-byte file (the source code itself) became 18720 bytes when compressed! Then I looked at the        "compressed" file and saw that it was composed of ASCII '1' and '0' characters rather than binary. If that had been converted to binary output, that would be 2340 bytes which actually is smaller than the input
