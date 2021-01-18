# Test the test-rgb-syntax.svg by using "example2" to convert it to "svg.png",
# and then load it in gimp to compare color columns. Also, compare gimp to e.g. firefox
# to compare the two results side by side.
#
test: example2
	./example2 test-rgb-syntax.svg && gimp svg.png

# Build the example2 program
example2: example2.c ../src/nanosvg.h
	g++ -I../src example2.c -o example2

clean: FORCE
	rm example2

FORCE:

