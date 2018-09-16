TARGET  := marketprice.exe
INCS = -I ../depends -I ../network -I ../utils -I ../../curl-7.45.0/include -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-Bstatic -lutils -lnetwork -lhiredis -ljansson -lrdkafka -lcurl -lev -lmpdec -lz -lssl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
