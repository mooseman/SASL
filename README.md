SASL
====

A simple and educational compiler for the SASL programming language.



Examples of usage
=================

In the examples below, "$" is the command prompt. 


$ ./sasl  test.sasl  
                          ( Waiting for your input ) 
def plus x y = x+y.       ( Don't forget the .     )  
plus 5 7 ;                ( Don't forget the ;     ) 
12   
def fst a b = a.          ( Another function definition ) 
fst 23 45 ; 
23
12 + 23 ; 
35 
def third a b c = c. 
third 3 5 7 ; 
7  

^C                        ( Ctrl-C to exit ) 
$  




Acknowledgement and thanks
========================== 

Dan Piponi (sigfpe) is the author of the SASL compiler here. 

He has very generously said in reply to my comment [here](http://blog.sigfpe.com/2017/06/a-relaxation-technique.html#comments) that I can do what I like with his code, and is happy for it to be released as "public domain". 
Thank you very much for that, Dan! 


So, with that in mind, I release the code in this fork as "public domain".  



- mooseman 

 
    
