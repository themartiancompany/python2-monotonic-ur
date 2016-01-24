# Maintainer: Felix Yan <felixonmars@archlinux.org>

pkgname=python2-monotonic
pkgver=0.6
pkgrel=1
pkgdesc="An implementation of time.monotonic() for Python 2 & < 3.3"
arch=('any')
url='http://pypi.python.org/pypi/monotonic'
license=('Apache')
depends=('python2')
makedepends=('python2-setuptools')
source=("https://pypi.python.org/packages/source/m/monotonic/monotonic-${pkgver}.tar.gz")
sha256sums=('2bc780a16024427cb4bfbfff77ed328484cf6937a787cc50055b83b13b653e74')

package() {
  cd monotonic-${pkgver}
  python2 setup.py install --root="${pkgdir}" --optimize=1
}

# vim: ts=2 sw=2 et:
