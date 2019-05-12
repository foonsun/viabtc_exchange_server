TARGET  := alertcenter.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -lhiredis -ljansson -lmpdec -lcurl -lssl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl -lldap -lkrb5 -llber -lgss -lidn -lrtmp -lz
include ../makefile.inc
