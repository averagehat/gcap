## Note ##

The release notes are no longer duplicated in this page. Please see the [NEWS](http://repo.or.cz/w/gcap.git/blob/HEAD:/NEWS) in the repository, instead.

### 0.1.0  Thu Sep 01 2011  Toni Gundogdu ###
Changes:
  * use Perl 5.10.1+
  * use Umph::Prompt with --interactive
    * Makes several improvements to the (old) prompt
    * Get it from http://umph.googlecode.com/ for now

### 0.0.8  Sun Mar 20 2011  Toni Gundogdu ###
Changes:
  * Print page URL instead of GVI URL with error messages
  * Extend URL pattern to cover the new "/embed/"
Bugfixes:
  * Empty captition queue check (e.g. ignore -i if empty)

### 0.0.7  Thu Mar 03 2011  Toni Gundogdu ###
Bugfixes:
  * Allow use of video IDs starting with dash ([issue #3](https://code.google.com/p/gcap/issues/detail?id=#3))


### 0.0.6  Sun Feb 20 2011  Toni Gundogdu ###

Changes:
  * Add HTML::Entities prerequisite
  * Add man1/gcap.1.pod
Bugfixes:
  * Decode HTML entities ([issue #2](https://code.google.com/p/gcap/issues/detail?id=#2))

### 0.0.5  Tue Nov 30 2010  legatvs ###

Changes:
  * Add --quiet
  * Add --proxy, --no-proxy
Bugfixes:
  * Fix "Nested quantifiers in regex" with Perl 5.8
    * Ported from grake, see <http://is.gd/hZj5f>

### 0.0.4  Sun Oct 31 2010  legatvs ###

Changes:
  * Add missing COPYING
  * Add t/gcap-Pod.t
  * Use "version" module

### Version 0.0.3  September 28, 2010 ###

Changes:
  * Update synopsis, help strings

### Version 0.0.2  August 26, 2010 ###

Changes:
  * Add support for embedded URLs

Bugfixes:
  * Load proxy settings from http\_proxy environment variables
  * Title parsing failed with ampersands

### Version 0.0.1  August 14, 2010 ###

  * Initial release