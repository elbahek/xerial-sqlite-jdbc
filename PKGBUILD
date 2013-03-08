# Maintainer: Ivan Abdulin <elbahek@gmail.com>

pkgname=xerial-sqlite-jdbc
pkgver=3.7.2
_fullname=sqlite-jdbc-${pkgver}
pkgrel=2
pkgdesc="Xerial implementation of SqliteJDBC"
arch=('i686' 'x86_64')
url="https://bitbucket.org/xerial/sqlite-jdbc"
license=('Apache')
depends=('java-runtime')
source=(https://bitbucket.org/xerial/sqlite-jdbc/downloads/${_fullname}.jar)

package() {
  install -D -m644 \
    $srcdir/${_fullname}.jar \
    $pkgdir/usr/share/java/${pkgname}/${_fullname}.jar
  ln -s ${_fullname}.jar $pkgdir/usr/share/java/${pkgname}/${pkgname}.jar
}
md5sums=('5fa420d75512d78ba9b08143ddca61b7')
