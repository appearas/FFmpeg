# Build arguments

The following arguments are provided to configure:
--enable-shared
--enable-demuxer=mpegts,mpegvideo,image2
--enable-muxer=mpegts
--enable-protocol=file,udp,rtp,srt
--enable-filter=overlay
--enable-zlib
--disable-doc
--enable-libsrt
--extra-cflags=-Wno-attributes
--extra-cflags=-Wno-deprecated-declarations
--extra-cflags=-Wno-format-truncation
--extra-cflags=-Wno-discarded-qualifiers
--extra-cflags=-Wno-format-overflow
--extra-cflags=-Wno-alloc-size-larger-than
--extra-cflags=-Wno-stringop-overflow
--extra-cflags=-Wno-stringop-truncation
--extra-libs=-lsrt
