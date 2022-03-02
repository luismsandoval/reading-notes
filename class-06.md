# Class 06 2/28/2022

## Primitive values and Object references

There are 8 different data types, all of which are primitive value types except for `objects`.

`Boolean`

`Null`

`Undefined`

`Number`

`BigInt`

`String`

`Symbol`

`Objects`

Primitive values are **immutable** - meaning they cannot be changed, while object references are **mutable** - meaning that they can be changed.

## Object Literals

We can use literal notation to create an object.

```javascript
let hotel = {
  name: 'Luis',
  rooms: 40,
  booked: 25,
  checkAvailability: function() {
    return this.rooms - this.booked;
  }
};
```

We can use dot notation to access a property or method inside an object.

```javascript
let hotelName = hotel.name;
let roomsFree = hotel.checkAvailability();
```

We can also access properties of an object using square bracket index.

```javascript
let hotelName = hotel['name'];
```

## Problem Domain

Find the problem! Break it down into smaller problems first.
