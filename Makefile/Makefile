
CXX     := g++
CXXFLAGS:= -Wall -O2
TARGET  := main
SRC     := main.cpp

all: $(TARGET)
       $(TARGET): $(SRC)
       $(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC)

run: $(TARGET)
       ./$(TARGET)

clean:
       rm -f $(TARGET)