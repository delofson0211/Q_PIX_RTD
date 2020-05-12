INCDIR = $(QpixDir)/include
LIBDIR = $(QpixDir)/Library

# Compiler flags
CXXFLAGS = -std=c++11 -Wall -Wextra -Wno-long-long \
	-O3 -fno-common  \
	-I$(INCDIR)

LDFLAGS = -L$(LIBDIR) -lQpix

test Example01: Example01.cc 
	$(CXX) Example01.cc -o Example01 $(CXXFLAGS) $(LDFLAGS)




