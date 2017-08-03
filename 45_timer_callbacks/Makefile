#OBJS specifies which files to compile as part of the project
OBJS = 45_timer_callbacks.cpp

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
COMPILER_FLAGS = -w

#LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer

CXXFLAGS=-g -std=c++11 -Wall -pedantic

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = 45_timer_callbacksx

#This is the target that compiles our executable
all : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) $(CXXFLAGS) -o $(OBJ_NAME)