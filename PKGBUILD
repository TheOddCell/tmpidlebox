pkgname=tmpidlebox
pkgver=2.0.0
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary Idlebox"
arch=('any')
url="https://github.com/TheOddCell/tmpidlebox"
license=('MIT')
depends=('systemd')
makedepends=()
optdepends=('busybox: removes requirement to bring your own')
source=('tmpidlebox')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpidlebox "$pkgdir/usr/bin/tmpidlebox"
}
