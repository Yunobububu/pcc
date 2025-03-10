# pcc
python crash course

conda create -n pcc python=3.11

conda activate pcc

conda install jupyter 

jupyter notebook

git add <file>
git commit -m 'description message'
git push

chapter04

1.understand how to slice a list [1,:] [:,4]
2.copy a list using slice: [:]
3.work throught a list using a for loop
4.PEP 8,the style guide. 
    4.1 no more than 79 characters each line.
    4.2 don't abuse the blank line.
    4.3 don't place more than two lines between two sections

chapter05 if statements

use if-elif-else chain 
element in or not in a list
if list 
    return True is more than one element in the list
    
chapter06 dictionaries

1.dictionary contains key-valus pairs using {}
2.using dict.keys() to find all keys. dict.values() to get all values.
3.using  key, value in dict.items() to get key-value pairs.
4.dict['key'] to get the value
5.dict['newKey'] = newValue to add the new key-value pair.
6.del dict['key'] to remove.

chapter07 while loops
1. use input() function to allow users to provide information
2. use while loops to run until when you want to end.
3. use flag to end while loop
4. use break to end while loop
5. use while loop with list,dictionary.

chapter08 functions

1. def function_name(arguement):
       """docstrings"""
       return

   def function_name(arguement0,arguement1='default'):
       """function with default value"""
       return
    
   def function_name(arguement, *kwg):
       """functions with unkonwn arguements"""
       return

   def function_name(arguement,**kwg):
       """functions with unknows key-value pairs"""
       return 

2. module
   import module_name as mn

   from moudule_name import func_name as fn

   from module_name import *





