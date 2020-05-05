SRC := $(wildcard *.c)

OBJ := ${SRC:.c=.o}

TARGET := espresso

all: $(TARGET)

$(TARGET): $(OBJ)
	$(LINK.c) $(OBJ) -o $(TARGET)

clean: 
	@- $(RM) $(TARGET)
	@- $(RM) $(OBJ)

