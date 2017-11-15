# Solution-of-equation

Solution of equation

Description

已知一个n元高次方程： 
 
其中：x1, x2,...,xn是未知数，k1,k2,...,kn是系数，p1,p2,...pn是指数。且方程中的所有数均为整数。 
假设未知数1 <= xi <= M, i=1,,,n，求这个方程的整数解的个数。 
1 <= n <= 6；1 <= M <= 150。 
 
方程的整数解的个数小于231。 
★本题中，指数Pi(i=1,2,...,n)均为正整数。 

Input

第1行包含一个整数n。第2行包含一个整数M。第3行到第n+2行，每行包含两个整数，分别表示ki和pi。两个整数之间用一个空格隔开。第3行的数据对应i=1，第n+2行的数据对应i=n。

Output

仅一行，包含一个整数，表示方程的整数解的个数。

Sample Input

3
150
1  2
-1  2
1  2

Sample Output

178
