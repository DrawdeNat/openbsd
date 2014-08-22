# $OpenBSD$

COMMENT =		get, unpack, build and install modules from CPAN

MODULES =		cpan
CPAN_AUTHOR =		MIYAGAWA
DISTNAME =		App-cpanminus-1.7004
CATEGORIES =		devel

MAINTAINER =		Edward <edward@rdtan.net>

# The Artistic License 1.0
PERMIT_PACKAGE_CDROM =	Yes

post-install:
	${INSTALL_DATA_DIR} ${PREFIX}/share/doc/App-cpanminus
	${INSTALL_DATA} ${WRKSRC}/{README,Changes,LICENSE} ${PREFIX}/share/doc/App-cpanminus/

.include <bsd.port.mk>
