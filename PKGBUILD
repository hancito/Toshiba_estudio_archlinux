# Maintainer Hancito Garcon <garha4@gmail.com>
# Based on package by: Shervin Khastoo <shervinkh145@gmail.com>
https://downloads.toshibatec.eu/publicsite-service/resource/download/pseu/en/a63be5b1-3aff-4c35-870c-11bf8e805ee8/33ffb77e179971644b96b7adf4270a27/TOSHIBA_e-STUDIO_CUPS_v7.103.zip
pkgname=ppd-toshiba-estudio_cups
pkgdesc="Cups driver for the Toshiba e-STUDIO class of printers"
url="https://electronicimaging.toshiba-europe.com/publicsite-service/driver/downloads?cID=12525906-38f4-425f-bb22-66468525d3dd&vkey=pseu&lang=en&locale=en_ENimpression.toshiba.fr&envi="
pkgver=7.103
pkgrel=1
arch=('any')
license=('Propietary')
depends=('cups')
source=('https://downloads.toshibatec.eu/publicsite-service/resource/download/pseu/en/a63be5b1-3aff-4c35-870c-11bf8e805ee8/33ffb77e179971644b96b7adf4270a27/TOSHIBA_e-STUDIO_CUPS_v7.103.zip')
sha256sums=('d57f6ee42b6428f4967726611e80e8b1e167a69aed889462e9fa5a6388ef7ca5')

package() {
  cd ${pkgdir}
  # This two files will be installed
  # usr/lib/cups/filter/est6550_Authentication
  # usr/share/cups/model/Toshiba/TOSHIBA_ColorMFP_CUPS.gz
  tar -xf ${srcdir}/TOSHIBA_e-STUDIO_CUPS_v7.103/CUPS/BW_Unix_Linux/2-sided_default/TOSHIBA_MonoMFP_CUPS.tar
  tar -xf ${srcdir}/TOSHIBA_e-STUDIO_CUPS_v7.103/CUPS/BW_Unix_Linux/normal/TOSHIBA_MonoMFP_CUPS.tar
  tar -xf ${srcdir}/TOSHIBA_e-STUDIO_CUPS_v7.103/CUPS/Color_Unix_Linux/2-sided_default/TOSHIBA_ColorMFP_CUPS.tar
  tar -xf ${srcdir}/TOSHIBA_e-STUDIO_CUPS_v7.103/CUPS/Color_Unix_Linux/normal/TOSHIBA_ColorMFP_CUPS.tar
}



