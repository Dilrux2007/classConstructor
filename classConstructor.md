## [Classes For Fetching Information on a Sports Player](https://edabit.com/challenge/ZngT4zDckDugt2JGY)

```js
class Player {
	constructor(name, age, height, weight) {
		this.name = name;
        this.age = age;
		this.height = height
		this.weight = weight
	}
	getAge() {
		return (`${this.name} is age ${this.age}`)
	}
	getHeight() {
		return (`${this.name} is ${this.height}cm`)
	}
	getWeight() {
		return (`${this.name} weighs ${this.weight}kg`)
	}
}		
```

## [Point Series 1: Skeleton](https://edabit.com/challenge/HwFtgwoW2qbQnoD6s)
```js
class Point  {
	constructor(x, y) {
	this.x = x;
    this.y = y;
	}
	toString(){
		return `[x=${this.x}, y=${this.y}]`
	}
}
```

## [Simple OOP Calculator](https://edabit.com/challenge/yxKoCKemzacK6PECM)
```js
	class Calculator {
	
	add(a , b) {
		return a + b
	}
	divide(a , b) {
		return a / b
	}
	multiply(a , b) {
		return a * b
	}
	subtract (a, b){
		return a - b
	}
	}
```

## [Fullname and Email](https://edabit.com/challenge/kGLhgwGaLJsCMS7wS)
```js
class Employee {
	constructor (firstname, lastname) {
		this.firstname = firstname
		this.lastname = lastname
		this.fullname = `${this.firstname} ${this.lastname}`
		this.lowefirstname = this.firstname.toLowerCase()
		this.lowelastname = this.lastname.toLowerCase()
		this.email = `${this.lowefirstname}.${this.lowelastname}@company.com`
	}
}
```

## [Make a Circle with OOP](https://edabit.com/challenge/Hgb38yhWGwJCMHbRQ)
```js
class Circle {
	constructor(r) {
    this.r = r
  }
  getArea() {
    return Math.PI * this.r ** 2
  }
  
  getPerimeter() {
    return 2 * (Math.PI * this.r)
  }
	
}
```