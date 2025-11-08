# Maintainer: Wael0dfg <iratenwaelx@gmail.com>

pkgname='fs'
pkgver=1.0.0
pkgrel=1
pkgdesc="a Simple CLI tool to show file and directory sizes"
arch=('any')
url="https://github.com/Wael0dfg/fs.git"
license=('custom')
depends=('python')

install=
changelog=
source=('fs::git://github.com/Wael0dfg/fs.git')
sha256sums=('skip')

build() {
	cd "$pkgname-$pkgver"
	make
}

package() {
	cd "$pkgname-$pkgver"
	install Dm755 ./fs "$pkgdir/usr/bin/fs"
}
