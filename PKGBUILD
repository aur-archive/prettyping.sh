# Maintainer: Wyatt J. Brown <sushidudeteam@gmail.com>
pkgname=prettyping.sh
pkgver=r169.b20d762b9c1a
pkgrel=1
pkgdesc='A better user interface for watching ping responses.'
arch=('any')
url='https://bitbucket.org/denilsonsa/small_scripts/src/default/prettyping.sh'
license=('MIT')
source=('https://bitbucket.org/denilsonsa/small_scripts/raw/b20d762b9c1a0d250ddbd8e26850df62d84b1559/prettyping.sh')
sha512sums=('31ab45b25dbd3f8c4ff3cb57e2125804e5229a40114a7bd642ca9493bf8c2631f1aa8a18b4f2679e3bbff97b73b52b8550649c03e6471161023288cc780e2a74')

package()
{
	install -Dm755 $srcdir/$pkgname $pkgdir/usr/bin/$pkgname
}
