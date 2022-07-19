# SET:

A set is a data structure that can store any number of unique values in any order you so wish. They are different from arrays in the sense that they only allow non-repeated, unique values within them.

![sets computer science](https://user-images.githubusercontent.com/92330348/178794848-e80d16c8-3e95-4516-b703-bb43d6cfad71.png)


They are used to store multiple items in a single variable. They can also be used to carry out mathematical set operations like union, intersection, difference and symmetric difference. Sets are mostly faster than lists because sets have been implemented using hash tables. So basically Python does not have to search the full set, which means that the time complexity in average is O(1).
                    


<img width="545" alt="Hasing-Python" src="https://user-images.githubusercontent.com/92330348/178795122-f3f36c8b-0307-4f71-a68d-ff70974355f2.png">


Some sets use hashes to store elements. A Hash is basically an algorithm that takes an element and converts it to a chunk of fixed size called a hash.

![hashing 101](https://user-images.githubusercontent.com/92330348/179078047-7a5dbc41-dcc1-422d-b178-2b1d1c0783b5.png)





There are different types of set operations like set-union and set-intersection.



. Set-union: A set-union is the union of two sets is the set of all the elements of both the sets without duplicates.

  An example:
                                                                                                                                                                                
                                                                                                                                                                                # Set union method
                      # initialize A and B
                      A = {1, 2, 3, 4, 5}
                      B = {4, 5, 6, 7, 8}
                      # use | operator
                      # Output: {1, 2, 3, 4, 5, 6, 7, 8}
                      print(A | B)                                                                                                                                                                  


          
. Set-intersection: A set-intersection is the intersection of two sets is the set of all the common elements of both the sets.

An Example of a set is:

                   thisset = {"apple", "banana", "cherry"}

                    print(len(thisset))
                    
  
 # Implementing a SET:
 
 Sets can be implemented using various data structures, which provide different time and space trade-offs for various operations. Some implementations are designed to improve the efficiency of very specialized operations, such as nearest or union. A simple implementation is to use a list, ignoring the order of the elements and taking care to avoid repeated values. This is simple but inefficient, as operations like set membership or element deletion are O(n), as they require scanning the entire list.
 
 An example would be: 
 
             my %elements = map { $_ => 1 } @elements;

                    
                    
                            
  
 - [0-welcome.md](0-welcome.md)
