TARGET  := alertcenter.exe
INCS = -I ../network -I ../utils -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-Bstatic -lutils -lnetwork -lhiredis -ljansson -lcurl -lev -lmpdec -lssl -lcrypto -Wl,-Bdynamic -lm
include ../makefile.inc
