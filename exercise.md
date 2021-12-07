### Q1

```js
class Movie {
  constructor(title, studio, rating = "PG") {
    this.title = title;
    this.studio = studio;
    this.rating = rating;
  }
  
  static getPG(movies) {
    return movies.filter(movie => movie.rating === "PG");
  }
}

let casinoRoyale = new Movie("Casino Royale", "Eon Productions", "PG13");
```

### Q2

```js
class Circle {
  constructor(radius = 1.0, color = "red") {
    this.radius = radius;
    this.color = color;
  }
  
  get getRadius() {
    return this.radius;
  }
  
  set setRadius(radius) {
    this.radius = radius;
  }
  
  get getColor() {
    return this.color;
  }
  
  set setColor(color) {
    this.color = color;
  }
  
  toString() {
    return `Circle[radius=${this.getRadius},color=${this.getColor}]`;
  }
  
  getArea() {
    return Math.PI * this.getRadius ** 2;
  }
  
  getCircumference() {
    return 2 * Math.PI * this.getRadius;
  }
}
```
### Q3
 
```js
class Person {
  
  constructor(firstName, lastName, age, address) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.age = age;
    this.address = address;
  }
```

### Q4

```js
class UberRide {
  
  constructor(costPerKm, distance) {
    this.costPerKm = costPerKm;
    this.distance = distance;
  }
  
  getRideCost() {
    return this.costPerKm * this.distance;
  }
}
```

  
  
