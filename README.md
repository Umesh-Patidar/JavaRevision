# JavaRevision

# Collection :

A **Collection** is a group of individual objects represented as a single unit. Java provides Collection Framework which defines several classes and interfaces to represent a group of objects as a single unit.

Before Collection Framework (or before JDK 1.2) was introduced, the standard methods for grouping Java objects (or collections) were **Arrays** or **Vectors** or **Hashtables**. All of these collections had no common interface. 

# Example

- Declaration
        1. int arr[] = new int[] {1, 2, 3, 4}; 
        2. Vector<Integer> v = new Vector(); 
        3. Hashtable<Integer, String> h = new Hashtable(); 
        
- Adding element
        1. v.addElement(1); 
        2. h.put(1,"geeks");
        
- Accessing first element of array, vector and hashtable 
        1. System.out.println(arr[0]); 
        2. System.out.println(v.elementAt(0)); 
        3. System.out.println(h.get(1));          

# Drawbacks
1. None of these collections (Array, Vector or Hashtable) implement a standard member access interface.
2. It was very difficult for programmers to write algorithms that can work for all kinds of Collections(Array, Vector or Hashtable).
3. Most of the ‘Vector’ methods are final, meaning we cannot extend the ’Vector’ class to implement a similar kind of Collection.

# Advantages of Collection Framework:

 - Consistent API : The API has a basic set of interfaces like Collection, Set, List, or Map. All classes (ArrayList, LinkedList, Vector, etc) that implement these interfaces have some common set of methods.
 
 - Reduces programming effort: A programmer doesn’t have to worry about the design of Collection, and he can focus on its best use in his program.
 
 - Increases program speed and quality: Increases performance by providing high-performance implementations of useful data structures and algorithms.

