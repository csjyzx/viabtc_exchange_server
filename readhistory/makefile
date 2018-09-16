TARGET  := readhistory.exe
INCS = -I ../depends -I ../network -I ../utils -I ../../jansson/src -I ../../librdkafka/src
LIBS = -L ../libs -Wl,-Bstatic -lutils -lnetwork -ljansson -lhiredis -lev -lmpdec -lmysqlclient -lz -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
