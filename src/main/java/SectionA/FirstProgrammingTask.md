 Section A – Simple Programming Task
    Describe an algorithm which sums all numbers from 1 to 1000000 both numbers
    inclusive in the simplest possible way.
   ------------------------------------------------------------------------------------------------------
   # Solution:
     To solve would be used an arithmetic progression formula for sum  of arithmetic sequence:
      n(a1 + an)/2 = 1000000(1+1000000)/2= 500000500000
      it would be more quick and simple then using loop and quicker then using recursion.
      Solution with Java is below:
   [src/main/java/SectionA/FirstProgrammingTask.java]
   -----------------------------------------------------------------------------------------------------
   [n is the number of terms]
   [a is the first term]
   [l is the Last term]
   1.Divide No. of term (n) with numerator by 2
       n/2= 1000000/2=500000 and store the value in variable say long M=500000
   2.Add the first term 'a' =1000000 and Last term 'l'=1
       a+l= 1000001 and store in variable say long S= 1000001
   3. Multiply variable long M and long S = M*S to get desire output = 500000*1000001=500,000,500,000 
   4.Print the result output.

 
