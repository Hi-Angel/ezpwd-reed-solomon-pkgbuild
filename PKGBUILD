# Maintainer: Konstantin Kharlamov <Hi-Angel@yandex.ru>

pkgname='ezpwd-reed-solomon-c++'
pkgver=1.8.0
pkgrel=1
pkgdesc='A header-only Reed-Solomon codes implementation'
arch=('any')
url='https://github.com/pjkundert/ezpwd-reed-solomon'
license=('custom')
source=("https://github.com/pjkundert/ezpwd-reed-solomon/archive/v$pkgver.tar.gz")
sha256sums=('d31ab61b4cc911508969d150f571878e824434c789d2a67870aeb1e3a9225211')

package() {
	cd "$srcdir/ezpwd-reed-solomon-$pkgver"
	mkdir -p  "$pkgdir/usr/include"
	cp -r c++/ezpwd "$pkgdir/usr/include/"
	mkdir -p  "$pkgdir/usr/share/licenses/$pkgname"
	install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
