Python 2 vs. Python 3
Some of you may be familiar with Python 2. You should thrive in this class since the differences between Python 2 and Python 3 are quite modest. To aid you in this transitions, here are the highlights of these differences. For more detailed information, you can review the official "What's New in Python" page at python.org.

Here is quick summary of some of the more important changes:

In Python 2, integer division (i.e. \color{red}{\verb|4 / 3|}4/3 returns the integer \color{red}{\verb|1|}1) . In Python 3, the same expression returns floating pointing number \color{red}{\verb|1.333333333333|}1.333333333333 .
In Python 2, printing to the console has the syntax \color{red}{\verb| print "Hello world"|}print"Helloworld". In Python 3, print is a function and has the syntax \color{red}{\verb| print( "Hello world" )|}print("Helloworld").
In Python 2, the methods \color{red}{\verb|math.ceil()|}math.ceil() and \color{red}{\verb|math.floor()|}math.floor() return floats. In Python 3, these methods return ints.
The built-in \color{red}{\verb| __next__()|}__next__() method for iterators in Python 2 has been renamed to \color{red}{\verb|next()|}next() in Python 3.
The type \color{red}{\verb|long|}long in Python 2 for long integers has be subsumed into the type \color{red}{\verb|int|}int in Python 3.
In Python 2, \color{red}{\verb| range()|}range() , \color{red}{\verb| map()|}map() , \color{red}{\verb|zip()|}zip() , and \color{red}{\verb|filter()|}filter() return lists. In Python 3, these functions return generator-type objects. (Note that CodeSkulptor3 still returns list while it is being upgraded.)
Here are some further external sources that further discuss these differences:

The key differences between Python 2.7.x and Python 3.x with examples
Python 2 vs. Python 3 language differences and workarounds
Porting Code to Python 3 with 2to3
