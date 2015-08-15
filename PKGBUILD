# Maintainer: James Barbour <james jebarb com>
pkgname=explain
pkgver=20140406
pkgrel=1
pkgdesc="Explain is a command line tool that takes in a command with options and prints out what those options do, straight from the man page."
url="https://github.com/andysalerno/explain"
arch=('any')
license=('MIT')
source=("git://github.com/andysalerno/explain.git")
md5sums=('SKIP')

build() {
  cd "${srcdir}/${pkgname}"
  make
}

package() {
  install -Dm755 explain/explain "$pkgdir"/usr/bin/explain
}

# vim:set ts=2 sw=2 et:
