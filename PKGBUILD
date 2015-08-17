# Maintainer: Diego Pi
# Developer: Vincenzo Cimmelli
# Contributor: Umberto Reale

pkgname=tubeflush
pkgver=0.3
pkgrel=4
pkgdesc="A script to download music from YouTube videos"
arch=('i686' 'x86_64')
url="https://github.com/vencizon/tubeflush"
license=('GPL3')
depends=('youtube-dl' 'ffmpeg' 'lame')
provides=("tubeflush=$pkgver")
conflicts=('tubeflush-git')
source=(https://raw.github.com/vencizon/tubeflush/e10ef362d8921c99259ab413c48e95bb4f159d9a/tubeflush)
md5sums=('300f3c991f2c96af437fa8c56e718cf4')

package() {
  cd $srcdir
  install -Dm755 tubeflush $pkgdir/usr/bin/tubeflush
}

