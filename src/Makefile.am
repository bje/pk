AM_CFLAGS = -std=c99 -D_XOPEN_SOURCE=700 -D_BSD_SOURCE -D_GNU_SOURCE \
            -Werror -Wall -Wextra -Wwrite-strings -Winit-self -Wcast-align \
            -Wcast-qual -Wpointer-arith -Wstrict-aliasing -Wformat=2 \
            -Wuninitialized -Wmissing-declarations -Wno-long-long \
            -Wno-unused-parameter -Wno-missing-field-initializers

bin_PROGRAMS = pk

pk_SOURCES = configuration.c fieldprinter.c helpers.c main.c stringlist.c \
                 tokenizer.c wrappers.c

noinst_HEADERS = configuration.h fieldprinter.h helpers.h stringlist.h \
                 tokenizer.h wrappers.h
