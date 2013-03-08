# Maintainer: Ivan Abdulin <elbahek@gmail.com>

pkgname=xerial-sqlite-jdbc
_pkgname=sqlite-jdbc
pkgver=3.7.2
pkgrel=2
pkgdesc="Xerial implementation of SqliteJDBC"
arch=('i686' 'x86_64')
url="http://www.xerial.org/trac/Xerial/wiki/SQLiteJDBC"
license=('Apache')
depends=('java-runtime')
source=(https://bitbucket.org/xerial/sqlite-jdbc/downloads/sqlite-jdbc-3.7.2.jar)

package() {
  install -D -m644 \
    $srcdir/${_pkgname}-${pkgver}.jar \
    $pkgdir/usr/share/java/${pkgname}/${pkgname}-${pkgver}.jar
  ln -s ${pkgname}-${pkgver}.jar $pkgdir/usr/share/java/${pkgname}/${pkgname}.jar
}
md5sums=('5fa420d75512d78ba9b08143ddca61b7')
