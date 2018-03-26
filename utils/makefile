TARGET  := libutils.a
INCS = -I ../network -I ../../jansson/src -I ../../librdkafka/src
include ../makefile.inc
$(TARGET) : $(OBJS)
	ar -rs $@ $^
