/******************************************************************************
 * Copyright (C) 2017 by Walid Osama
 *
 * Redistribution, modification or use of this software in source or binary
 * forms is permitted as long as the files maintain this copyright. Users are 
 * permitted to modify this and use it to learn about the field of embedded
 * software. Alex Fosdick and the University of Colorado are not liable for any
 * misuse of this material. 
 *
 *****************************************************************************/
/**
* @author walid osama
* @brief makefile to automate the generation of bunch of files of different types easily
*  
* 
* go to /src folder where sorce files exist then you can simply run any of the supported rules 
* for the makefile ( build , compile-all , *.i , *.asm , *.o , clean)
* 
* clean : will remove all generated files , only leave makefile , *.mk , *.c
* 
* compile-all : will generate  *.o file for each *.c file
* 
* build : will generate *.o file for each *.c file ,c1m2.map , c1m2.out & *.d file for each 
*         source file , and it will give data about code size and memory allocation 
* 
* all the others will generate the required file with its extension from existing source files
*/
