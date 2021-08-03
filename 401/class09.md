## Dunder Methods

### What Are Dunder Methods?

* In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end
with double underscores, for example `__init__ or __str__.`
* As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”
* These “dunders” or “special methods” in Python are also sometimes called “magic methods.
* Dunder methods let you emulate the behavior of built-in types
* Object Initialization: `__init__` : 
  * Right upon starting my class I already need a special method. To construct account objects from the Account class I need a constructor
  which in Python is the` __init__ dunder`
* `__repr__` :  The “official” string representation of an object. This is how you would make an object of the class. The goal 
of` __repr__ `is to be unambiguous.

* `__str__`: The “informal” or nicely printable string representation of an object. This is for the enduser.
* `Callable Python Objects: __call__ `: You can make an object callable like a regular function by adding the` __call__ dunder` method


**Special Methods and the Python Data Model**

* This elegant design is known as the Python data model and lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access, etc.

* You can see Python’s data model as a powerful API you can interface with by implementing one or more dunder methods. If you want to write more Pythonic code, knowing how and when to use dunder methods is an important step.


**Enriching a Simple Account Class**
- Throughout this article I will enrich a simple Python class with various dunder methods to unlock the following language features:

1. Initialization of new objects
2. Object representation
3. Enable iteration
4. Operator overloading (comparison)
5. Operator overloading (addition)
6. Method invocation
7. Context manager support (with statement)

**Object Initialization: __init__**
Right upon starting my class I already need a special method. To construct account objects from the Account class I need a constructor which in Python is the __init__ dunder:
```
class Account:
    """A simple account class"""

    def __init__(self, owner, amount=0):
        """
        This is the constructor that lets us create
        objects from this class
        """
        self.owner = owner
        self.amount = amount
        self._transactions = []
```

##### What is probability?
At the most basic level, probability seeks to answer the question, “What is the chance of an event happening?” An event is some outcome of interest.
To calculate the chance of an event happening, we also need to consider all the other events that can occur. 
The quintessential representation of probability is the humble coin toss. In a coin toss the only events that can happen are:
* Flipping a heads.
* Flipping a tails.


##### The data and the distribution
Intuitively, we’d like to use the scores of the wines to compare groups, but there comes a problem: the scores usually fall in a range. 
How do we compare groups of scores between types of wines and know with some degree of certainty that one is better than the other? 
Enter the **normal distribution**. The normal distribution refers to a particularly important phenomenon in the realm of probability and statistics.

In a probability context, the high point in a normal distribution represents the event with the highest probability of occurring. 
As you get farther away from this event on either side, the probability drops rapidly, forming that familiar bell-shape. 
The high point in a statistical context actually represents the mean. As in probability, as you get farther from the mean, you rapidly drop off in frequency. 
That is to say, extremely `high` and `low` deviations from the `mean` are present but exceedingly rare.

If we visualize each group of scores as normal distributions, we can immediately tell if two distributions are different based on where they are.
We assume the scores will be normally distributed since we have a ton of data.

**Revisiting the normal**
* The normal distribution is significant to probability and statistics thanks to two factors: the Central Limit Theorem and the Three Sigma Rule.

 - **Central Limit Theorem**
In the previous section, we demonstrated that if we repeated our 10-toss trials many, many times, the average heads-count of all of these trials will approach the 50% we expect from an ideal coin. With more trials, the closer the average of these trials approach the true probability, even if the individual trials themselves are imperfect. This idea is a key tenet of the Central Limit Theorem. In our coin-tossing example, a single trial of 10 throws produces a single estimate of what probability suggests should happen (5 heads). We call it an estimate because we know that it won’t be perfect (i.e. we won’t get 5 heads every time).

