pkgname=python3-pyserial
pkgver=2.5
pkgrel=1
pkgdesc="Multiplatform Serial Port Module for Python3"
arch=('any')
url="http://pyserial.sf.net"
license=('custom:PYTHON')
depends=('python')
source=(http://downloads.sourceforge.net/sourceforge/pyserial/pyserial-$pkgver.tar.gz)
md5sums=('34340820710239bea2ceca7f43ef8cab')

build() {
  cd $srcdir/pyserial-$pkgver
  python setup.py install --root=$pkgdir
  install -D -m644 LICENSE.txt $pkgdir/usr/share/licenses/$pkgname/LICENSE.txt
}
