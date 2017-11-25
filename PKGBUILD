# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=scripts-kibojoe
pkgver=1709
pkgrel=7
pkgdesc="Scripts for Kibojoe Linux"
arch=('any')
license=('GPL3')
url="https://github.com/kibojoe/scripts-kibojoe"
source=("git+$url.git")
sha256sums=('SKIP')

package() {
	cd $srcdir/$pkgname
	install -dm755 $pkgdir/usr/bin
	cp -r $srcdir/$pkgname/kibojoe $pkgdir/usr/bin
}