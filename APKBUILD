pkgname=firmware-xiaomi-cactus
pkgver=2
pkgrel=1
pkgdesc="Firmware files for Xiaomi Redmi 6A"
url="https://github.com/hiprisid/firmware-xiaomi-cactus"
arch="armv7"
depends=""
license="proprietary"
options="!strip !check !archcheck !spdx !tracedeps pmb:cross-native"
_commit="f1bd0abe5721863b4a97028903ca20593a23807c"
source="cactus-fw-$_commit.tar.gz::https://github.com/hiprivsid/postmarketos-vendor-xiaomi-cactus/archive/$_commit.tar.gz"
_fwdir="/lib/firmware/postmarketos"

package() {
	cd "$srcdir/postmarketos-vendor-xiaomi-cactus-$_commit"
  install -Dm0644 *.* -t "$pkgdir/$_fwdir"
}

sha512sums=""
