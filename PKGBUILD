# Maintainer: Mauricio de Lima <emauricio@uai21.com>
pkgname=uaiso-calamares-config
_destname1="/etc"
pkgver=22.06
pkgrel=15
pkgdesc="Calamares para UAISO"
arch=('any')
url="https://github.com/UaiSO21"
license=('GPL3')
makedepends=('git')
depends=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}