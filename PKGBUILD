# Maintainer: Pierrick BRUN <pierrick.brun gmail.com>
pkgname=libreoffice-flat-icon-set
pkgver=0.3.8
pkgrel=1
pkgdesc="An icons pack for libreoffice with flat icons"
arch=(any)
url="http://gnome-look.org/content/show.php/Faenza+Icons++for+LibreOffice++4.0.0?content=157970"
license=('GPL')
depends=('libreoffice-common>=4.1.0')
conflicts=('libreoffice-faenza-mod')
install=${pkgname}.install
source=("https://dl.dropboxusercontent.com/u/1229628/libreoffice-flat-icon-set_${pkgver}.zip")
noextract=("libreoffice-flat-icon-set_${pkgver}.zip")
md5sums=('bd14cef48440bdeabb3497831e6c6706') 

package() {
LO_DIR=/usr/lib/libreoffice/share/config

mv libreoffice-flat-icon-set_${pkgver}.zip images_flat.zip
mkdir -p $pkgdir$LO_DIR
cp images_flat.zip $pkgdir$LO_DIR

}

