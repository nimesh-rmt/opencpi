
from ubuntu:20.04

# LABEL about the custom image
LABEL maintainer="nimesh"
LABEL version="0.1"
LABEL description="opencpi attempt"

# Disable Prompt During Packages Installation
ARG DEBIAN_FRONTEND=noninteractive

RUN apt update

RUN apt install -y acl adwaita-icon-theme alien aspell aspell-en at-spi2-core autopoint autotools-dev binutils-aarch64-linux-gnu binutils-common build-essential ca-certificates-java cmake-data colord colord-data cpp cpp-9 cups-bsd cups-client cups-common cups-filters cups-filters-core-drivers cups-ipp-utils debhelper debugedit dh-autoreconf dh-strip-nondeterminism dictionaries-common dpkg-dev dwz emacsen-common fontconfig fontconfig-config fonts-dejavu-core fonts-dejavu-extra fonts-droid-fallback fonts-noto-mono fonts-urw-base35 g++-9 gcc gcc-9 gcc-9-base gettext ghostscript gtk-update-icon-cache guile-2.2-libs hicolor-icon-theme humanity-icon-theme hunspell-en-us intltool-debian java-common keyutils libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl libarchive-cpio-perl libarchive-zip-perl libasan5 libaspell15 libasyncns0 libatk-bridge2.0-0 libatk-wrapper-java libatk-wrapper-java-jni libatk1.0-0 libatk1.0-data libatomic1 libatspi2.0-0 libavahi-client3 libavahi-common-data libavahi-common3 libbinutils libc-dev-bin libcairo-gobject2 libcairo2 libcc1-0 libcolord2 libcolorhug2 libcroco3 libcrypt-dev libctf-nobfd0 libctf0 libcups2 libcupsfilters1 libcupsimage2 libdatrie1 libdebhelper-perl libdpkg-perl libdrm-amdgpu1 libdrm-nouveau2 libdrm-radeon1 libdw1 libenchant-2-2 libexif12 libfakeroot libfile-fcntllock-perl libfile-stripnondeterminism-perl libfl-dev libflac8 libfontconfig1 libfontembed1 libfontenc1 libgail-common libgail18 libgc1c2 libgcc-9-dev libgd3 libgdk-pixbuf2.0-0 libgdk-pixbuf2.0-bin libgdk-pixbuf2.0-common libgif7 libgl1 libgl1-mesa-dri libgl1-mesa-glx libglapi-mesa libglvnd0 libglx-mesa0 libglx0 libgomp1 libgphoto2-6 libgphoto2-l10n libgphoto2-port12 libgraphite2-3 libgs9 libgs9-common libgsasl7 libgtk2.0-0 libgtk2.0-bin libgtk2.0-common libharfbuzz0b libhunspell-1.7-0 libidn11 libieee1284-3 libijs-0.35 libisl22 libitm1 libjbig0 libjbig2dec0 libjpeg-turbo8 libjpeg62 libjpeg8 libjsoncpp1 libkyotocabinet16v5 liblcms2-2 libllvm12 liblouis-data liblouis20 liblouisutdml-bin liblouisutdml-data liblouisutdml9 liblsan0 libltdl-dev liblua5.2-0 libmail-sendmail-perl libmailutils6 libmpc3 libmysqlclient21 libncurses5 libnfsidmap2 libntlm0 libopenjp2-7 libpango-1.0-0 libpangocairo-1.0-0 libpangoft2-1.0-0 libpaper-utils libpaper1 libpcre2-posix2 libpcsclite1 libpixman-1-0 libpoppler-cpp0v5 libpoppler97 libpulse0 libqpdf26 librhash0 librpm8 librpmbuild8 librpmio8 librpmsign8 librsvg2-2 librsvg2-common libsane libsane-common libsensors-config libsensors5 libsndfile1 libsnmp-base libsnmp35 libstdc++-9-dev libsub-override-perl libsys-hostname-long-perl libtcl8.6 libthai-data libthai0 libtiff5 libtinfo5 libtirpc-common libtirpc3 libtsan0 libubsan1 libusb-0.1-4 libvorbisenc2 libvulkan1 libwayland-client0 libwebp6 libx11-xcb1 libxaw7 libxcb-dri2-0 libxcb-dri3-0 libxcb-glx0 libxcb-present0 libxcb-randr0 libxcb-render0 libxcb-shape0 libxcb-shm0 libxcb-sync1 libxcb-xfixes0 libxcomposite1 libxcursor1 libxdamage1 libxfixes3 libxft2 libxi6 libxinerama1 libxkbfile1 libxpm4 libxrandr2 libxrender1 libxshmfence1 libxtst6 libxv1 libxxf86dga1 libxxf86vm1 linux-libc-dev lsb-core lsb-invalid-mta lsb-printing lsb-security m4 mailutils mailutils-common manpages-dev mesa-vulkan-drivers mysql-common pax po-debconf poppler-data poppler-utils rpcbind rpm-common rpm2cpio sane-utils sgml-base sgml-data tcl-expect tcl8.6 ubuntu-mono update-inetd x11-utils xml-core \
    blt fonts-lyx javascript-common libauthen-sasl-perl libblas3 libdata-dump-perl libexpat1-dev libfdt1 libfile-listing-perl libfont-afm-perl libgfortran5 libhtml-form-perl libhtml-format-perl libhtml-tree-perl libhttp-cookies-perl libhttp-daemon-perl libhttp-negotiate-perl libimagequant0 libio-socket-ssl-perl libjs-jquery libjs-jquery-ui liblapack3 liblbfgsb0 liblwp-protocol-https-perl libmailtools-perl libnet-http-perl libnet-smtp-ssl-perl libnet-ssleay-perl libpython3-dev libpython3.8-dev libtext-unidecode-perl libtk8.6 libtry-tiny-perl libwebpdemux2 libwebpmux3 libwww-perl libwww-robotrules-perl libxml-libxml-perl libxml-namespacesupport-perl libxml-parser-perl libxml-sax-base-perl libxml-sax-expat-perl libxml-sax-perl libxss1 perl-openssl-defaults python-matplotlib-data python-pip-whl python3-cycler python3-dateutil python3-decorator python3-kiwisolver python3-olefile python3-pil python3-pyparsing python3-tk python3.8-dev python3.8-venv swig4.0 tex-common tk8.6-blt2.5 ttf-bitstream-vera

# Optional packages and clean up
RUN apt install -y git sudo neovim 


RUN cd /opt &&\
    git clone https://gitlab.com/opencpi/opencpi.git

COPY ubuntu20_04-packages.sh /opt/opencpi/projects/core/rcc/platforms/ubuntu20_04/
RUN cd /opt/opencpi &&\
    rm -rf projects/platform/prerequisites/xvcd

RUN cd /opt/opencpi &&\
    scripts/install-opencpi.sh

RUN rm -rf /var/lib/apt/lists/* && \
    apt clean
