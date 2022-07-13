1. STACKS:

For those who don't know, stacks are bundles of software that comprise your site's back end and everything from the operating system and web servers to APIs and programming frameworks.They follow the Last In, First Out principle which is also known as LIFO. We use stacks because they enables all data to operate at one end only. 

So the only element that can be removed is the element at the top of the stack, and only one item can be read or removed at a given time.
Stacks are faster due to the access pattern which makes it important to allocate and deallocate memory from a pointer.

Stacks have two basic operations which are push and pop.

. Push: Push adds an element to the collection 
. Pop: Pop removes the most recently added element that was not yet removed.

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
