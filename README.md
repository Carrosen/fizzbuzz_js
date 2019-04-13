Question 1:

let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)

Answer: already built in methods, that we should use.

Question 2: In your README to the best of your knowledge please explain why we are placing the let fizzBuzz = new FizzBuzz outside the it block?



Question 3: In your README to the best of your knowledge please explain the difference between using === and == in JS?


Question 4. In your README to the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?

You start at the top because you would like to get 'Fizz Buzz' instead of 'Fizz' or 'Buzz' right,it's kind of similar to the bills in the ATM_challenge you would like to get the 20 bills first instead of 5 right so you but it in the order [20, 10, 5]. It's the same principal.


