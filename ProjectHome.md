## About ##

gcap is a command line tool for downloading Youtube closed captions. The downloaded closed captions are saved in Subrip (srt) file format. The srt files are saved as "$videoid_$langid.srt" by default._

## News ##

| 2011-11-05 | gcap 0.1.1 [released](http://repo.or.cz/w/gcap.git/blob/refs/tags/v0.1.1:/NEWS) |
|:-----------|:--------------------------------------------------------------------------------|
| 2011-09-01 | gcap 0.1.0 [released](http://repo.or.cz/w/gcap.git/blob/refs/tags/v0.1.0:/NEWS) |

## Synopsis ##

```
gcap [-i] [-t] [-r <regexp>] [--proxy=<addr> | --no-proxy] [--help] <url> | <video_id>
```

## Example ##

```
# Typical use.
gcap 0QRO3gKj3qw

# Same as above but with full URL.
gcap "http://www.youtube.com/watch?v=0QRO3gKj3qw"

# Same as above two but use video title in the filename and choose which
# of the closed captions should be downloaded.
gcap -ti 0QRO3gKj3qw
```

## gitweb ##

  * http://repo.or.cz/w/gcap.git

## See also ##

  * [umph](http://umph.googlecode.com/)
  * [grake](http://grake.googlecode.com/)
  * [cclive](http://cclive.sourceforge.net/)
  * [clive](http://clive.sourceforge.net/)