# Created by: ijliao
# $FreeBSD$

PORTNAME=	Perl-Critic
PORTVERSION=	1.132
CATEGORIES=	textproc devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	perl@FreeBSD.org
COMMENT=	Critique Perl source for style and standards

LICENSE=	ART10 GPLv1+
LICENSE_COMB=	dual
LICENSE_FILE=	${WRKSRC}/LICENSE

BUILD_DEPENDS=	p5-B-Keywords>=1.05:devel/p5-B-Keywords \
		p5-Config-Tiny>=2:devel/p5-Config-Tiny \
		p5-Exception-Class>=1.23:devel/p5-Exception-Class \
		p5-File-HomeDir>=0:devel/p5-File-HomeDir \
		p5-File-Which>=0:sysutils/p5-File-Which \
		p5-IO-String>=0:devel/p5-IO-String \
		p5-List-MoreUtils>=0.19:lang/p5-List-MoreUtils \
		p5-Module-Pluggable>=0:devel/p5-Module-Pluggable \
		p5-Pod-Spell>=1:textproc/p5-Pod-Spell \
		p5-PPI>=1.220:textproc/p5-PPI \
		p5-PPIx-QuoteLike>=0:textproc/p5-PPIx-QuoteLike \
		p5-PPIx-Regexp>=0.027:textproc/p5-PPIx-Regexp \
		p5-PPIx-Utilities>=1.001:textproc/p5-PPIx-Utilities \
		p5-Readonly>=2.00:devel/p5-Readonly \
		p5-String-Format>=1.13:textproc/p5-String-Format \
		p5-Task-Weaken>=0:devel/p5-Task-Weaken \
		perltidy:devel/p5-Perl-Tidy
RUN_DEPENDS:=	${BUILD_DEPENDS}
TEST_DEPENDS=	p5-Test-Deep>=0:devel/p5-Test-Deep \
		p5-Test-Memory-Cycle>=0:devel/p5-Test-Memory-Cycle

NO_ARCH=	yes
USES=		perl5
USE_PERL5=	modbuild

.include <bsd.port.mk>
