#	@(#)Makefile	8.1 (Berkeley) 6/6/93
# $FreeBSD$

MAN=

.include <bsd.own.mk>

PROG=	uudecode
LINKS=	${BINDIR}/uudecode ${BINDIR}/b64decode

.if ${MK_TESTS} != "no"
SUBDIR+= tests
.endif

.include <bsd.prog.mk>
