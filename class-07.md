# Class 7 3/5/2022

## Tables

```html
<table>
  <th scope="row">
  <tr rowspan="3">
    <th scope="col">
    <td colspan="2">
```

```html
<thead>
<tbody>
<tfoot>
```

## Objects

`new` and `object` will create a new new empty object.

We can add to that object using the dot notation.

```javascript
let hotel = new Object();
hotel.name = 'Quay';
hotel.rooms = 40;

hotel.checkAvail = function() {
  \\code here\\;
}
```

We can update these properties using the same technique as above.

```javascript
hotel.name = "new name";
hotel['name'] = 'another new day';
```

**Heres how we can use a function to create multiple objects that represent multiple things**

```javascript
function Hotel(name, rooms, booked) {
  this.name = name;
  this.rooms = rooms;
  this.booked = booked;
  this.checkAvail = function() {
    return this.rooms - this.booked;
  }
}

Hotel('Hyatt', 100, 75);
```

**arrays are objects**
