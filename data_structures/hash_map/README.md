### HashMap

HashMap is a Map based collection class that is used for storing Key & value pairs, it is denoted as HashMap<Key, Value> or HashMap<K, V>. This class makes no guarantees as to the order of the map. It is similar to the Hashtable class except that it is unsynchronized and permits nulls(null values and null key).

It is not an ordered collection which means it does not return the keys and values in the same order in which they have been inserted into the HashMap. It does not sort the stored keys and Values. You must need to import java.util.HashMap or its super class in order to use the HashMap class and methods.

1. void clear(): It removes all the key and value pairs from the specified Map.
1. Object clone(): It returns a copy of all the mappings of a map and used for cloning them into another map.
1. boolean containsKey(Object key): It is a boolean function which returns true or false based on whether the specified key is found in the map.
1. boolean containsValue(Object Value): Similar to containsKey() method, however it looks for the specified value instead of key.
1. Value get(Object key): It returns the value for the specified key.
1. boolean isEmpty(): It checks whether the map is empty. If there are no key-value mapping present in the map then this function returns true else false.
1. Set keySet(): It returns the Set of the keys fetched from the map.
1. value put(Key k, Value v): Inserts key value mapping into the map. Used in the above example.
1. int size(): Returns the size of the map – Number of key-value mappings.
1. Collection values(): It returns a collection of values of map.
1. Value remove(Object key): It removes the key-value pair for the specified key. Used in the above example.
1. void putAll(Map m): Copies all the elements of a map to the another specified map.
