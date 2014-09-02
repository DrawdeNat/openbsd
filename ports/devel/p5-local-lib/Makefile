# $OpenBSD$

COMMENT =		create and use a local lib/ for perl modules with PERL5LIB

MODULES =		cpan
CPAN_AUTHOR =		HAARG
DISTNAME =		local-lib-2.000012
CATEGORIES =		devel

MAINTAINER =		Edward <edward@rdtan.net>

# perl
PERMIT_PACKAGE_CDROM =	Yes

MODCPAN_EXAMPLES =	Yes
MODCPAN_EXAMPLES_DIST=  eg

post-install:
	${MODCPAN_POST_INSTALL}
	${INSTALL_DATA_DIR} ${PREFIX}/share/doc/local-lib
	${INSTALL_DATA} ${WRKSRC}/{README,Changes} ${PREFIX}/share/doc/local-lib/

.include <bsd.port.mk>
