# Maintainer: Jan Boelsche <jan@lagomorph.de>

pkgname='auto-dhcp'
pkgver=1.0
pkgrel=2
pkgdesc='networkd config that enables DHCP on ethernet interfaces'
packager='Jan Boelsche'
arch=('any')
license=('GPL')
groups=()
depends=('dhcpcd')
makedepends=()
checkdepends=()
optdepends=()
install=
source=('20-wired.network')

sha256sums=('9874e14209f363517c1cfa8d9c2f01af95328a25864dd63aaac6f1b980c70932')

package () {
  install -Dm 744 -t "${pkgdir}/etc/systemd/network" 20-wired.network
}
