# Maintainer: Felix Yan <felixonmars@archlinux.org>

pkgname=python2-monotonic
pkgver=0.5
pkgrel=1
pkgdesc="An implementation of time.monotonic() for Python 2 & < 3.3"
arch=('any')
url='http://pypi.python.org/pypi/monotonic'
license=('Apache')
depends=('python2')
makedepends=('python2-setuptools')
source=("https://pypi.python.org/packages/source/m/monotonic/monotonic-${pkgver}.tar.gz")
sha256sums=('8c1f882aa66c41daffa701cbf7121d8d264d0cb7722bbb78a6eccd2d8b12c880')

package() {
  cd monotonic-${pkgver}
  python2 setup.py install --root="${pkgdir}" --optimize=1
}

# vim: ts=2 sw=2 et:
