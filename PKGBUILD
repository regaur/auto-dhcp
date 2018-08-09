# Maintainer: Jan Boelsche <jan@lagomorph.de>

pkgname='auto-dhcp'
pkgver=1.0
pkgrel=1
pkgdesc='udev rule to start dhcpcd for network upcoming network interfaces'
packager='Jan Boelsche'
arch=('any')
license=('GPL')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
install=${pkgname}.install
source=('81-dhcpcd.rules')

sha256sums=('631c80787d60f0ac40455ae13f401c5c849dc6496816208b1ab63db1f46c664d')

package () {
  install -Dm 744 -t "${pkgdir}/etc/udev/rules.d" 81-dhcpcd.rules
}
