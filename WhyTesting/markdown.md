# Why is Testing Important?



## The Developer Feedback Loop

![External Image](https://mitchdenny.com/content/images/2018/01/CodeBuildTest.png)

Note: This will only appear in the speaker notes window.


### Confidence

We do this to be **confident** in the changes we’re making.


### What effects our confidence?

* Time
* Short term fixes
* Complexity
* Other Developers
* ...



## Lets do it efficiently


#### Automate It!

Automating this process gives us the confidence we need, and saves us time.


#### Kent Says

> "The tests save me time, and they give me — and all the users of my libraries — a great amount of peace of mind."


#### Kent Says

> "I write tests because they allow me to accomplish more than I could otherwise. I now have thousands of Kents in the form of automated tests telling me whether changes are breaking use cases. With that venerable army of robots, I'm able to rest easy and get more accomplished."

Confidently Shipping Code - https://kentcdodds.com/blog/confidently-shipping-code



## What are the different types of automated testing?


#### The Testing Trophy

![External Image](https://kentcdodds.com/static/c56de32357ab41ab66d6feb2dfaec567/00d43/testing-trophy.png)


#### Static Analysis Tools

Catch typos, and type errors as you write the code

* ESLint
* Prettier
* TypeScript


#### Unit Testing

Verify that individual, isolated parts work as expected


#### Integration Testing

Verify that several units work together in harmony


#### End to End

> A helper robot that behaves like a user to click around the app and verify that it functions correctly.

— Kent again

https://kentcdodds.com/blog/unit-vs-integration-vs-e2e-tests



## 

![External Image](https://kentcdodds.com/static/c331ec0658e3d2927db08b6e4946e266/e3189/confidence-coefficient.png)


#### Trade Offs

* **Cost** - manhours to build and maintain tests
* **Time** - amount of time it takes to run a test
* **Confidence** - how much confidence it gives us


#### The Confidence Coefficient

value = confidence / (cost + time)



## Next Time

### How can we maximize our confidence per cost/time invested?



## Citation Needed

1. Confidently Shipping Code - [https://kentcdodds.com/blog/confidently-shipping-code](https://kentcdodds.com/blog/confidently-shipping-code)
2. Demystifying Testing - [https://kentcdodds.com/blog/demystifying-testing](https://kentcdodds.com/blog/demystifying-testing)
3. Why You've Been Bad About Testing - [https://kentcdodds.com/blog/why-youve-been-bad-about-testing](https://kentcdodds.com/blog/why-youve-been-bad-about-testing)
4. Eliminate an Entire Category Of Bugs With A Few Simple Tools - [https://kentcdodds.com/blog/eliminate-an-entire-category-of-bugs-with-a-few-simple-tools](https://kentcdodds.com/blog/eliminate-an-entire-category-of-bugs-with-a-few-simple-tools)
5. Static vs Unit vs Integration vs E2E Testing for Frontend Apps -[https://kentcdodds.com/blog/unit-vs-integration-vs-e2e-tests](https://kentcdodds.com/blog/unit-vs-integration-vs-e2e-tests)