# $FreeBSD$

PORTNAME=	libusb1
PORTVERSION?=	1.6.6
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	jbeich@FreeBSD.org
COMMENT=	Pure-python wrapper for libusb-1.0

LICENSE=	LGPL21+

CONFLICTS_INSTALL?=	${PKGNAMEPREFIX}${PORTNAME}15

NO_ARCH=	yes
USES=		python
USE_PYTHON=	autoplist distutils

do-test:
		@${PYTHON_CMD} -m unittest discover -vs ${TEST_WRKSRC}

.include <bsd.port.mk>
