# Maintainer: Felix Yan <felixonmars@archlinux.org>

pkgname=python2-monotonic
pkgver=0.4
pkgrel=1
pkgdesc="An implementation of time.monotonic() for Python 2 & < 3.3"
arch=('any')
url='http://pypi.python.org/pypi/monotonic'
license=('PSF')
depends=('python2')
makedepends=('python2-setuptools')
source=("https://pypi.python.org/packages/source/m/monotonic/monotonic-${pkgver}.tar.gz")
sha256sums=('852f656adbf623ee859def6ca2f5498f4cae3256f8320d5c50570ee8a0592ab6')

package() {
  cd monotonic-${pkgver}
  python2 setup.py install --root="${pkgdir}" --optimize=1
}

# vim: ts=2 sw=2 et:
