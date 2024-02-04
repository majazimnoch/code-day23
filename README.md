# To do list with Vue
## Intro
This is day 23 and 24 of my coding challenge. On day 23 I put focus on developing logic. Day 24 is dedicated to styling my functional website.

## Idea 
I wanted to brush up on my Vue skills while developing a useful app. Todo list allows to use some features privided by the framework, like `ref`, `watch`, `onMounted`, `computed`.

## Breaking down the code
I used `ref` to create reactive variables like `todos`, `name`, `input_content`, and `input_category`. There's a computed property `todos_asc` that returns the to-do list sorted in descending order based om the `createdAt` property. 

There are two watchers (`watch` function). One watch watches changes in the to-do array and stores it in the local storage. The other watch watches changes in the `name` variable and stores it in the local storage. 

All the HTML tags are in the template section. 

## Demo
Click <a href="https://hilarious-snickerdoodle-fd4dd4.netlify.app/">here</a>.

To run the project npm run dev