# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=archlinux-unbloater
pkgver=0.1
pkgrel=1
epoch=
pkgdesc="A simple script to remove unneeded packages"
arch=( any )
url="https://github.com/itamar567/archlinux-unbloater"
license=('GPL2')
groups=()
depends=( 'base' 'bash' 'dialog' )
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=( "git+https://github.com/itamar567/archlinux-unbloater.git" )
noextract=()
md5sums=( "SKIP" )
validpgpkeys=()

prepare() {
	cd "$pkgname"
}

build() {
	cd "$pkgname"
}

check() {
	cd "$pkgname"
}

package() {
	cd "$pkgname"
	install -Dm=755 unbloater $pkgdir/usr/bin/unbloater
}
