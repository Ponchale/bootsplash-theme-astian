

pkgbase=bootsplash-themes pkgname=('bootsplash-theme-astian') pkgver=0.1 pkgrel=4 url="https://lists.freedesktop.org/archives/dri-devel/2017-December/160242.html" arch=('any') license=('GPL') makedepends=('imagemagick' 'bootsplash-packer') options=('!libtool' '!emptydirs') provides=("bootsplash-theme-manjaro") conflicts=("bootsplash-theme-manjaro") source=('bootsplash-manjaro.sh' 	'bootsplash-manjaro.initcpio_install' 	'spinner.gif' 	'logo_astian.png') sha256sums=('SKIP'             'SKIP'             'SKIP'             'SKIP') build() {   cd "$srcdir"   sh ./bootsplash-manjaro.sh } package_bootsplash-theme-astian() {   pkgdesc="Bootsplash Theme Astian logo"   cd "$srcdir"   install -Dm644 "$srcdir/bootsplash-manjaro" "$pkgdir/usr/lib/firmware/bootsplash-themes/manjaro/bootsplash"   install -Dm644 "$srcdir/bootsplash-manjaro.initcpio_install" "$pkgdir/usr/lib/initcpio/install/bootsplash-manjaro" } 

