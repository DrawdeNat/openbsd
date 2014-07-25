# $OpenBSD$

COMMENT =		get, unpack, build and install modules from CPAN

MODULES =		cpan
CPAN_AUTHOR =		MIYAGAWA
DISTNAME =		App-cpanminus-1.7004
CATEGORIES =		devel

MAINTAINER =		Edward <myself@rdtan.net>

# The Artistic License 1.0
PERMIT_PACKAGE_CDROM =	Yes

post-install:
	@mkdir -p ${PREFIX}/share/doc/${DISTNAME}
	${INSTALL_DATA} ${WRKDIST}/README ${PREFIX}/share/doc/${DISTNAME}/
	${INSTALL_DATA} ${WRKDIST}/Changes ${PREFIX}/share/doc/${DISTNAME}/
	${INSTALL_DATA} ${WRKDIST}/LICENSE ${PREFIX}/share/doc/${DISTNAME}/

.include <bsd.port.mk>
