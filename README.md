# Movie-Star

1 Introduction 
This document explains moviestore.py python code. It gives the general description of all the methods used, how they work and the citations used. 
2 Classes  
[18] class Movie(object): 
      This class describes movies, it is a parent class. The __init__ () method is the class constructor, it initializes the object attributes; name, price and category 
 [26] class Customer(object) 
      This class describes movies, it is a parent class. The __init__ () method is the class constructor, it initializes the object attributes; name, idno, fines and movies_returned 
[36] class Storekeeper(object): 
      This class describes movies, it is a parent class. The __init__ () method is the class constructor, it initializes the object attributes; name, movies_lent and movies 
[44] class Loan(object): 
      This class describes movies, it is a parent class. The __init__ () method is the class constructor, it initializes the object attributes; number_of_days   
3 Methods 
[50] def enter_movie():  
 Does not return anything. This method allows the storekeeper add movies to the movie store. There are three categories of movies namely; new_release, children’s, and regular. When the store keeper enters 
 
Movie store Code Documentation  
2 
the movie name, and category. Using the category standard price, price of the movie is determined so there is no need for more data entry. Colored method from clint.textui is used to add color to printed output. 
[83] def enter_customer(): 
 This method does not return anything. It allows the storekeeper add new customers to the movie store. They enter the customer name and idno. 
[107] def rent_amovie (): 
 Here the store keeper checks the customer list to see if the customer exists. Then he/she checks the available movies to see if the one the customer wants is available. After renting the movie, movie is added to customer’s movie list and the movie removed from store and added to movies rented.  It prints the movies the customer has borrowed and their total charges. The method does not return anything 
[166] def return_amovie () 
        This method does not return anything. Here the store keeper checks the movies the customer has brought back to see if they are the ones they borrowed. Check if customer has a fine or not. It prints the movies the person has brought back and also their total charge in case they have a fine. 
[215] def exit_program (): 
 This method does nothing. 
4 Main Function (starts on line 218) 
4.1 Outline of methods used 
1. enter_movie 2. enter_customer 3. rent_amovie 4. return_amovie 5. exit_program 
5 Citations 
1. clint module 2. math class 
  
