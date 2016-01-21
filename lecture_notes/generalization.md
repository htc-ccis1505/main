---
layout: notes
---
# Abstraction & Generalization
Last week we talked about the idea of computational thinking and listed several key principles we'd be discussing in this course:

- generalization
- abstraction
- decomposition
- creativity
- data and information
- algorithms

We talked a bit about abstraction last week.  Let's see what you remember...  
(Please start with your name as you answer lecture/discussion questions.)

## Generalization
This week we are going to discuss generalization which overlaps a bit with the idea of abstraction.  As you make something more abstract and remove details, often you are also generalizing as you do this.  But abstraction is really more about the hiding of the details or establishing that *line* at which you don't need to know what the details below that line are.  Generalization is more concerned with finding common ground between various things or situations, allowing us to make a general form - a sort of template - for them.

<blockquote>
1. a. To reduce to a general form, class, or law.<br>&nbsp;&nbsp;&nbsp;
   b. To render indefinite or unspecific.<br>
2. a. To infer from many particulars.<br>&nbsp;&nbsp;&nbsp;
   b. To draw inferences or a general conclusion from.<br>
3. a. To make generally or universally applicable.<br>&nbsp;&nbsp;&nbsp;
   b. To popularize.<br>
~<a href="http://www.yourdictionary.com/generalize">American Heritage® Dictionary</a>
</blockquote>

## Data Types & Objects

### Simple Types
One way that we can generalize relates to *things*.  For example some general types of data we work with in computing includes:

- numeric data
- text or character data
- date / time data

Different computer systems and different programming languages might define these differently, but most have a way to work with each of these different data types.  

These are very general groupings, and they are often broken down into more specific groups.  For example we might generalize numbers such as 1, 2, 4, 0, -10 into a *data type* (usually) called an integer and generalize numbers such as 1.2, 4.5, -3.0 into a different data type usually called a *float* or floating-point (for the point or decimal).

Character data is a bit more complex as there are different ways to map the letters and symbols that we use to read and write into a format that can be stored in the computer.  There are several different ways to *encode* character data - EBCDIC (mainframes used this), ASCII (personal computers used this but not so great for non-English characters), unicode (standard that represents characters from most languages).

While the number 1 and the character of 1 look visually the same, they are very different to a computer as they are different data types.  A very common beginners mistake in programming is to forget this.

### Complex Types
We can make generalizations about more complex things too.  I teach several *specific* courses here, but from what I know about those specific courses, I could outline a sort of general course:

- Course name
- Department
- Course number
- Section number
- Number of credits
- Description

Those are things (or data) that each course should have, and some may be the same as other courses and some may be different.  We can use that general idea of a course as a template for the layout of a course catalog or website, or use it as a form to fill in details for making a new course. (Neither of which *needs* to be in any way computerized, though today it would seem almost silly not to.)  

When we generalize things like this in computing, we often call them objects.  We'll talk more about objects later in the semester.  Not all such generalizations are objects though,

## Actions
Another way that we generalize involves actions.  Recipes are a good example - at least some are.  Let's talk sandwiches...  at least the cold lunch box kind Mary got in school.  I got ham sandwiches, turkey sandwiches, sometimes chicken sandwiches, and the rare meatloaf sandwiches.  

Let's look at my mom's sandwich recipes:

1. Ham Sandwich:  Take a slice of bread, add 2 slices of ham, top it with another slice of bread.  
2. Turkey Sandwich:  Take a slice of bread, add 2 slices of turkey, top it with another slice of bread.
3. Chicken Sandwich:  Take a slice of bread, add some bits of chicken, top it with another slice of bread.
4. Meatloaf Sandwich: Take a slice of bread, add 2 slices of meatloaf, top it with another slice of bread.

We better stop there or I might have nightmares...  That's 4 unique recipes right?  Or is it... what if we generalize a bit.

Mom's sandwich recipe:  Take a slice of bread, add meat, top it with another slice of bread
(We had a big celebration when we later got her to add cheese...)

OK, so my school lunch nightmares aside...  We can do this for lots of things, right?  What other examples can you think of?  Non-food/recipe ones?

### Functions
A function is a way to generalize an action in computing.  Examples might be making a sandwich (I'm sure somewhere robots do this...), adding two numbers, saying hello to someone in the chat room (Slackbot), or drawing a shape.

A good function has a few characteristics:

- descriptively named
- it is generalized - repeatable & reusable
- conceptually, it does a single thing
- it is independent - testable in isolation

Keep these characteristics in mind as you are working on your practice assignments and projects.  

For the most part, the labs tell you where and when to make a function, but for the assignments you have to figure out where to make them yourself.  Your grade will not be as high if you do not make and use functions.  

## Composition
When you have a function that does one thing, you might want to use it as part of another function that does something bigger.  Using one function inside of another function is called composition.

Going back to the sandwich making...

- The “make sandwich” function might be used by the “make lunch” function
- The “make lunch” function might also be used by the “get ready for school” function
- It’s even possible the “get ready for school” function does nothing but use other functions.


 
