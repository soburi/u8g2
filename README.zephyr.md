Changes at zephyr porting
=========================

## Remove license incompatible fonts

### Font lists

| Filename | License | Distribution origin |
|----------|---------|---------------------|
| tools/font/bdf/10x20.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/4x6.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/5x7.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/5x8.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x10.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x12.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x13.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x13B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x13O.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/6x9.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/7_Seg_33x19.bdf | public domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/7_Seg_41x21.bdf | public domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/7Segments_26x42.bdf | public domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/7x13.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/7x13B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/7x13O.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/7x14.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/7x14B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/8x13.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/8x13B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/8x13O.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/9x15.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/9x15B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/9x18.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/9x18B.bdf | public doamin | [https://gitlab.freedesktop.org/xorg/font/misc-misc](https://gitlab.freedesktop.org/xorg/font/misc-misc) |
| tools/font/bdf/ArtosSans-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/ArtosSerif-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/b10.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b10_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b12.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b12_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b14.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b14_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b16.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/b16_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/CalBlk36.bdf | mit | [https://github.com/thegeek82000/openGLCD](https://github.com/thegeek82000/openGLCD) |
| tools/font/bdf/CalLite24.bdf | mit | [https://github.com/thegeek82000/openGLCD](https://github.com/thegeek82000/openGLCD) |
| tools/font/bdf/Chroma48Medium-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/courB08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courB10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courB12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courB14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courB18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courB24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/courR24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/cu12.bdf | mit | [https://gitlab.freedesktop.org/xorg/font/mutt-misc](https://gitlab.freedesktop.org/xorg/font/mutt-misc) |
| tools/font/bdf/cursor.bdf | adobe-x11 | [https://gitlab.freedesktop.org/xorg/font/mutt-misc/](https://gitlab.freedesktop.org/xorg/font/mutt-misc) |
| tools/font/bdf/emoticons21.bdf | public domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/etl14-thai.bdf | public doamin | [https://github.com/tlwg/thaixfonts/](https://github.com/tlwg/thaixfonts/) |
| tools/font/bdf/etl16-thai.bdf | public doamin | [https://github.com/tlwg/thaixfonts/](https://github.com/tlwg/thaixfonts/) |
| tools/font/bdf/etl24-thai.bdf | public doamin | [https://github.com/tlwg/thaixfonts/](https://github.com/tlwg/thaixfonts/) |
| tools/font/bdf/f10.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f10_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f12.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f12_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f14.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f14_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f16.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/f16_b.bdf | bsd-new | [http://openlab.ring.gr.jp/efont/unicode/](http://openlab.ring.gr.jp/efont/unicode/) |
| tools/font/bdf/freedoomr10r.bdf | ofl-1.1 | convert from [https://fontlibrary.org/en/font/freeuniversal](https://fontlibrary.org/en/font/freeuniversal) |
| tools/font/bdf/freedoomr25n.bdf | ofl-1.1 | convert from [https://fontlibrary.org/en/font/freeuniversal](https://fontlibrary.org/en/font/freeuniversal) |
| tools/font/bdf/gb16st.bdf | historical | [https://gitlab.freedesktop.org/xorg/font/isas-misc](https://gitlab.freedesktop.org/xorg/font/isas-misc) |
| tools/font/bdf/gb24st.bdf | historical | [https://gitlab.freedesktop.org/xorg/font/isas-misc](https://gitlab.freedesktop.org/xorg/font/isas-misc) |
| tools/font/bdf/helvB08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB08_gps.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvB24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/helvR24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/lubB08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubB24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubBI24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubI24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBIS24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/lubR24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luBS24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luIS24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS08.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS10.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS12.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS14.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS18.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS19.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/luRS24.bdf | other-permissive | [https://gitlab.freedesktop.org/xorg/font/bh-100dpi ](https://gitlab.freedesktop.org/xorg/font/bh-100dpi ) |
| tools/font/bdf/m2icon_5.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/m2icon_7.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/m2icon_9.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/micro.bdf | public-domain | [https://gitlab.freedesktop.org/xorg/font/micro-misc](https://gitlab.freedesktop.org/xorg/font/micro-misc) |
| tools/font/bdf/ncenB08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenB10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenB12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenB14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenB18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenB24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/ncenR24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/open_iconic_all_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_all_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_all_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_all_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_all_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_app_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_app_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_app_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_app_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_app_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_arrow_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_arrow_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_arrow_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_arrow_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_arrow_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_check_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_check_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_check_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_check_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_check_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_email_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_email_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_email_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_email_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_email_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_embedded_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_embedded_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_embedded_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_embedded_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_embedded_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_gui_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_gui_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_gui_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_gui_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_gui_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_human_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_human_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_human_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_human_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_human_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_mime_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_mime_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_mime_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_mime_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_mime_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_other_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_other_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_other_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_other_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_other_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_play_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_play_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_play_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_play_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_play_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_text_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_text_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_text_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_text_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_text_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_thing_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_thing_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_thing_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_thing_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_thing_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_weather_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_weather_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_weather_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_weather_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_weather_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_www_1x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_www_2x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_www_4x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_www_6x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/open_iconic_www_8x.bdf | ofl-1.1 | [https://github.com/iconic/open-iconic](https://github.com/iconic/open-iconic) |
| tools/font/bdf/profont10.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont11.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont12.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont15.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont17.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont22.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/profont29.bdf | mit | [https://tobiasjung.name/profont/](https://tobiasjung.name/profont/) |
| tools/font/bdf/SaikyoSansBold-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/spleen-12x24.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/spleen-16x32.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/spleen-32x64.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/spleen-5x8.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/spleen-6x12.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/spleen-8x16.bdf | bsd-simplified | [https://github.com/fcambus/spleen](https://github.com/fcambus/spleen) |
| tools/font/bdf/symb08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/symb10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/symb12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/symb14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/symb18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/symb24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/t0-11b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-11-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-12b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-12-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-13b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-13-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-14b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-14-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-15b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-15-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-16b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-16-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-17b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-17-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-18b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-18-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-22b-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/t0-22-uni.bdf | ttyp0 | [https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/](https://people.mpi-inf.mpg.de/~uwe/misc/uw-ttyp0/) |
| tools/font/bdf/timB08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timB10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timB12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timB14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timB18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timB24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR08.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR10.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR12.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR14.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR18.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/timR24.bdf | x11-adobe-dec | [https://gitlab.freedesktop.org/xorg/font/adobe-75dpi](https://gitlab.freedesktop.org/xorg/font/adobe-75dpi) |
| tools/font/bdf/tom-thumb.bdf | mit | [https://github.com/apparentlymart/led-matrix-fonts](https://github.com/apparentlymart/led-matrix-fonts) |
| tools/font/bdf/TorusSansBold-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/u8g2_squeezed_bold_6.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/u8g2_squeezed_bold_7.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/u8g2_squeezed_regular_6.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/u8g2_squeezed_regular_7.bdf | public-domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/u8glib_4.bdf | public domain | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/VictoriaBold-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/VictoriaMedium-8.bdf | cc0-1.0 | [http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux](http://opengameart.org/content/a-package-of-8-bit-fonts-for-grafx2-and-linux) |
| tools/font/bdf/win_crox1c.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox1cb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox1h.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox1hb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox1t.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox1tb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2c.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2cb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2h.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2hb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2t.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox2tb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3c.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3cb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3h.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3hb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3t.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox3tb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox4h.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox4hb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox4t.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox4tb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox5h.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox5hb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox5t.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/bdf/win_crox5tb.bdf | other-permissive | [http://www.kovrik.com/sib/russify/x-windows/#win-fonts](http://www.kovrik.com/sib/russify/x-windows/#win-fonts) |
| tools/font/ttf/12x6LED.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3960](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3960) |
| tools/font/ttf/3x5.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7785](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7785) |
| tools/font/ttf/8bitClassic.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6076](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6076) |
| tools/font/ttf/9x6LED.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3980](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3980) |
| tools/font/ttf/BBSesque.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=670](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=670) |
| tools/font/ttf/Beanstalk.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=158](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=158) |
| tools/font/ttf/BitCasual.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=353](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=353) |
| tools/font/ttf/BitTypeWriter.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1455](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1455) |
| tools/font/ttf/Born2bSportySlab.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1084](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1084) |
| tools/font/ttf/Born2bSportyV2.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=383](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=383) |
| tools/font/ttf/botmaker.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9968](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9968) |
| tools/font/ttf/BracketedBabies.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=70](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=70) |
| tools/font/ttf/ByteSize.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4843](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4843) |
| tools/font/ttf/CelibateMonk.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=911](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=911) |
| tools/font/ttf/Ciircle13.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3904](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3904) |
| tools/font/ttf/Cube.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=152](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=152) |
| tools/font/ttf/CupcakeMeToYourLeader.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1047](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1047) |
| tools/font/ttf/CursivePixel.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=858](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=858) |
| tools/font/ttf/DiodeSemiMono.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1133](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1133) |
| tools/font/ttf/DisrespectfulTeenager.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=918](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=918) |
| tools/font/ttf/DoomAlpha04.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6915](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6915) |
| tools/font/ttf/EfraneExtraCondensed.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10166](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10166) |
| tools/font/ttf/Elispe.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6161](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6161) |
| tools/font/ttf/Engrish.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=369](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=369) |
| tools/font/ttf/eventhrees.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9842](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9842) |
| tools/font/ttf/Fewture.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=409](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=409) |
| tools/font/ttf/fivepx.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5504](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5504) |
| tools/font/ttf/FreeUniversal-Bold.ttf | ofl-1.1 | [https://fontlibrary.org/en/font/freeuniversal](https://fontlibrary.org/en/font/freeuniversal) |
| tools/font/ttf/FreeUniversal-Regular.ttf | ofl-1.1 | [https://fontlibrary.org/en/font/freeuniversal](https://fontlibrary.org/en/font/freeuniversal) |
| tools/font/ttf/Frikativ.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=550](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=550) |
| tools/font/ttf/GanjNamehSans-Regular.ttf | ofl-1.1 | [https://github.com/font-store/GanjnamehFont/](https://github.com/font-store/GanjnamehFont/) |
| tools/font/ttf/GarbageCan.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6188](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6188) |
| tools/font/ttf/Georgia7px.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1451](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1451) |
| tools/font/ttf/GreenBloodSerif2.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5359](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5359) |
| tools/font/ttf/HabsburgChancery.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=803](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=803) |
| tools/font/ttf/Halftone.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=434](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=434) |
| tools/font/ttf/HEAVYBOTTOM.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2348](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2348) |
| tools/font/ttf/HeiSans.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9029](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9029) |
| tools/font/ttf/HelvetiPixel.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=381](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=381) |
| tools/font/ttf/HelvetiPixelOutline.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=182](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=182) |
| tools/font/ttf/ImpactBits.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=846](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=846) |
| tools/font/ttf/inb.otf | ofl-1.1 | [https://fontlibrary.org/en/font/inconsolata-lgc](https://fontlibrary.org/en/font/inconsolata-lgc) |
| tools/font/ttf/inr.otf | ofl-1.1 | [https://fontlibrary.org/en/font/inconsolata-lgc](https://fontlibrary.org/en/font/inconsolata-lgc) |
| tools/font/ttf/Kibibyte.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6597](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6597) |
| tools/font/ttf/Koleeko.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=748](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=748) |
| tools/font/ttf/LikeMinecraft.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10128](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10128) |
| tools/font/ttf/LittleMissLoudonBold.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5650](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5650) |
| tools/font/ttf/Mademoiselle.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=129](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=129) |
| tools/font/ttf/m-c-kids-nes-credits-font.ttf | cc0-1.0 | [https://fontstruct.com/fontstructions/show/1963150/m-c-kids-nes-credits-font](https://fontstruct.com/fontstructions/show/1963150/m-c-kids-nes-credits-font) |
| tools/font/ttf/MedSans.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8938](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8938) |
| tools/font/ttf/MichaelMouse.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=913](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=913) |
| tools/font/ttf/MicroPixel.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9254](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9254) |
| tools/font/ttf/Mildras.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8262](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8262) |
| tools/font/ttf/Minicute.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8792](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8792) |
| tools/font/ttf/MinuteConsole.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3370](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3370) |
| tools/font/ttf/MissingPlanet.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3730](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3730) |
| tools/font/ttf/MooseNooks.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2095](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2095) |
| tools/font/ttf/mystery-quest.regular.ttf | ofl-1.1 | [https://fonts.google.com/specimen/Mystery+Quest](https://fonts.google.com/specimen/Mystery+Quest) |
| tools/font/ttf/Nerhoe.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=410](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=410) |
| tools/font/ttf/NEW3x9PixelFont.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5134](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5134) |
| tools/font/ttf/NokiaLargeBold.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6180](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6180) |
| tools/font/ttf/NokiaSmallBold.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6182](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6182) |
| tools/font/ttf/NokiaSmallPlain.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6181](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6181) |
| tools/font/ttf/OldStandard-Bold.ttf | ofl-1.1 | [https://fontlibrary.org/en/font/old-standard](https://fontlibrary.org/en/font/old-standard) |
| tools/font/ttf/OldStandard-Regular.ttf | ofl-1.1 | [https://fontlibrary.org/en/font/old-standard](https://fontlibrary.org/en/font/old-standard) |
| tools/font/ttf/OldWizard.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=168](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=168) |
| tools/font/ttf/OrdinaryBasis.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=804](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=804) |
| tools/font/ttf/OriginalSans.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7464](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7464) |
| tools/font/ttf/Oskool.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=411](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=411) |
| tools/font/ttf/PieceOfCake.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=165](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=165) |
| tools/font/ttf/PixelMordred.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=735](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=735) |
| tools/font/ttf/PixelTheatre.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1267](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1267) |
| tools/font/ttf/PixzillaV1.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4728](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4728) |
| tools/font/ttf/Press.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=156](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=156) |
| tools/font/ttf/PressStart2P.ttf | ofl-1.1 | [https://zone38.net/font/](https://zone38.net/font/) |
| tools/font/ttf/Questgiver.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=947](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=947) |
| tools/font/ttf/RePress.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=159](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=159) |
| tools/font/ttf/ResoledBold.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9016](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9016) |
| tools/font/ttf/ResoledMedium.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9015](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9015) |
| tools/font/ttf/Samim.ttf | ofl-1.1 | [https://github.com/rastikerdar/samim-font/](https://github.com/rastikerdar/samim-font/) |
| tools/font/ttf/Samim-FD.ttf | ofl-1.1 | [https://github.com/rastikerdar/samim-font/](https://github.com/rastikerdar/samim-font/) |
| tools/font/ttf/SandyForest.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=899](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=899) |
| tools/font/ttf/Scrum.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5304](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5304) |
| tools/font/ttf/SecretaryHand.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1066](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1066) |
| tools/font/ttf/Seraphimb1.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=946](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=946) |
| tools/font/ttf/SirClive.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2051](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2051) |
| tools/font/ttf/SirClivetheBold.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2058](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2058) |
| tools/font/ttf/SisterSerif.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8570](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8570) |
| tools/font/ttf/SmallSimple.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10152](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10152) |
| tools/font/ttf/smolFont.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9959](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9959) |
| tools/font/ttf/Squirrel.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2229](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2229) |
| tools/font/ttf/Standardized3x5.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9866](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9866) |
| tools/font/ttf/Sticker.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=167](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=167) |
| tools/font/ttf/Sticker100Complete.ttf | public domain | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2618](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2618) |
| tools/font/ttf/StylishCharm.ttf | public domain | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8520](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8520) |
| tools/font/ttf/Tallpix.ttf | public domain | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=235](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=235) |
| tools/font/ttf/TallPixelExtended.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1608](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1608) |
| tools/font/ttf/TenFatGuys.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=332](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=332) |
| tools/font/ttf/TenStamps.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=329](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=329) |
| tools/font/ttf/TenThinGuys.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=335](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=335) |
| tools/font/ttf/TenThinnerGuys.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=338](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=338) |
| tools/font/ttf/ThreePix.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9693](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9693) |
| tools/font/ttf/TimesNewPixel.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=57](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=57) |
| tools/font/ttf/tinyByGK.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10108](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10108) |
| tools/font/ttf/tinyBySimon.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9731](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9731) |
| tools/font/ttf/TinyFace.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7473](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=7473) |
| tools/font/ttf/TinyPixie2.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5554](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5554) |
| tools/font/ttf/TinyTim.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=450](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=450) |
| tools/font/ttf/TooseOrnament.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=461](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=461) |
| tools/font/ttf/TwelveDings.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=330](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=330) |
| tools/font/ttf/UnnamedDOSFontIV.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6171](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6171) |
| tools/font/ttf/Untitled16PixelSansSerifBitmapTestFont.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3046](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3046) |
| tools/font/ttf/Wedge.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3950](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3950) |
| tools/font/ttf/Wizzard.ttf | public doamin | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=902](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=902) |

