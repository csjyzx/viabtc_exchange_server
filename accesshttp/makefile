TARGET  := accesshttp.exe
INCS = -I ../depends -I ../network -I ../utils -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-Bstatic -lutils -lnetwork -lhiredis -lev -ljansson -lmpdec -lrdkafka -lz -lssl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
