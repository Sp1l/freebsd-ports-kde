# Created by: Johannes Jost Meixner <johannes@perceivon.net>
# $FreeBSD$

PORTNAME=	adal
DISTVERSION=	1.0.2
CATEGORIES=	net-mgmt python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Authentication ot Azure Active Directory for python apps

LICENSE=	MIT

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}cryptography>=1.1.0:security/py-cryptography@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}dateutil>=2.1.0:devel/py-dateutil@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pyjwt>=1.0.0:www/py-pyjwt@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=2.0.0:www/py-requests@${PY_FLAVOR}

NO_ARCH=	yes
USES=		python
USE_PYTHON=	autoplist concurrent distutils

.include <bsd.port.mk>
