### Question 1: 
#### In your README to the best of your knowledge please explain what the following lines of code do:

```
let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js' ;
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
```

### Answer:
Loading already built in methods.

---

### Question 2: 
#### In your README to the best of your knowledge please explain why we are placing the let fizzBuzz = new FizzBuzz outside the it block?

### Answer:
So you don't need to write it in every it block. Now it is accessible for every it block. 

---

### Question 3:
#### In your README to the best of your knowledge please explain the difference between using === and == in JS?

### Answer:
==(equal) is not as precise as ===(deeply equal)

---


### Question 4.
#### In your README to the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?

### Answer:
Answered the question and then I noticed 5 instead of 15? typo? or am I wrong here

You start at the top because you would want to get 'Fizzbuzz' before 'Buzz' or 'Fizz' right, it's kind of similar to the bills in the ATM_challenge, you would like to get the 20 bills first so you put it in the order [20, 10, 5]. It's the same principle.

---


### Question 5.
#### In your README to the best of your knowledge please explain the difference between feature and unit test.

### Answer:
Unit tests will test small parts of code and with feature testing you are testing the application as a user would in bigger portions.

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
Your testing the page so you want it to visit it, reload the page and then close it. This need to happen to test the functions on the page.

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
Im not really sure but this is what we put in the html and we are calling on the function we have in our fizz-buzz.js file, we are waiting for a user to lick the button, so when it gets clicked we will display the answer which depends on what the user put in(value) so we have four scenarios in this case, it will display fizz, buzz, fizzbuzz or 'Try again' depending of what the input was.

---

### Question 9.
#### In your README to the best of your knowledge please explain what a CDN (Content Delivery Network) is?

### Answer:
CDN means a group of servers working together to provide fast delivery of Internet content. It is designed to load your website, quickly, by having servers closer to the costumer and the website will load faster.

---

