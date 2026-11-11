CXX = g++
CXXFLAGS = -Wall -Wextra -std=c++17

SRC = Kazino-Royal.cpp
TARGET = Kazino-Royal
TARGET_DEBUG = Kazino-Royal-dbg

all: $(TARGET) $(TARGET_DEBUG)

$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -O2 -o $(TARGET) $(SRC)

$(TARGET_DEBUG): $(SRC)
	$(CXX) $(CXXFLAGS) -g -o $(TARGET_DEBUG) $(SRC)

clean:
	rm -f $(TARGET) $(TARGET_DEBUG) *.o

.PHONY: all clean
