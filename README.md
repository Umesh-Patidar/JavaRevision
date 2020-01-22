# JavaRevision

# Collection :

A **Collection** is a group of individual objects represented as a single unit. Java provides Collection Framework which defines several classes and interfaces to represent a group of objects as a single unit.

```
Before Collection Framework (or before JDK 1.2) was introduced, the standard methods for grouping Java objects (or collections) were **Arrays** or **Vectors** or **Hashtables**. All of these collections had no common interface. 

#Example

Declaration
        *int arr[] = new int[] {1, 2, 3, 4}; 
        *Vector<Integer> v = new Vector(); 
        *Hashtable<Integer, String> h = new Hashtable(); 
        
Adding element
        v.addElement(1); 
        h.put(1,"geeks");
        
Accessing first element of array, vector and hashtable 
        System.out.println(arr[0]); 
        System.out.println(v.elementAt(0)); 
        System.out.println(h.get(1));          

#Drawbacks
1. None of these collections (Array, Vector or Hashtable) implement a standard member access interface.
2. It was very difficult for programmers to write algorithms that can work for all kinds of Collections(Array, Vector or Hashtable).
3. Most of the ‘Vector’ methods are final, meaning we cannot extend the ’Vector’ class to implement a similar kind of Collection.
```
