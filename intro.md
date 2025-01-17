
Data Science for Economics and Finance
==============================================

```{warning}
These notes are very much a work in progress. I am still slowly assembling everything and this site as it currently stands is not reflective of the final product. The expectation is to have these notes done by some time in 2022. 
```

In this part of the course we will focus on machine learning methods and databases. At this stage in the world of data science three of the most frequently used languages are `R`, `Python` and `SQL`. This means that when you enter the job market, you will have be proficient in at least one of these languages. In terms of statistical analysis R is the undoubted champion, while Python is a great general programming languages that can be used effectively in machine learning. SQL is the language used to interact with databases. We will be using both Python and R as our preferred programming languages, touching briefly on the basics of SQL. You do not have to worry if you have never worked with Python, you can continue working in R if you are more comfortable focusing on just one language at a time. 

Just to make it clear, in this course we **officially** use R, which means I will provide you with `R` code (even if we work with Python). For my section it is more important that you understand the machine learning concepts and then you can implement it in any language that you prefer. At this stage in your career as an economist / data scientist, you can focus on one programming language to fulfill most of your needs. You can most likely use one language for your entire career. However, concepts will remain the same across most languages and as you develop your skills you will notice that the language you use becomes almost irrelevant. Someone that is trained in Python, for example, should be able to transfer those skills to other languages in a short time frame. 

The reason to showcase Python in this course is then partly to introduce you to a new language and then show that you can easily switch between languages if needed. You should not be afraid to use different tools for different problems. My goal is not to overwhelm you with syntax, but rather show you how easy it can be to play around with different languages. In my personal workflow I leverage the speed of `Julia` for computational problems and switch to Python for machine learning problems due to its mature package ecosystem. I am sure that I would be able to use Python for numerical analysis, I just have a strict preference to use Julia. Whenever I have to do basic data wrangling and visualisation, I find that R is the easiest to use. However, I am becoming more enamoured with Python's plotting ecosystem and I have seen some truly amazing things developing over the years in Python.   

# Topics

Below are some of the topics that we will cover during this term.

1. Python fundamentals (self-study)
2. Math for machine learning (self-study)
3. Linear and polynomial regression
4. k-Nearest neighbours
5. Tree-based methods
6. Support vector machines
7. Neural networks
8. Databases (SQL and BigQuery) 
9.  Parallel programming
10. Cloud computing with Google Compute Engine

We will not have time to cover all the topics in full detail, so you can refer to the notes if you would like to know more. I will also link to other sets of notes so that you can read in more detail on some of the issues at hand. Since most of you have little experience with machine learning and programming, we will be taking things quite slow. In that sense this course provides you the basic tools from which you can go and further explore. 

# Readings

Mathematics and statistics is at the core of all machine learning. The better you understand the math behind the algorithms that you want to implement, the less likely you are to make errors. There are different levels of mathematics needed for machine learning, it all depends on what you want to do. For the purpose of this course we will focus on basic linear algebra and optimisation. The best book that I know of that covers all the basic ideas that you need to get started with machine learning is that of [*Mathematics for Machine Learning*](https://mml-book.github.io/book/mml-book.pdf) by Marc Peter Deisenroth, A. Aldo Faisal, and Cheng Soon Ong. You will want to look at the first seven chapters of this book. The prerequisites are simply high school mathematics, so everyone should be able to read this book without issue. 

Topics in machine- and deep learning are developing at such a pace that one cannot possibly assign a textbook to cover all the relevant topics. However, there are some excellent and **free** books that can act as a springboard to further exploration. In terms of machine learning the main source that we will use is [*Introduction to Statistical Learning*](http://faculty.marshall.usc.edu/gareth-james/ISL/) by Gareth James, Daniela Witten, Trevor Hastie (a fellow South African) and Robert Tibshirani. This book is truly an inspiring introduction to the field of statistical learning and gives an intuitive overview of some of the crucial concepts you are likely to encounter as a data scientist. 

The code for the book is presented in `R`, but I will provide Python code to replicate the labs and figures in the book, so that you can see how we can use different languages to solve the same problem. I will also be borrowing from other books to compile these notes and will reference those as we proceed.

For those students that want higher level coverage of the work that we will be doing I recommend the following textbooks. 

[*Probabilistic Machine Learning: An Introduction*](https://github.com/probml/pml-book/releases/latest/download/pml1.pdf) by Kevin Murphy

[*Pattern Recognition and Machine Learning*](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) by Christopher Bishop

[*Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/download.html) by Trevor Hastie, Robert Tibshirani and Jerome Friedman

The books mentioned above cover the basic mathematical foundations and deal with machine learning topics. However, for the sections on parallel programming and cloud computing, as well as the section on databases, I am not going to rely on specific textbooks. References will be provided as needed here. 
