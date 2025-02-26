The SortedMultiMap is an ADT that stores ordered (key, value) pairs in a singly linked list (SLL) based on a given relation applied to keys.
Unlike standard maps, it allows multiple values for the same key while maintaining a sorted structure.
Insertion places elements in order, while searching and deletion require linear traversal.
The structure dynamically allocates memory, adjusting as elements are added or removed. Although less efficient than other map implementations,
it provides a simple and flexible way to handle duplicate keys
