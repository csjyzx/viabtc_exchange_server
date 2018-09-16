TARGET  := accessws.exe
INCS = -I ../depends -I ../network -I ../utils -I ../../librdkafka/src -I ../../jansson/src -I ../../curl-7.45.0/include
LIBS = -L ../libs -Wl,-Bstatic -L ../utils -lutils -L ../network -lnetwork -lev -lmpdec -ljansson -lrdkafka -lz -lssl -lhiredis -lcurl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
