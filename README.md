Start → Program begins. 

Initialize Variables → Store the values 10 in var1 and 15 in var2. 

Load Data → I move the value of var1 into the EAX register. 

Add Values → I add the value of var2 to EAX. 

Store Result → I save the sum in the result variable. 

Exit Program → I tell Linux the program is finished. 

End → Program closes. 

1.The biggest challenge was understanding the difference between initialized and uninitialized variables.  I wasn't sure why var1 and var2 belonged in the .data section while result had to go in the .bss section. I realized .data is for variables that already have values assigned, while .bss is for variables that get their value later when the program runs.  

2.Another problem I ran into was checking whether my program actually worked. Since the program doesn't print anything on the screen but you did say that would happen. So, after using GDB to inspect the result variable and verify that it stored the correct value of 25 it worked. 

 
