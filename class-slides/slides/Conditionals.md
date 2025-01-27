# Conditionals & Operators
---
### Review Last project
By Tracy Phillips
<iframe src="https://editor.p5js.org/phillipstt2/full/AL5VM-95u" width=800 height=900></iframe>

--

by Khalid Al Ismaeel
<iframe src="https://editor.p5js.org/universamv/full/9qRdDTkaj" width=800 height=900></iframe>

--

By Masao Gallan
<iframe src="https://editor.p5js.org/gallanma/full/8Pv_5DH_f" width=800 height=800></iframe>

--

By Lauren Wits

<iframe src="https://editor.p5js.org/witsle/full/utDHfPs5g" width=500 height=500></iframe>

--

<iframe src="https://editor.p5js.org/Luniss101/full/Z4eH_25gA" width=500 height=500></iframe>

---

## Conditional

<iframe src="https://editor.p5js.org/lilyxia99/full/FC1tdHiW1" width = 500 height=500></iframe>

--

``` javascript
if (sunHeight < horizon) {
    fill('lightgreen');
  } else {
    fill('green');
  }

```

--

```javascript
if({your condition}){
	//what the program will do if it satisfy the condition in the ()
}
```

--

```javascript
if({your condition}){
	//functions and whatever you wanna do
}else{
	//if it doesn't satisfy
}
```


--


```javascript
if({your condition}){
	//functions and whatever you wanna do
}else if(your another condition){
	//if it doesn't satisfy
}
```

---

```javacript
=, /, *, + are all operators
```

--

"=" assignment operator

"+" additional operator

"*" multiplication operator

">" comparision operator 

--

| Operator | Description                                                         |
| -------- | ------------------------------------------------------------------- |
| +        | Addition                                                            |
| -        | Subtraction                                                         |
| *        | Multiplication                                                      |
| **       | Exponentiation ([ES2016](https://www.w3schools.com/js/js_2016.asp)) |
| /        | Division                                                            |
| %        | Modulus (Division Remainder)                                        |
| ++       | Increment                                                           |
| --       | Decrement                                                           |
|          |                                                                     |

---

### Comparison Operators

| Operator | Description                       | Comparing | Returns |
| -------- | --------------------------------- | --------- | ------- |
| ==       | equal to                          | x == 8    | false   |
|          |                                   | x == 5    | true    |
|          |                                   | x == "5"  | true    |
| ===      | equal value and equal type        | x === 5   | true    |
|          |                                   | x === "5" | false   |
| !=       | not equal                         | x != 8    | true    |
| !==      | not equal value or not equal type | x !== 5   | false   |
|          |                                   | x !== "5" | true    |
|          |                                   | x !== 8   | true    |
| >        | greater than                      | x > 8     | false   |
| <        | less than                         | x < 8     | true    |
| >=       | greater than or equal to          | x >= 8    | false   |
| <=       | less than or equal to             | x <= 8    | true    |
|          |                                   |           |         |

--

most commonly used:

```
==, !=, <, >
```

--

```
if(you == "hard-working"){
  you = "A";
}
```

---

## Logical Operators



---

And

```javascript
if(homework=="experiments" && you =="hard-working"){

}
```

--
Or
```javascript
if(you=="experiments" || you =="hard-working")
```

---

Exercise: 

try to make a simple interactive sketch, either based on your original animated sketch or a new shape sketch, so that the shape is animated only under a certain condition (e.g. controlled by your mouseX and mouseY)