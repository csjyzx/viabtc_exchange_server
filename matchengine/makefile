TARGET  := matchengine.exe
INCS = -I ../depends -I ../network -I ../utils -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-zmuldefs,-Bstatic -lutils -lnetwork -ljansson -lev -lmpdec -lmysqlclient -lrdkafka -lz -lssl -lcrypto -lhiredis -lcurl -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
