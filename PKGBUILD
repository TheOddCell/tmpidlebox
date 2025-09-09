pkgname=tmpidlebox
pkgver=1.0.0
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary Idlebox"
arch=('any')
url="https://github.com/TheOddCell/tmpidlebox"
license=('MIT')
depends=('bash' 'busybox' 'systemd')
makedepends=()
source=('tmpidlebox')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpidlebox "$pkgdir/usr/bin/tmpidlebox"
}
