# Why do we need a New Data Structure Hash Map?

When we are searching for a value in BST it has a time complexity of  **O(log n)** we want to reduce the time complexity to **O(1)**  that is constant in constant time . So we need a data strucutre that organizes data in a manner so that we can retrieve information in constant time.

<br>

---

### Idea 
<br>
 
So what we do is we make an array which stores values and we decide index based on a fucntion which givex index based on value. 

<br>

### Approach 
* ***Division*** 
<br><br>

    * In this approach we make a function 
        ~~~
        f(x) = x % size
        ~~~
    
        known as **Hash Function** 

        A Hash Function can be any fucntion of x  (the value) hash fucntion returns the index
        that the value should be assigned to .

        > Hash Function can be anything.

        ~~~ 
        f(x) = (x + 3) % size 

        f(x) = (x + (x+4)) % size 

        ~~~
<br><br>

* ***Mid Square method***
    
    * In this method we square the given value and 
    take the middle element as the index where we will store the given value
    


    










