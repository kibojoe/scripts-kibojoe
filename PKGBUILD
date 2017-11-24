# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=scripts-kibojoe
pkgver=20171123
pkgrel=0
pkgdesc="Scripts for Kibojoe Linux"
arch=('any')
license=('GPL3')
url="https://github.com/kibojoe/scripts-kibojoe"
source=("git+$url.git")
sha256sums=('SKIP')

pkgver() {
	date +%Y%m%d
}

package() {
	cd $srcdir/$pkgname
	install -dm755 $pkgdir/usr/bin
	cp -r $srcdir/$pkgname/kibojoe $pkgdir/usr/bin
}