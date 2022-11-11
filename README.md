# moniwiki-apserver
Apache + PHP server package builder for MoniWiki

This is a set of build scripts to make a portable apache+PHP server package for windows users.
This script utilizes the apache/PHP windows packages distributed by official/unofficial sites.

 * PHP : php7.4.x from https://windows.php.net/downloads/releases/archives/
 * Apache : apache2.4.x from https://www.apachelounge.com/download/VC15/
 * rcs57+diffutils for PC: original site: https://www.cs.purdue.edu/homes/trinkle/RCShome/
   * https://github.com/wkpark/rcs57pc - rcs57 mingw32 64bit build.
   * https://github.com/wkpark/pc-diffutils - diffutils 2.7.1 mingw32 64bit build.

To build your own packages you need to install some other utilities
 * zip/unzip
 * wget
 * upx 4.0

To use this package, you might need to install the `vc_redist_x64.exe` redistributable package. Please see https://learn.microsoft.com/ko-kr/cpp/windows/latest-supported-vc-redist?view=msvc-170

## See also
 * MicroApache: http://microapache.kerys.co.uk/ - no more updated.
 * Dokuwiki USB stick builder: https://github.com/splitbrain/dokuwiki-stickbuilder
