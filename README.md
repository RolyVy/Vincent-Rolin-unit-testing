# Vincent-Rolin-unit-testing

## **Intro**

This is a learning challenge to develop and test our skills on unit testing.
We got provided the code/program to test and we need to create the unit test code to test this program. 

Below you can find back the **Learning Objectives** and some **instructions** for this challenge.

---

> **_Pending things to do:_** xxxxxx Still Everything, Just Starting! xxxxxx


---


 *What, Why, When, How, Who.* aka learning evolution (I am adding at each step of the project my new understandings that will help me complete the project)
 
* Learning and understanding what part of the program should be tested and why. 

 We want to create tests to see if a program is working as expected, it will become helpful when months later we are coming back (me personally or another contributor) to add some new functionalities or just make our code more efficient. Then it is faster to see if our different modules run well all together even after the changes, without the need to to really make run the program.
 
 Aswell there is no need to test every and each functions of the program and ho it completely work from A to Z . We just want to check that the output that we expect is right(like a "blackbox"). Allowing us then later to rewrite some part of the code/ functions in a more efficient way to have the same input , and have our tests still relevant .
 
 Understand how the code is written, understand the objects within it and its functionalities, and that way understand what to test.
 
 * A Mock is a dubbel, it plays the role of an other object (like a server etc). 
 
 The goal is then to test the working connection/interaaction between the object tested and this other object without needing to really connect with that object. We just want to see if it would work if/when we then really run the program.
 Important to sync Mock and API (of those "mocked" objects)
 
 * (Res)Sources Used 
 
 Becode Theano 2-27 Repo
 
 Rails Conf 2013 The Magic Tricks of Testing by Sandi Metz    https://www.youtube.com/watch?v=URSWYvyc42M&feature=emb_title
 
 https://learn.datacamp.com/courses/unit-testing-for-data-science-in-python
 
 https://openclassrooms.com/en/courses/4425126-testez-votre-projet-avec-python
 
 

## **Learning Objectives¶**
You will learn how to take advantage of unit testing to create robust code. At the end of the challenge, you will be able to:

* Test your code with the assert python keyword
* Test your code with the unittest module
* Test your code with pytest module
* Use Mock objects
* Use other features from pytest

## **The Mission**
You work for a company working in Python. Your customer complains that your code crashes a lot and they're not able to access your services half of the time.

You see all the seniors of your company debugging all day and being mad at their colleagues breaking the code everytime they want to add a feature.

Your project manager asks you to write unit tests to fix the problem.

## **Must-have features¶**
* All the functions have to get at least one test.
* Use the Mock object
* Use pytest at least once

## **Nice-to-have features**
* Folow pep8 rules.
* Add a docstring for each test.
* Add type hinting for all your tests.
* Use Black to format your code.
* Use pytest for all your tests
* Try to mix pytest and unittest



Create your own fixture
Use parametrization


