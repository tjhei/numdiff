CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

PROJECT(numdiff)

SET(SRC
analyze.c
arith.c
cmpbuf.c
cmpfns.c
exitfail.c
flags.c
inout.c
io.c
linesplit.c
main.c
numutil.c
options.c
side.c
thrlist.c
util.c
xalloc-die.c
xmalloc.c
)

# other files:
# errors.c error.c getopt.c new.c setmode.c number.c



ADD_EXECUTABLE(numdiff ${SRC})
