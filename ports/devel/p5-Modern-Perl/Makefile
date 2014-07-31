# $OpenBSD$

COMMENT =		enable all of the features of Modern Perl with one import

MODULES =		cpan
CPAN_AUTHOR =		CHROMATIC
DISTNAME =		Modern-Perl-1.20140107
CATEGORIES =		devel

MAINTAINER =		Edward <edward@rdtan.net>

# The Artistic License 1.0
PERMIT_PACKAGE_CDROM =	Yes

post-install:
	@mkdir -p ${PREFIX}/share/doc/${DISTNAME}
	${INSTALL_DATA} ${WRKDIST}/README ${PREFIX}/share/doc/${DISTNAME}/
	${INSTALL_DATA} ${WRKDIST}/Changes ${PREFIX}/share/doc/${DISTNAME}/
	${INSTALL_DATA} ${WRKDIST}/LICENSE ${PREFIX}/share/doc/${DISTNAME}/

.include <bsd.port.mk>
