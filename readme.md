# Elliott Mejia Sumbission for Code Wiz

This is an interactive UI demo for your assessment.

I wanted to make sure that my submission was unique in design and implementation, while remaining on a single HTML file.

This SPA was made with React 18, Babel, and Tailwind over CDN.

*Full disclosure- I initially hit a bit of a roadblock deconstructing createRoot from ReactDOM.client, which is usually imported with **import { createRoot } from 'ReactDOM/client'** in module files. For the sake of time, I moved on quickly and this was originally written in React 17. I then fixed it in a dream by just logging the ReactDOM object and realizing they changed structure for CDN, which also worked in real life. So you may notice I changed the React version to 18. Hilarious.*

If you do not have a live server set up, you can run this file with this one-liner.

```bash
npm install http-server -g && http-server && open http://localhost:8080
```

*Here is the prompt for the assessment:*

## JavaScript Test Assessment: Shape Display Challenge

**Objective:**
Create a single-page HTML application that dynamically displays geometric shapes based on the divisibility of input numbers. The application should not be developed with the assistance of AI tools, please use any other tools you would like such as jQuery, bootstrap, etc. Please complete this assessment by Friday 1/19/24, we look forward to reviewing your work. Thank you.

### Requirements:
**HTML Structure:** Single file HTML page with embedded JavaScript.
**Shape Display Logic:**
● **Square:** Display if the number is divisible by 2.
● **Rectangle:** Display if the number is divisible by 3.
● **Triangle:** Display if the number is an odd number less than 10.
● **Circle:** Display if the number is a prime number.
● **Input & Output:** If the output number is odd, the inside of the shape should be filled
with the color green. If it is even, display the background color as red. Background color of the shape should be gray if the number is greater than 50. If the number is greater than 50, gray background should take priority over background based on even or odd.
The application should accept a series of numbers (at least 8 for testing purposes).
Each output (shape) must be displayed on a new line, preceded by the number of the question (e.g., "1. Triangle(the shape, not the word)" for the first number if it meets the triangle criteria).
Implement an interactive UI allowing users to input numbers and see the result in real-time.
**Example Outputs:** Input: 4 (divisible by 2)
**Output:** Square.
**Color:** No color filling (since 4 is even). Background: Default (4 is not greater than 50). Input: 9 (odd and less than 10)
**Output:** Triangle.
**Color:** Green filling (since 9 is odd). Background: Default (9 is not greater than 50). Input: 17 (prime number)

**Output:** Circle.
**Color:** Green filling (since 17 is odd). Background: Default (17 is not greater than 50). Input: 51 (greater than 50)
**Output:** Follows the shape logic based on divisibility. Color: If odd, fill with green.
**Background:** Light gray (since 51 is greater than 50).
This comprehensive assessment will test the candidate's proficiency in JavaScript, HTML, and CSS, focusing on logic implementation, DOM manipulation, and styling. It also provides room for creativity and problem-solving skills.
Please test using these numbers: 4
9
17
51
24
35
13
30
55
23
