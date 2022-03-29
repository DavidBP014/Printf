Printf
first c language project, create a function that prints special characters

Flow Chart


<img width="501" alt="Captura de Pantalla 2022-03-28 a la(s) 8 00 51 p m" src="https://user-images.githubusercontent.com/91141739/160511573-c1668dcc-44c2-43e1-aa07-a8973756793e.png">

Objective.
Write your own printf function

Description.
       %c: Prints the character passed as parameter.

       %s: Prints text string finished with null character.

       %d: Converts argument to signed decimal notation and print it.

       %i:  Converts  argument  to unsigned decimal notation and print it.

       %% Prints a single '%' character

       %b Convert the unsigned argument to a binary and print it.

        %u Prints the integer unsigned decimal conversion.

       Examples:
       1:) _printf("Let's try to printf a simple sentence.\n");
       Let's try to printf a simple sentence.
       
       2:) _printf("Length:[%d, %i]\n", len, len);
       Length:[39, 39]
       
       3:) _printf("Negative:[%d]\n", -762534);
       Negative:[-762534]
       
       4:) _printf("Unsigned:[%u]\n", ui);
       Unsigned:[2147484671]

Compilations:
      Your code will be compiled this way:

      $ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

      and execute it with the command 
      ./a.out

SYNOPSYS

    Print ARGUMENT(s) according to FORMAT.


    Interpreted sequences are:


     %c:
     Prints the character passed as parameter.

     %s:
     Prints text string finished with null character.

     %d:
     Converts argument to signed decimal notation and print it.

     %i:
     Converts argument to unsigned decimal notation and print it.

     %%
     Prints a single '%' character

     %b
     Convert the unsigned argument to a binary and print it.

     %u
     Prints the integer unsigned decimal conversion.

     %o
     prints the integer unsigned octal conversion.

     %x
     Unsigned hexadecimal conversion in lowercase form.

     %X
     Unsigned hexadecimal conversion uppercase  form. 

     %r
     prints the reversed string.

     %R
     print a string in Rot 13.
 AUTHOR(S)
        Juan Ballesteros.
        Johanna Rodriguez.
