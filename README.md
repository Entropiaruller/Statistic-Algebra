# Statistic-Algebra
A collection of thoughts and a simple program in python for computational explorations

#.........................INTRODUCTION..........................................


#Statistic algebra is a collection of thoughts not a theory.
#It starts with the thought that maybe there are more than plus or minus signs.
#So which is the other one and how we call it...
#We have 6 we have -6 .Can we have and sth else?
#So let's say yes to that question and lets give some definitions.
#Statistic 6 is the number that we write like this 6^ and maybe is 6 or -6.
#Also maybe is 4 , -4 , 2 , -2 and of course zero...
#Why it can be equal to all this numbers?The definition will answer in a moment.
#n^ reading as statistic n is the set of numbers n^={-n,-n+2,-n+4,-n+8...,n}.
#So n^ is not exactly equal to anything is simple a set of numbers.
#This is the definition.
#But how we came there?
#Every statistic number n^ is the result of adding random 1 or -1 n times.
#You can think of it with an example for better understanding.
#Number 5 = 1 + 1 + 1 + 1 + 1 so we add 1 five times.What if we add -1
#in one of those steps? 5^ = _ + _ + _ + _ + _ statistic five can have 1 or -1
#in every step.The possibility in every step is exactly 1/2.
#Like a coin that has 1 in one side and -1 in the other.
#So is easy to see that 5^ = 5 with the possibility of 1/(2**5)
#And in general statistic n^ = n with the possibility of 1/(2**n)
#In those equalities the mathematical meaning is that n and -n belongs
#to the set n^ and the possibility is sth that has to do with our ideas
#with the way that the set n^ is constructed.
#Let's see again...n^ = -n because n times we have -1 with 1/2 possibility/step.
#But in fact every combination of 1 and -1 has this possibility.
#But there are combinations that gives the same numbers.
#This numbers is the members of the set n^={-n,-n+2,-n+4,....,n}
#So the possibility to have for example -n+4 is the sum of the possibilities
#of the different combinations of 1 and -1 that gives the same result -n+4.
#ANOTHER INTERESTING FACT IS THAT THE STATISTIC INFINITIVE IS EXACTLY ZERO...

#.............................Examples..........................................

#Lets see some examples now...
#1^= {1,-1} and of course each of this results have a connection with the
#number 1/2. So 1/2 possibility to have 1^=1 and 1/2 to have 1^=-1
#Now with the number 2^={2,0,-2} zero has a greater number that we construct
#with the way i describe and is bound to it...Lets call it possibility of
#existance from now on.The zero has 1/2...the 2 and -2, 1/4 each.
#With little writing and counting a patent appears...Nice thing of course.
#Is the pascal triangle...and every row of it is a exact copy of the other set
#that we want to find and relate to the n^...is the possibilities
#of every "result" of the statistic number if we divide them first with 1/(2**n)




#............................The program........................................
#This is a program that for a given number n will find the set
#n^={-n,-n+2,-n+4,-n+8...,n} and the possibilities of every member in the set.
#...............................................................................
