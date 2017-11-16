# Eeny-Meeny

Eeny Meeny

Description

In darkest < name of continent/island deleted to prevent offence > lived a tribe called the ``Eeny Meenys''. They got this name from their way of choosing a chief for a year. It appears that a newspaper reporter visited the tribe and managed to get across a few ideas of civilisation, but apparently came to an unfortunate end before finishing the job. Thus the tribe no longer had a permanent chief; the chief's term was exactly one year. At the end of that time, they ate the current chief, and chose another chief. Their method of choosing a chief was the ``Eeny meeny miny mo'' method. All eligible tribal members (women were also eligible--one of the blessings of civilisation the tribe had adopted) stood in a circle, a starting place was chosen, and the chief medicine man (who was ineligible for chieftainship) went around counting out `E', `e', `n', `y', `M', `e', `e', `n', `y', `M',`i', `n', `y', `M', `o!', `E', `e', `n', `y', `M', `e', `e', `n', `y', `M', `i', `n', `y', `M', `o!', .... At every `o!', the person indicated was pushed out of the circle which then closed up and the count restarted with his neighbour (the one who would have been `E' anyway). This process continued until only one was left--the new chief.


While the chance of glory for a year makes the job of chief highly attractive to tribal members, you (possessing a computer decades before they were invented) find the brevity of the glory unappealing. You have managed to find out that the count this year will start with Mxgobgwq (a very large person), so you would like to know where not to stand. You don't know the direction, nor how many eligible people there are, but you can estimate the number (it is certainly less than 500).


Write a program that will determine the `first' (i.e. closest to Mxgobgwq) safe position to stand, regardless of the actual number of people and the direction of count (clockwise or anti-clockwise).

Input

Input will consist of a series of lines, each line containing the upper and lower estimates of the number of eligible people (both numbers inclusive). The file will be terminated by a line containing two zeroes (0 0).

Output

Output will consist of a series of lines, one for each line of the input. Each line will consist of a single number giving the number of the position closest to Mxgobgwq that will not be chosen as chief for any number in the given range and for either direction of elimination. If no position is safe then print "Better estimate needed".

Sample Input

80 150
40 150
0 0

Sample Output

1
Better estimate needed
