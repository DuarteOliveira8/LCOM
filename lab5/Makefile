# Makefile for lab4

COMPILER_TYPE= gnu

CC= gcc

PROG= lab5
SRCS= lab5.c test5.c vbe.c video_gr.c video_test.c timer.c keyboard.c read_xpm.c sprite.c

CFLAGS= -Wall 

DPADD+= ${LIBDRIVER} ${LIBSYS}
LDADD+= -ldriver -lsys -llm

LDFLAGS+= -L .

MAN=

.include <bsd.prog.mk>
.include <bsd.gcc.mk>
