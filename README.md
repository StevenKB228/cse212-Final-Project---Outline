# cse212-Final-Project---Outline
Hey guys, I am Steven Balibuno and welcome to my Programming with data structures final outline tutorial. Here I will be talking about things programmers should know or learn about like stacks, Set, and Tree.

1. Stack:

Stacks are bundles of software that comprise your site's back end and everything from the operating system and web servers to APIs and programming frameworks. Stacks follow the Last In, First Out principle which is also known as LIFO. We use stacks because they enables all data to operate at one end only. So the only element that can be removed is the element at the top of the stack, and only one item can be read or removed at a given time. Stacks are faster due to the access pattern which makes it important to allocate and deallocate memory from a pointer.

Stacks have two basic operations which are push and pop. Push adds an element to the collection and Pop removes the most recently added element that was not yet removed.
      
Example 1.
    
     begin
    if stack is full
       return
      endif
    else  
      increment top
      stack[top] assign value
     end else
     end procedure                            Example 2.

                                                         class DoublyLinkedList
                                                             attr_accessor :head, :tail, :length
                                                             
                                                             def initialize()
                                                                @head = nil
                                                                @tail = nil

                                                                @length = 0
                                                              end
                                                              
2. Set

A set is an abstract data type that will store an unordered collection of unique values. They are used to store multiple items in a single variable. They can be also be used to carry out mathematical set operations like union, intersection, difference and symmetric difference. There are different types of set operations like set-union and set-intersection.

               .Set-union: A set-union is the union of two sets is the set of all the elements of both the sets without duplicates.
              
               . Set-intersection: A set-intersection is the intersection of two sets is the set of all the common elements of both the sets.

An Example of a set is:

                       thisset = {"apple", "banana", "cherry"}

                        print(len(thisset))



3. Tree

. Definition
. It's use
. It's Operations
. Example
. Problem / solution
