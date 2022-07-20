# STACKS:

For those who don't know, stacks are bundles of software that comprise your site's back end and everything from the operating system and web servers to APIs and programming frameworks.They follow the Last In, First Out principle which is also known as LIFO.




![geek-stack-1](https://user-images.githubusercontent.com/92330348/178790973-dd1186ea-50bb-4ef3-adae-8c1b8ec445e4.png)




We use stacks because they enables all data to operate at one end only, so the only element that can be removed is the element at the top of the stack, and only one item can be read or removed at a given time.



![stack-660x345](https://user-images.githubusercontent.com/92330348/178791568-695cf41d-2100-4b35-9a01-61c5c41b458d.png)




Stacks are faster due to the access pattern which makes it important to allocate and deallocate memory from a pointer.


Stacks have two basic operations which are push and pop.

. Push: Push adds an element to the collection.
  
  An example: 
  
       begin
       if stack is full
          return
       endif
      else  
       increment top
       stack[top] assign value
      end else
      end procedure

. Pop: Pop removes the most recently added element that was not yet removed.

  An example:
  
        begin procedure pop:
        
          if stack is empty
              return null
          endif
          
          data <- stack[top]
          top <- top - 1
          return data
      end procedure
      
      


 # Implementing a stack:

So with a static array, the first element of the array, which is located at position 0,0, will be the bottom of the stack.  The stack will have a fixed capacity, which means that if you continuously add items to the stack, it will result in a stack overflow. This is why static implementations must include an is_full() operation to check whether a stack is at its maximum capacity.

This pseudocode shows how an array to service a stack with space for 10 elements could be initialised.


                              MAX_SIZE = 10  // Uses a constant

                              ARRAY stack[MAX_SIZE]
                              top = -1
                              
                              
                              

# Stack problem:

For my stack problem I will be designing a stack that supports push and pop and retrieves the element in constant time.



[stack solution.py](stack solution.py)









                              
      
 - [0-welcome.md](0-welcome.md)
