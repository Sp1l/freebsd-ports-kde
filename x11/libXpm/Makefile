# Created by: Eric Anholt <anholt@FreeBSD.org>
# $FreeBSD$

PORTNAME=	libXpm
PORTVERSION=	3.5.12
PORTREVISION=	1
CATEGORIES=	x11

MAINTAINER=	x11@FreeBSD.org
COMMENT=	X Pixmap library

LICENSE=	MIT

XORG_CAT=	lib
USE_XORG=	xorgproto x11 xext xt
LDFLAGS+=	-L${LOCALBASE}/lib

OPTIONS_DEFINE=		NLS
NLS_USES=		gettext
NLS_CONFIGURE_ENV_OFF=	ac_cv_search_gettext=no

INSTALL_TARGET=	install-strip

.include <bsd.port.mk>
