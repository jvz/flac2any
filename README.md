flac2any
========

Collection of scripts to convert FLAC audio files to other formats including MP3, AAC, Ogg Vorbis, and ALAC.

This project depends on [FFmpeg](http://ffmpeg.org/) for general audio transcoding.
There is also a fallback mechanism to use individual tools like `flac`, `metaflac`,
`oggenc`, `lame`, `faac`, etc., but metadata that is copied is limited to a subset
of all the possible metadata tags that may be supported in a particular format.

Flac2any is licensed under the [OpenBSD license](http://www.openbsd.org/cgi-bin/cvsweb/src/share/misc/license.template?rev=1.3;content-type=text%2Fplain),
which means you can do pretty much anything you want with it.
