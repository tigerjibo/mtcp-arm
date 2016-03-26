### GCC ###
#GCC = gcc
GCC = /root/open-estuary/toolchain/gcc-linaro-aarch64-linux-gnu-4.9-2014.09_linux/bin/aarch64-linux-gnu-gcc # edit by Tong SHEN
#GCC_OPT = -m64 -Wall -fPIC -c
GCC_OPT = -Wall -fPIC -c # edit by Tong SHEN
GCC_OPT += -DNDEBUG -O3 -DNETSTAT -DINFO -DDBGERR -DDBGCERR


### LIBRARIES AND INCLUDES ###
CFLAGS = -I./include/


### COMPILE ###
all:
	${GCC} ${GCC_OPT} ${CFLAGS} tdate_parse.c   # edit by Tong SHEN
	${GCC} ${GCC_OPT} ${CFLAGS} http_parsing.c  # edit by Tong SHEN

clean:
	rm -rf *~ *.o

