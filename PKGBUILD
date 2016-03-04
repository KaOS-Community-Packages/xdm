pkgname=xdm
pkgver=5.0.47
pkgrel=1
pkgdesc="Powerful tool to increase Download Speed & Video Grabber that works with integration to ANY browser."
url="http://xdman.sourceforge.net/"
arch=('x86_64')
license=('custom')
depends=('ffmpeg')
source=("http://ufpr.dl.sourceforge.net/project/xdman/xdm-jre-64bit.tar.xz"
        "xdm.desktop")
md5sums=('00096f8c8a50f93c9f4d02687474e9b0'
         '56856f3bcabab58afc3ab6270164da5e')

package() {
    install -d -m 755 "${pkgdir}/opt"
    cp -r xdm "${pkgdir}/opt/"
    install -Dm644 xdm.desktop "$pkgdir/usr/share/applications/xdm.desktop"
} 
