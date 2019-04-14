### Question 1: 
#### In your README to the best of your knowledge please explain what the following lines of code do:

```
let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js' ;
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
```

### Answer:
Already built in methods, that we can use.

---

### Question 2: 
#### In your README to the best of your knowledge please explain why we are placing the let fizzBuzz = new FizzBuzz outside the it block?

### Answer:
So you don't need to write it in every it block.

---

### Question 3:
#### In your README to the best of your knowledge please explain the difference between using === and == in JS?

### Answer:
==(equal) is not as precise as ===(deeply equal)

---


### Question 4.
#### In your README to the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?

### Answer:
You start at the top because you would want to get 'Fizz Buzz' instead of 'Fizz' or 'Buzz' right, it's kind of similar to the bills in the ATM_challenge, you would like to get the 20 bills first instead of 5 so you put it in the order [20, 10, 5]. It's the same principal.

---


### Question 5.
#### In your README to the best of your knowledge please explain the difference between feature and unit test.

### Answer:
Unit tests make sure that all the units of code functions in isolation and with feature testing you are testing the application as a user would. 

---

### Question 6.
#### In your README to the best of your knowledge please explain what this following code does:

```
describe('User can input a value and get FizzBuzz results', () => {
    before(async () => {
        await  browser.init()
        await  browser.visitPage('http://localhost:8080/')
    });

    beforeEach(async () => {
        await  browser.page.reload();
    })

    after(async ()=> {
        await  browser.close();
    })
})
```
### Answer:
Your testing the page, so you want it do find it, visit it, reload the page and then close it. This need to happen to test the functions on the page.

---

### Question 7.
#### In your README to the best of your knowledge please explain what expectations in the context of testing are.

### Answer:
What you expect should happen when you write in something specific like "5", then we expect that the output should be "Buzz".

---

### Question 8.
#### In your README to the best of your knowledge please write a line to line explanation of what is happening in this code:

```
<script src="./js/fizz-buzz.js"></script>
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            let button = document.getElementById('button')
            let displayDiv = document.getElementById('display_answer')
            button.addEventListener('click', () =>{
                let value = document.getElementById('value').value
                let fizzBuzz = new FizzBuzz
                let result = fizzBuzz.check(value)
                displayDiv.innerHTML = result;
            })
        })
    </script>
```

### Answer:


---

### Question 9.
#### In your README to the best of your knowledge please explain what a CDN (Content Delivery Network) is?

### Answer:


---

