# Python_Tuple

Advantages of Tuple over List
Since tuples are quite similar to lists, both of them are used in similar situations. However, there are certain advantages of implementing a tuple over a list.

<b>Below listed are some of the main advantages:</b>

We generally use tuples for heterogeneous (different) data types and lists for homogeneous (similar) data types. Since tuples are immutable, iterating through a tuple is faster than with list. So there is a slight performance boost. Tuples that contain immutable elements can be used as a key for a dictionary. With lists, this is not possible. If you have data that doesn't change, implementing it as tuple will guarantee that it remains write-protected.
