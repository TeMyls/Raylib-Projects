CC = gcc
CFLAGS = -Wall -std=c99

SRC = main.c
OUT = raylib_demo.exe

# Update these paths to match your raylib install
RAYLIB_PATH = C:/raylib
INCLUDES = -I$(RAYLIB_PATH)/include
LIBS = -L$(RAYLIB_PATH)/lib -lraylib -lopengl32 -lgdi32 -lwinmm

all:
	$(CC) $(CFLAGS) $(SRC) -o $(OUT) $(INCLUDES) $(LIBS)

run: all
	./$(OUT)

clean:
	del $(OUT)
