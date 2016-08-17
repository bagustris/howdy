# howdy
Hello world in many languages

1. Bash

  Installation

  - None, bash is always installed in the default image, but just in case.

        $ sudo apt install -y bash

  Code: bash/howdy.sh

        #!/bin/sh
        echo "    ====> Shell: Howdy, Windows!”

  Compilation
  
    - None, bash is an interpreted language

  Execution

        $ chmod +x ./bash/howdy.sh
        $ ./bash/howdy.sh 

   ====> Shell: Howdy, Windows!

2. Python

  Installation

    - None, python is always installed in the default image, but just in case…

        $ sudo apt install -y python

    Code: python/howdy.py

        #!/usr/bin/python
        print("    ====> Python: Howdy, Windows!")

  Compilation

    - None, python is an interpreted language

  Execution

        $ chmod +x ./python/howdy.py
        $ ./python/howdy.py 

   ====> Python: Howdy, Windows!

3. Perl

    Installation

        $ sudo apt install -y perl

  Code: perl/howdy.pl

        #!/usr/bin/perl
        print("    ====> Perl: Howdy, Windows!\n");

  Compilation

    - None, Perl is an interpreted language

  Execution

        $ chmod +x ./perl/howdy.pl
        $ ./perl/howdy.pl 

   ====> Perl: Howdy, Windows!

4. Ruby

    Installation

        $ sudo apt install -y ruby

    Code: ruby/howdy.rb
  
        #!/usr/bin/ruby
        puts "    ====> Ruby: Howdy, Windows!"

    Compilation

      - None, Ruby is an interpreted language

    Execution

        $ chmod +x ./ruby/howdy.rb
        $ ./ruby/howdy.rb 

   ====> Ruby: Howdy, Windows!

5. PHP

    Installation

        $ sudo apt install -y php5-cli

    Code: php/howdy.php

        #!/usr/bin/php
        <?php
        print("    ===> PHP: Howdy, Windows!\n")
        ?>

    Compilation

    - None, PHP is an interpreted language

    Execution

        $ chmod +x ./php/howdy.php
        $ ./php/howdy.php 

   ===> PHP: Howdy, Windows!

6. Node.js

    Installation

        $ sudo apt install -y nodejs

    Code: nodejs/howdy.js

        console.log('    ====> NodeJS: Howdy, Windows!');

    Compilation

    - None, Node.js is an interpreted language

    Execution

        $ nodejs nodejs//howdy.js 
   ====> NodeJS: Howdy, Windows!


6. C

    Installation

     $ sudo apt install -y gcc

  Code: c/howdy.c

      #include <stdio.h>
      int main() {
      printf("    ====> C: Howdy, Windows!\n");
      return 0;
      }

  Compilation

       $ gcc -o c/howdy c/howdy.c

  Execution

       $ ./c/howdy

   ====> C: Howdy, Windows!

7. C++

  Installation

       $ sudo apt install -y g++

  Code: cpp/howdy.cpp

       #include <iostream>
       int main() {
       std::cout << "    ====> C++: Howdy, Windows!\n";
       }

  Compilation

       $ g++ -o cpp/howdy cpp/howdy.cpp

  Execution

        $ ./cpp/howdy

   ====> C++: Howdy, Windows!

8. Golang

  Installation

       $ sudo apt install -y golang

  Code: golang/howdy.go

         package main
         import "fmt"
         func main() {
         fmt.Printf("    
         ====> Golang: Howdy, Windows!\n")
         }

  Compilation

       $ go build -o golang/howdy golang/howdy.go

  Execution

        $ ./golang/howdy

   ====> Golang: Howdy, Windows!

9. Fortran

  Installation

       $ sudo apt install -y gfortran

  Code: fortran/howdy.f90

         program howdy
         print *, "    ====> Fortran: Howdy, Windows!"
         end program howdy

  Compilation

         $ gfortran fortran/howdy.f90 -o fortran/howdy

  Execution

        $ ./fortran/howdy

  ====> Fortran: Howdy, Windows!

10. Pascal

  Installation

         $ sudo apt install -y fp-compiler

  Code: pascal/howdy.pas

         program Howdy;
         Begin
         writeln('    ====> Pascal: Howdy, Windows!');
         end.

  Compilation

         $ pc pascal/howdy.pas
  
    Execution
        $ ./pascal/howdy

   ====> Pascal: Howdy, Windows!

11. Erlang

  Installation

       $ sudo apt install -y erlang-base

  Code: erlang/howdy.erl

        -module(howdy).
        -export([howdy/0]).
        howdy() -> io:fwrite("    ====> Erlang: Howdy, Windows!\n").
  
  Compilation

       $ erlc erlang/howdy.erl

  Execution

        $ erl -noshell -s howdy howdy -s init stop

   ====> Erlang: Howdy, Windows!
