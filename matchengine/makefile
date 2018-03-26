TARGET  := matchengine.exe
INCS = -I ../network -I ../utils -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-Bstatic -lutils -lnetwork -lhiredis -ljansson -lrdkafka -lev -lmpdec -lmysqlclient -lz -lssl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
