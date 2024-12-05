# Core Java Questions

- [Collections](#Collecctions)
- [Threads](#Threads)

## Collections 
1.  Java.util.collection interface 
1.  List (Interface) > ArrayList, LinkedList, Vector, CopyOnWriteArrayList 
1.  Set (Interface) > HashSet, LinkedHashSet 
1.  SortedSet (Interface) > TreeSet, NavigableSet, ConcurrentSkipListSet 
1.  Map (Interface) > HashTable, HashMap > LinkedHashMap, IdentityHashMap, WeakHashMap. 
1.  ConcurrentMap (Interface) > ConcurrentHashMap 
1.  SortedMap (Interface) > NavigableMap (Interface) > TreeMap, ConcurrentSkipListMap. ⮚ EnumMap 
1.  Queue (Interface) > PriorityQueue 
1.  Queue (Interface) > Deque (Interface) > ArrayDeque 
1.  Queue (Interface) > BlockingQueue > BlockingDeque 
1.1.  which is better removeAll () method vs map.clear () in collections? 
1.1.  Which is better map.clear () vs (map=null or map=new Map) in collections? 

---

## Thread:- 
1.  Sleep() 
1.  Wait() 
1.  Notify() 
1.  notify all() 
1.  volatile 
1.  Yield() 
1.  Synchronize 
1.  Join() 
1.  Interrupt 
1.  Thread pool 
1.  Locks(Class level lock vs object level lock) 
1.  Reentrant Locks 
1.  Inter thread communication 
1.  Static synchronization vs non-static synchronization 
1.  Thread Local. 
1.  Executers 
1.  Why wait (), notify () and notifyAll () put in Object class. 
1.  Why wait (), notify () and notifyAll () must be call from Synchronize block or Synchronize method only. 
1.  Deadlock 
1.  Race condition

---

### Important Topics in Java: - 
1.  Serialization and Inheritance 
1.  Transient 
1.  Will static, final variables serialized? 
1.  Checked Exception vs Unchecked Exception. 
1.  Exception handling and Overriding. 
1.  Exception Propagation. 
1.  Throw, throws and custom exception. 
1.  Immutable Class. 
1.  Prevent singleton from breaking. 
1.  How to make class immutable. 
1.  Deep cloning vs shallow cloning. 
1.  Rules for multicatch. 
1.  Serialization vs Externalization 
1.  Why String are immutable in java. 
1.  Concurrent API 
1.  Java.util.concurrent.atomic 
1.  Atomic variable 
1.  Failfast vs Failsafe 
1.  Iterator vs Listiterator 
1.  Immutable collections 
1.  Why it’s better to use iterator.remove () method while iterating instead of list.add or list.remove method. 
1.  Why add method not put in iterator while it is in listiterator. 
1.  Optional class. 
1.  Strictfp 
1.  Defensive Copy 
1.  Varargs 
1.  Covariant Return Type 
1.  Anonymous Classes 
1.  Why LinkedHashMap maintain insertion order while HashMap not. 
1.  upcasting vs downcasting 
1.  widening primitive conversion vs narrowing primitive conversion 
1.  Generalization vs Specialization 
1.  Oops concept 
1.  Overriding with access modifier 
1.  Overloading with arguments 
1.  Double null check in Singleton 
1.  Can we override static method? 
1.  Assertion 
1.  Why HashMap should not be used in multithreaded environment? 
1.  Rehashing in HashMap 
1.  Loadfactor in HashMap 
1.  Definite Assignment

---

### Generics: - 
1.  Java generics 
1.  wild cards 
1.  Difference between extends and super. 

---

### Points to remember:- 
1.  ✔ By default, Unchecked Exceptions are forwarded in the calling chain (propagated).
1.  ✔ By default, Checked Exceptions are not forwarded in the calling chain (propagated).
1.  ✔ If the superclass method does not declare an exception, subclass overridden method cannot declare the checked exception.
1.  ✔ If the superclass method does not declare an exception, subclass overridden method cannot declare the checked exception but can declare unchecked exception. 
1.  ✔ If the superclass method declares an exception, subclass overridden method can declare same, subclass exception or no exception but cannot declare parent exception in case of checked exception only. 
1.  ✔ Functional interface cannot have more than one abstract method but it can have more than one default method. 
1.  ✔ Strictfp applied on method, interface or classes (any class), it cannot be applied on abstract methods, variables or constructor. 
1.  ✔ Class must be public or abstract or final. 
1.  ✔ Exception Hierarchy:- 
1.1  Object > Throwable:- 
a) Error 
b) Exception:- 
o Checked Exception: - Class which extends Exception class 
and classes which doesn’t extends RuntimeException. 
Examples: - IOException, SQLException, 
InterruptedException. 
o Unchecked Exception: - Class which extends 
RuntimeException 
Examples: - ArithmeticException, ClassCastException, 
NullPointerException, IndexOutOfBoundExcepotion. 
✔ Type parameter in generics are single uppercase letters they are:- 
E – Element ( used extensively in java collection framework). 
K – Key 
N – Number 
T – Type 
V – Value 
S,U,V etc. – 2nd, 3rd, 4th types 
1.  ✔ The question mark (?) called the wildcard, represent an unknown type, it is used as type of parameter, field, local variable or return type, it is never used as type argument for generic method invocation, a generic class instance creation, or a supertype. 
1.  ✔ Upper Bounded Wildcard is a question mark(?) followed by extends keyword e.g. <? extends A> ✔ Unbounded Wildcard is (?) for e.g.- List<?> list of unknown type. 
1.  ✔ Lower Bounded Wildcard is question mark(?) followed by super keyword e.g. <? super A> ✔ The set of checked exception that a method can throw is the intersection of set of checked exception that it declared to throw in all applicable type. 
1.  ✔ The language specification says that checked exception in catch clause are permitted only when the corresponding try block can throw the exception in question. 

---

### Points to be observed (For Better Performance): - 
1) Use String Literal instead of creating String with new Keyword. 
2) Eliminate obsolete object references. 
3) Always override hashcode when override equals or vice versa.
4) Make Defensive copies when needed (immutable classes). 
5) Prefer instanceof instead of overloading when needed. 
6) Return empty array or collections not null. 
7) Prefer foreach loop instead of for loop or while loop. 
8) Always use Bigdecimal(String) instead of Bigdecimal(double) and where exact answer are required. 
9) Prefer List in place of Arrays. 
10) Avoid raw type use generics type. 
11) Minimize the scope of local variables. 
12) Avoid float or double, use BigDecimal, int or long for monetary calculations. 13) Prefer primitive types to boxed primitives. 
14) Use boxed primitives as elements, keys and values in collections, can’t put primitives in collection. 

