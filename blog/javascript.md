# JavaScript Blog

My Name Is Aditya!! How are you all doing! Hope you all are doing good!!😎 and today this blog is for the totally beginners in Javascript.

So, Today I am gonna write the basic syntax of Javascript for you guys because genuinely I love to teach someone so I am writing a blog on Javascript!!❤

Here in this series I am going to tell different concepts of JavaScript (JS) starting with one of important topics of JS

Promise During University Placements you gone for company interview but hurriedly to reach there by mistake you forgot your resume. Your turn is next . Luckily your your flatmate still in house so you called him to find the resume and come to give it He promise reply you back. There are two outcome to this situation either he find resume (task is successful or resolve ✅) or sadly he calls he can't find it (results in failure or reject ❌). But time is passing by and flatmate is not messaging but interviewer was kind enough to let it pass and continue the interview marking resume submission as still pending

So in JS terms a promise is asynchronous meaning it takes time to resolve. In mean time JS doesn't wait for resolving of one event it mark it as pending waiting for returning value and run rest part of the code 👨‍💻. In this case you are waiting for your friend call for the result. Just like that in promise we use callback function (promise handler) to return the results. To specify which callback to call we use to two callbacks function using nested then()method

Resolve(value): This indicates that the asynchronous task was successful. This will call the fulfillment callback in the then() handler.

Here waiting (setTimeout ) is 300 secs or 5 mins before moving forward

Reject(error): This indicates an error while trying to run the asynchronous task. This will call the rejection callback in the then() handler.

Always keep in mind that a then() method must take both the fulfillment hander and a rejection handler. This way, the first is called if the promise is fulfilled and the second is called if the promise is rejected with an error.

JavaScript promises are a very powerful feature that help you run asynchronous code in JavaScript. In most asked in backed developer interviews .

In this blog , I have explained what a promise is in simple terms, and I've shown its basic practical usage with some code examples. I hope you got something useful from this blog.
