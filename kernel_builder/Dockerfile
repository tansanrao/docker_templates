FROM ubuntu:jammy

ARG DEBIAN_FRONTEND=noninteractive

# Install Build Dependencies
RUN set -x \
	    && apt-get update && apt-get upgrade -y \
	    && apt-get install -y --no-install-recommends \
	    autoconf automake autopoint autotools-dev bsdmainutils debhelper dh-autoreconf git fakeroot\
	    dh-strip-nondeterminism distro-info-data dwz file gettext gettext-base groff-base \
	    intltool-debian libarchive-zip-perl libbsd0 libdebhelper-perl libelf1 libexpat1 \
	    libfile-stripnondeterminism-perl libglib2.0-0 libicu-dev libmagic-mgc libmagic1 libmpdec3 \
	    libpipeline1 libpython3.11-stdlib libpython3.11-minimal libsigsegv2 \
	    libssl3 libsub-override-perl libtool libuchardet0 libxml2 \
	    lsb-release m4 man-db mime-support po-debconf python-apt-common python3-apt \
	    python3.11 python3.11-minimal sbsigntool tzdata dctrl-tools kernel-wedge \
	    libncurses-dev gawk flex bison openssl libssl-dev dkms libelf-dev libudev-dev libpci-dev \
	    libiberty-dev autoconf bc build-essential libusb-1.0-0-dev libhidapi-dev curl wget \
	    cpio makedumpfile libcap-dev libnewt-dev libdw-dev rsync gnupg2 ca-certificates\
	    libunwind8-dev liblzma-dev libaudit-dev uuid-dev libnuma-dev lz4 xmlto equivs \
	    cmake pkg-config zstd dwarves devscripts python3-docutils asciidoc \
	    bindgen-0.56 rust-1.62-src
