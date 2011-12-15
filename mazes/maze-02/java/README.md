Running the Program
=================== 

First compile the Driver.java file using "javac".

To run the maze with default settings:
<pre>
> java Driver 
</pre>

To run the maze with custom width and height:
<pre>
> java Driver -w20 -h25
</pre>

To run the maze with a preset seed, to model deterministic behavior:
<pre>
> java Driver -s100
</pre>

To run the maze in animation mode (<-- COOL):
<pre>
> java Driver -a
</pre>

To run the maze with a custom animation delay:
<pre>
> java Driver -a -d0.1
</pre>