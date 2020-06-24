# Maintainer Hancito Garcon <garha4@gmail.com>
# Based on package by: Shervin Khastoo <shervinkh145@gmail.com>

pkgname=ppd-toshiba-estudio_cups
pkgdesc="Cups driver for the Toshiba e-STUDIO class of printers"
url="https://electronicimaging.toshiba-europe.com/publicsite-service/driver/downloads?cID=12525906-38f4-425f-bb22-66468525d3dd&vkey=pseu&lang=en&locale=en_ENimpression.toshiba.fr&envi="
pkgver=7.99
pkgrel=1
arch=('any')
license=('Propietary')
depends=('cups')
source=('https://electronicimaging.toshiba-europe.com/publicsite-service/resource/download/pseu/en/a63be5b1-3aff-4c35-870c-11bf8e805ee8/8b015933853fee58a68d255602c19837/TOSHIBA_e-STUDIO_CUPS_v7.99.zip')
sha256sums=('83bd3a45a08822fe586d437818220d2751a328c7e84b28c0831634abe1536aca')

package() {
  cd ${pkgdir}
  # This two files will be installed
  # usr/lib/cups/filter/est6550_Authentication
  # usr/share/cups/model/Toshiba/TOSHIBA_ColorMFP_CUPS.gz
  tar -xf ${srcdir}/BW_Unix_Linux/CUPS/Usa/2-sided_default/TOSHIBA_MonoMFP_CUPS.tar
  tar -xf ${srcdir}/BW_Unix_Linux/CUPS/Usa/normal/TOSHIBA_MonoMFP_CUPS.tar
  tar -xf ${srcdir}/Color_Unix_Linux/CUPS/Usa/2-sided_default/TOSHIBA_ColorMFP_CUPS.tar
  tar -xf ${srcdir}/Color_Unix_Linux/CUPS/Usa/2-sided_default/TOSHIBA_ColorMFP_CUPS.tar
}

