Download Link: https://assignmentchef.com/product/solved-lab-9-java-programming
<br>
1. Declare and implement a class named Pythagorean. The class will contain the following five methods:

getTriples(int n) prints all Pythagorean triples (a, b, c) such that a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>, 0 &lt; a ≤ b ≤ c ≤ n.

getQuadruples(int n) prints all Pythagorean quadruples (a, b, c, d) such that a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> = d<sup>2</sup>, 0 &lt; a ≤ b ≤ c ≤ d ≤ n.

getQuintuples(int n) prints all Pythagorean quintuples (a, b, c, d, e) such that a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> +d<sup>2</sup> = e<sup>2</sup>, 0 &lt; a ≤ b ≤ c ≤ d ≤ e ≤ n.

getHextuples(int n) prints all Pythagorean hextuples (a, b, c, d, e, f) such that a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> + d<sup>2</sup> + e<sup>2</sup> = f<sup>2</sup>, 0 &lt; a ≤ b ≤ c ≤ d ≤ e ≤ f ≤ n.

getSeptuples(int n) prints all Pythagorean septuples (a, b, c, d, e, f, g) such that a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> + d<sup>2</sup> + e<sup>2</sup> + f<sup>2</sup> = g<sup>2</sup>, 0 &lt; a ≤ b ≤ c ≤ d ≤ e ≤ f ≤ g ≤ n.

For example, for n = 10. These methods will print

triples:

3, 4, 5

6, 8, 10

quadruples:

1, 2, 2, 3

1, 4, 8, 9

2, 3, 6, 7

2, 4, 4, 6

3, 6, 6, 9

4, 4, 7, 9

quintuples:

1, 1, 1, 1, 2

1, 1, 3, 5, 6

1, 1, 7, 7, 10

1, 2, 2, 4, 5

1, 3, 3, 9, 10

1, 4, 4, 4, 7

1, 5, 5, 7, 10

2, 2, 2, 2, 4

2, 2, 3, 8, 9

2, 2, 4, 5, 7

2, 4, 4, 8, 10

2, 4, 5, 6, 9

3, 3, 3, 3, 6

4, 4, 4, 4, 8

5, 5, 5, 5, 10

hextuples:

1, 1, 1, 2, 3, 4

1, 1, 1, 4, 9, 10

1, 1, 1, 5, 6, 8

1, 1, 2, 3, 7, 8

1, 1, 3, 3, 4, 6

1, 1, 3, 5, 8, 10

1, 2, 2, 2, 6, 7

1, 2, 2, 6, 6, 9

1, 2, 3, 5, 5, 8

1, 3, 3, 3, 6, 8

1, 3, 4, 5, 7, 10

2, 2, 2, 2, 3, 5

2, 2, 2, 4, 6, 8

2, 2, 3, 4, 4, 7

2, 3, 4, 4, 6, 9

3, 3, 3, 3, 8, 10

3, 4, 5, 5, 5, 10

4, 4, 4, 4, 6, 10

septuples:

1, 1, 1, 1, 1, 2, 3

1, 1, 1, 1, 3, 6, 7

1, 1, 1, 1, 4, 4, 6

1, 1, 1, 2, 2, 5, 6

1, 1, 1, 2, 3, 3, 5

1, 1, 1, 2, 5, 7, 9

1, 1, 1, 3, 4, 6, 8

1, 1, 1, 5, 6, 6, 10

1, 1, 2, 2, 3, 9, 10

1, 1, 2, 3, 3, 5, 7

1, 1, 2, 3, 6, 7, 10

1, 1, 2, 5, 5, 5, 9

1, 1, 3, 3, 4, 8, 10

1, 1, 3, 3, 5, 6, 9

1, 2, 2, 2, 2, 8, 9

1, 2, 2, 3, 3, 3, 6

1, 2, 3, 3, 3, 7, 9

1, 2, 3, 3, 4, 5, 8

1, 2, 3, 5, 5, 6, 10

1, 3, 3, 3, 6, 6, 10

1, 3, 3, 4, 4, 7, 10

1, 4, 4, 4, 4, 4, 9

2, 2, 2, 2, 2, 4, 6

2, 2, 2, 2, 4, 7, 9

2, 2, 2, 4, 6, 6, 10

2, 2, 3, 3, 5, 7, 10

2, 2, 4, 4, 4, 5, 9

2, 3, 3, 3, 3, 3, 7

2, 3, 3, 3, 5, 5, 9

3, 3, 3, 3, 3, 6, 9

3, 3, 4, 4, 5, 5, 10

Value n must be read from the user in the main method.