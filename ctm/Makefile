# ----------------------------------------------------------------------------
# "THE BEER-WARE LICENSE" (Revision 42):
# <phk@FreeBSD.org> wrote this file.  As long as you retain this notice you
# can do whatever you want with this stuff. If we meet some day, and you think
# this stuff is worth it, you can buy me a beer in return.   Poul-Henning Kamp
# ----------------------------------------------------------------------------
#
# $FreeBSD$

PROG=	ctm
SRCS=  	ctm.c ctm_input.c ctm_pass1.c ctm_pass2.c ctm_pass3.c \
	ctm_passb.c ctm_syntax.c ctm_ed.c

LDADD=	-l md

WARNS?=	2

.include <bsd.prog.mk>
