# Created by: Olivier Duchateau
# $FreeBSD$

PORTNAME=	pantheon-calculator
PORTVERSION=	0.1.2
PORTREVISION=	1
CATEGORIES=	math
MASTER_SITES=	https://launchpadlibrarian.net/303135059/ \
	https://launchpad.net/${PORTNAME}/0.4-loki/${PORTVERSION}/+download/
DIST_SUBDIR=	pantheon

MAINTAINER=	ports@FreeBSD.org
COMMENT=	Simple calculator written in Vala

LICENSE=	GPLv3
LICENSE_FILE=	${WRKSRC}/COPYING

BUILD_DEPENDS=	valac:lang/vala
LIB_DEPENDS=	libgranite.so:x11-toolkits/granite \
		libgee-0.8.so:devel/libgee

USES=	cmake pkgconfig gettext tar:xz
USE_GNOME=	glib20 gtk30 cairo gdkpixbuf2 intltool

GLIB_SCHEMAS=	org.pantheon.calculator.gschema.xml

.include <bsd.port.mk>
