pkgname=haystack
pkgver=0.3.0
pkgrel=1
pkgdesc="A tool to categorise your screenshots"
arch=('x86_64' 'aarch64')
url="https://github.com/JohnCosta27/haystack-arch"
license=('MIT')
depends=('cairo' 'desktop-file-utils' 'gdk-pixbuf2' 'glib2' 'gtk3' 'hicolor-icon-theme' 'libsoup' 'pango' 'webkit2gtk-4.1' 'slurp' 'grim')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("${url}/releases/download/v${pkgver}/Haystack_${pkgver}_amd64.deb")
sha256sums_x86_64=('24cdb147e4862fdc13d678a1b94431f191f61440ec3b916c039e67f998c108dc')

package() {
  # Extract package data
  tar -xvf data.tar.gz -C "${pkgdir}"
}