### Removed Fonts

| Filename | License | Distribution origin |
|----------|---------|---------------------|
| tools/font/bdf/amstrad_cpc_extended.bdf | cc-by-sa | convert from [https://fontstruct.com/fontstructions/show/25590/amstrad_cpc_extended](https://fontstruct.com/fontstructions/show/25590/amstrad_cpc_extended) |
| tools/font/bdf/battery19.bdf | Undeterminable  | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/battery24.bdf | Undeterminable  | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/cursorr.bdf | Undeterminable  |  |
| tools/font/bdf/siji.bdf | gpl-2.0 | [https://github.com/stark/siji](https://github.com/stark/siji) |
| tools/font/bdf/u8g2_percent_circle_25.bdf | Undeterminable  | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/u8x8extra.bdf | Undeterminable  | [https://github.com/olikraus/u8g2](https://github.com/olikraus/u8g2) |
| tools/font/bdf/unifont_upper.bdf | gpl-2.0 | [https://unifoundry.com/unifont/index.html](https://unifoundry.com/unifont/index.html) |
| tools/font/bdf/waffle-10.bdf | gpl-3.0 | [https://github.com/addy-dclxvi/bitmap-font-collections](https://github.com/addy-dclxvi/bitmap-font-collections) |
| tools/font/ttf/04B_03__.TTF | other license | [http://www.04.jp.org/](http://www.04.jp.org/) |
| tools/font/ttf/04B_03B_.TTF | other license | [http://www.04.jp.org/](http://www.04.jp.org/) |
| tools/font/ttf/3x3Basic.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4043](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4043) |
| tools/font/ttf/Abel.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8975](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8975) |
| tools/font/ttf/Adventurer.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=195](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=195) |
| tools/font/ttf/astra0.ttf | cc-by-sa-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/astragal-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/astragal-nbp) |
| tools/font/ttf/baby.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/baby_4](http://fontstruct.com/fontstructions/show/baby_4) |
| tools/font/ttf/BALRG_0.ttf | cc-by-sa-3.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/balthasar-regular-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/balthasar-regular-nbp) |
| tools/font/ttf/BALTT_0.ttf | cc-by-sa | [https://www.fontspace.com/balthasar-regular-nbp-font-f15434](https://www.fontspace.com/balthasar-regular-nbp-font-f15434) |
| tools/font/ttf/Bauhaus2015.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2048](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2048) |
| tools/font/ttf/blipfest_07.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/blipfest_07](http://fontstruct.com/fontstructions/show/blipfest_07) |
| tools/font/ttf/BPixel.ttf | Undeterminable  |  |
| tools/font/ttf/BPixelDouble.ttf | Undeterminable  |  |
| tools/font/ttf/bubble.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/1533797/bubble-100](https://fontstruct.com/fontstructions/show/1533797/bubble-100) |
| tools/font/ttf/BusDisplay11x5.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3789](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3789) |
| tools/font/ttf/BusDisplay8x5.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3790](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3790) |
| tools/font/ttf/CALIBRATE1.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/calibration-gothic-nbp-latin](https://www.fontspace.com/total-fontgeek-dtf-ltd/calibration-gothic-nbp-latin) |
| tools/font/ttf/cardimon-pixel.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/1266554/cardimon-pixel](https://fontstruct.com/fontstructions/show/1266554/cardimon-pixel) |
| tools/font/ttf/chargen-92.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/1599418/chargen-92-1](https://fontstruct.com/fontstructions/show/1599418/chargen-92-1) |
| tools/font/ttf/chikita.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/chikita](http://fontstruct.com/fontstructions/show/chikita) |
| tools/font/ttf/Commodore64.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5612](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5612) |
| tools/font/ttf/CosmonazisSerif.ttf | Undeterminable  |  |
| tools/font/ttf/DigitalDisco.ttf | cc-by-sa-4.0 | [https://www.dafont.com/digital-disco.font](https://www.dafont.com/digital-disco.font) |
| tools/font/ttf/DigitalDisco-Thin.ttf | cc-by-sa-4.0 | [https://www.dafont.com/digital-disco.font](https://www.dafont.com/digital-disco.font) |
| tools/font/ttf/Dystopia.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1293](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1293) |
| tools/font/ttf/Eckpixel.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5879](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5879) |
| tools/font/ttf/FancyPixels.ttf | cc-by-nc | [https//www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3287](https//www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3287) |
| tools/font/ttf/FindersKeepers.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3809](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3809) |
| tools/font/ttf/Fourmat.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2092](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=2092) |
| tools/font/ttf/Frigidaire.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9013](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=9013) |
| tools/font/ttf/glasstown_nbp.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/glasstown-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/glasstown-nbp) |
| tools/font/ttf/GUILD_0.ttf | cc-by-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/rosencrantz-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/rosencrantz-nbp) |
| tools/font/ttf/haxrcorp4089.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/192981/haxrcorp_4089](https://fontstruct.com/fontstructions/show/192981/haxrcorp_4089) |
| tools/font/ttf/IconQuadPix.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=244](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=244) |
| tools/font/ttf/IPAandRUSLCD.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=355](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=355) |
| tools/font/ttf/IranianSansRegular.ttf | gpl-3.0 | [https://github.com/nekofar/iranian-sans-fontface](https://github.com/nekofar/iranian-sans-fontface) |
| tools/font/ttf/JinxedWizards.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1362](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1362) |
| tools/font/ttf/LastApprenticeBold.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1323](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1323) |
| tools/font/ttf/LastApprenticeThin.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1324](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1324) |
| tools/font/ttf/LastPriestess.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=488](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=488) |
| tools/font/ttf/Logisoso.ttf | gpl-3.0 | [https://openfontlibrary.org/de/font/logisoso](https://openfontlibrary.org/de/font/logisoso) |
| tools/font/ttf/Lord.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8978](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=8978) |
| tools/font/ttf/lucasarts-scumm-subtitle-roman.ttf | cc-by-nc-3.0 | [https://fontstruct.com/fontstructions/show/786126/lucasarts-scumm-subtitle-roman](https://fontstruct.com/fontstructions/show/786126/lucasarts-scumm-subtitle-roman) |
| tools/font/ttf/lucasarts-scumm-subtitle-roman-outline.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/786126/lucasarts-scumm-subtitle-roman-outline](https://fontstruct.com/fontstructions/show/786126/lucasarts-scumm-subtitle-roman-outline) |
| tools/font/ttf/lucasfont_alternate.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/lucasfont_alternate](http://fontstruct.com/fontstructions/show/lucasfont_alternate) |
| tools/font/ttf/Magdalena.ttf | Undeterminable  |  |
| tools/font/ttf/MagdalenaBold.ttf | Undeterminable  |  |
| tools/font/ttf/maniac.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/604350/maniac_2](https://fontstruct.com/fontstructions/show/604350/maniac_2) |
| tools/font/ttf/mercutio_basic.ttf | cc-by-sa-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/mercutio-nbp-basic](https://www.fontspace.com/total-fontgeek-dtf-ltd/mercutio-nbp-basic) |
| tools/font/ttf/mercutio_sc.ttf | cc-by-sa-4.0 | [https://www.fontspace.com/mercutio-nbp-basic-font-f15814](https://www.fontspace.com/mercutio-nbp-basic-font-f15814) |
| tools/font/ttf/MIRANDA.ttf | cc-by-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/miranda-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/miranda-nbp) |
| tools/font/ttf/MOZART_0.ttf | cc-by-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/mozart-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/mozart-nbp) |
| tools/font/ttf/Neuecraft.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6206](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=6206) |
| tools/font/ttf/nine0.ttf | cc-by-sa-3.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/nine-by-five-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/nine-by-five-nbp) |
| tools/font/ttf/nokiafc22.ttf | other license | [https://www.dafont.com/nokia-cellphone.font](https://www.dafont.com/nokia-cellphone.font) |
| tools/font/ttf/p01type.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/p01type](http://fontstruct.com/fontstructions/show/p01type) |
| tools/font/ttf/pcsenior.ttf | other license | [https://zone38.net/font/](https://zone38.net/font/) |
| tools/font/ttf/pearfont.ttf | other license | [https://www.dafont.com/pearfont.font](https://www.dafont.com/pearfont.font) |
| tools/font/ttf/Pixellari.ttf | other license | [https://www.dafont.com/pixellari.font](https://www.dafont.com/pixellari.font) |
| tools/font/ttf/pixelle_micro.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/pixelle_micro](http://fontstruct.com/fontstructions/show/pixelle_micro) |
| tools/font/ttf/pixelpoiiz.ttf | other license | [https://www.dafont.com/pixelpoiiz.font](https://www.dafont.com/pixelpoiiz.font) |
| tools/font/ttf/Princess.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1294](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=1294) |
| tools/font/ttf/prospero_bold_nbp.ttf | cc-by-sa | [https://www.fontspace.com/prospero-nbp-font-f15256](https://www.fontspace.com/prospero-nbp-font-f15256) |
| tools/font/ttf/prospero_nbp.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/prospero-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/prospero-nbp) |
| tools/font/ttf/Px437_Wyse700a.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/Px437_Wyse700b.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/PxClassic.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3715](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3715) |
| tools/font/ttf/PxPlus_IBM_CGA.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/PxPlus_IBM_CGAthin.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/PxPlus_IBM_VGA8.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/PxPlus_IBM_VGA9.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/PxPlus_TandyNew_TV.ttf | cc-by-sa-4.0 | [https://int10h.org/oldschool-pc-fonts/](https://int10h.org/oldschool-pc-fonts/) |
| tools/font/ttf/RENT_0.ttf | cc-by-4.0 | [https://www.fontspace.com/total-fontgeek-dtf-ltd/roentgen-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/roentgen-nbp) |
| tools/font/ttf/robot_de_niro.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/robot_de_niro_2](http://fontstruct.com/fontstructions/show/robot_de_niro_2) |
| tools/font/ttf/ROSEN_0.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/rosencrantz-nb](https://www.fontspace.com/total-fontgeek-dtf-ltd/rosencrantz-nb) |
| tools/font/ttf/shylock_nbp.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/shylock-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/shylock-nbp) |
| tools/font/ttf/Simple1.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10169](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=10169) |
| tools/font/ttf/smart_patrol_nbp.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/smart-patrol-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/smart-patrol-nbp) |
| tools/font/ttf/SonicMania.ttf | cc-by-nc | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4905](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=4905) |
| tools/font/ttf/synchronizer_nbp.ttf | cc-by-sa | [https://www.fontspace.com/total-fontgeek-dtf-ltd/synchronizer-nbp](https://www.fontspace.com/total-fontgeek-dtf-ltd/synchronizer-nbp) |
| tools/font/ttf/TEACPSS_.TTF | Undeterminable  |  |
| tools/font/ttf/TEACPSSB.TTF | Undeterminable  |  |
| tools/font/ttf/Terminal.ttf | other license | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5556](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=5556) |
| tools/font/ttf/TinyUnicode.ttf | cc-by-sa | [https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=468](https://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=468) |
| tools/font/ttf/trixel_square.ttf | cc-by-sa-3.0 | [http://fontstruct.com/fontstructions/show/trixel_square_1](http://fontstruct.com/fontstructions/show/trixel_square_1) |
| tools/font/ttf/unifont_upper.ttf | gpl-2.0-plus | [https://unifoundry.com/unifont/index.html](https://unifoundry.com/unifont/index.html) |
| tools/font/ttf/utopia24.ttf | cc-by-sa-3.0 | [https://fontstruct.com/fontstructions/show/1963904/utopia24](https://fontstruct.com/fontstructions/show/1963904/utopia24) |
| tools/font/ttf/VCR_OSD_MONO_1.001.ttf | other license | [https://www.dafont.com/vcr-osd-mono.font](https://www.dafont.com/vcr-osd-mono.font) |

