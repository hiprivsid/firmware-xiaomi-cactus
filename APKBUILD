pkgname=firmware-xiaomi-cactus
pkgver=1
pkgrel=0
_commit="f1bd0abe5721863b4a97028903ca20593a23807c"
pkgdesc="Firmware files for Xiaomi Redmi 6A"
url="https://postmarketos.org"
arch="armv7"
license="proprietary"
depends=""
source="$_commit.tar.gz::https://github.com/hiprivsid/postmarketos-vendor-xiaomi-cactus/archive/$_commit.tar.gz"
options="!strip !check !archcheck !spdx !tracedeps pmb:cross-native"

_fwdir="/lib/firmware/postmarketos"

package() {
	cd "$srcdir/postmarketos-vendor-xiaomi-cactus-$_commit"
        install -Dm0644 *.* -t "$pkgdir/$_fwdir"
}

sha512sums=""
