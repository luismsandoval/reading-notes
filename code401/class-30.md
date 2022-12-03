# Hashtables

## What is a hashtable

1. Hash -- taking a string, and turning it into a unique index
2. Buckets -- what is contained at each index
3. Collisions -- when more than one key gets hashed to the same index

## Why use them

1. Hold unique values
2. Dictionary
3. Library

## What are they

- Hashtables are a data structure that utilize key/value pairs.

  - Every node has a key and a value

- The idea is being able to store a value and quickly retrieve this value using the hash.

- Hashmaps have fast read access because of the hash. O(1)

```typescript
hashMap.Add("Pioneer Square", 98104);
```

```
Bucket 92: [{Pioneer Square: 98104}
```

### Storing a value

- accepts a key
- calculate the hash
- store the key with the value to a linked list at the index(bucket)

### Reading a value

- accepts a key
- calculate the hash
- use index to access the linked list

## Methods

- `get()`

  - input: key
  - return: value

- `has()`

  - input: key
  - return: boolean

- `keys()`

  - returns collection of hash keys

- `hash()`
  - input: string
  - returns index
