# Contributor: Nebulosa <nebulosa2007 na yandekse>

pkgname=2gis-voronezh
pkgver=7
pkgrel=1
pkgdesc="Map of Voronezh for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Voronezh-${pkgver}.orig.zip")
md5sums=('3cb077c941fc7fff1ab961f77a319f50')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Voronezh.dgdat "${startdir}/pkg/opt/2gis/voronezh.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Voronezh.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Voronezh.dglf" || return 1

}
