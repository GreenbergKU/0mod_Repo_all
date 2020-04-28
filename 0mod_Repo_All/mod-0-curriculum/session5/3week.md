---
layout: page
title: Session 5
subheading: Attention to Detail, Iteration, and Assessment Expectations
---

<div class="goals-agenda">
  <div>
    <h3>Goals</h3>
    <strong>By the end of this session, you will be able to:</strong>
    <ul>
      <li>apply strategies to identify issues in syntax and style</li>
      <li>define iteration in programming</li>
      <li>demonstrate iteration in real-world and programming situations</li>
      <li>understand assessment expectations</li>
    </ul>
  </div>
  <div>
    <h3>Agenda</h3>
    <ul>
      <li><strong>10 min: </strong>Follow-Ups and Goals</li>
      <li><strong>25 min: </strong><a href="#mockassessment">Mock Assessment Follow ups</a></li>
      <li><strong>35 min: </strong><a href="#attention-to-detail">Attention to Detail</a></li>
      <li><strong>5 min: </strong>Break</li>
      <li><strong>35 min: </strong><a href="#iteration">Iteration</a></li>
      <li><strong>15 min: </strong><a href="#assessmentprev">Assessment Preview</a></li>
    </ul>
  </div>
  <div>
    <h3>Materials</h3>
    <ul>
      <li>Notebook</li>
      <li>Writing instrument</li>
      <li>Laptop</li>
      <li>Headphones & mic</li>
    </ul>
  </div>
</div>

## Housekeeping and Goals

### Wins

- Great work asking questions in the public channel!
- Answering questions in the public channel is the best way to solidify your learning and practice communicating technically
- Many Git diagrams were posted early. Way to stay on top of things!

### Follow-Ups

- Look through some of your classmate's git diagrams after class. Maybe they described things in a way you never thought of.
- Ellen and Bob are going to be sitting in on the lesson and managing the chat today!
- Capstone study session tomorrow. Be sure to emoji rsvp!

### Today's Goals

(See above)

## Intros, Review, and Icebreaker

<div class="try-it">
  <h3>Intros, Review, and Icebreaker</h3>
  <p>Person with the shortest first name goes first.</p>
  <p>1. Introduce yourself: name, pronouns</p>
  <p>2. What is a book, tv show, or movie that you've read/watched recently and really enjoyed? Why?</p>
  <p>3. Accountability review: what tangible progress have you made toward your mod 0 focus skills?</p>
  <p>4. Determine who will bring your breakout group questions back to the whole group</p>
  <p>Have extra time? Share what extra things you're doing to get ready to start school at Turing.</p>
</div>

<a name="mockassessment"></a>
## Mock Assessment Follow-up

This is a great time to ask for clarity on expectations or even some feedback on your responses.

The most common issues we run into that leave people pending on the assessment are as follows:
  - method definitions are too broad and don't actually change an attribute or create a return value
  - values aren't filled in properly, using proper syntax for a particular data type
  - format of the top down design portion is wildly off. Only use markdown if you're really comfortable

<div class="try-it">
  <h3>Try It: Assessment Review (~10 minutes)</h3>
  <p>Clone down <a href="https://github.com/damwhit/m0-mock-assessment">this repo:</a></p>
  <p>With the rules above in mind, what is wrong with class 1 and the class 1 example object?</p>
  <p>What about class 2 and the class 2 example object?</p>
  <p>Fix everything? Create a new example object</p>
</div>

<a name="attention-to-detail"></a>
## Attention to Detail

After reflecting on and trying to find patterns for the people who are struggling in mod 1, we've identified that attention to detail is one of the main themes we've seen.

Attention to detail is something that constantly comes up when coding
* A missing or misplaced character can make your code behave in an entirely different way
* Documentation is super dense, you'll likely need to read it at least couple of times before you're able to understand and apply it
* Tutorials and directions for implementation are common place. If you miss one step, you won't get the same result

### Identifying Mistakes

#### Breakout Groups (10 minutes)
Go through the following examples, and determine whether or not each piece of code is syntactically correct. Even if the line of code is syntactically correct, are there any other mistakes in it?

Be sure to pay attention to how your capstone is formatted. If people have poorly formatted gists and repos for their capstone, it is a bit of a red flag on our end for this reason.

As a group, either in your text editors, or in a notebook, write down your answers for each number below. Be sure to deliberate as a group and try your best to explain **why** you expect something to work or not.

```
1. bestFoodOfAllTime = 'burritos'

2. isIt = true

3. secondBestFood = 'ramen'

4. sandwich = "taco?'

5. phoneNumber = '123-456-7890'

6. bestFoodOfAllTime

7. isLying = False

8. animals = ['donkey', 'giraffe', 'elephant', 'chimpanzee']

9. secondBestfood

10. sandwiches = ['cheesesteak', 'po' boy', 'reuben']

11. drinkSize = 12 oz

12. ,2 * 2

13. 4 / 2

14. (6 * 2) + (6 / 3) / 6)

15. grads = { "9th grade": 110, "10th grade": 125, "11th grad": 66 }

16.
instructors = {
  "Mod 0": "Tim and David",
  "Mod 1": 'Mike and Sal",
  "Mod 2": "Brittany and Robbie"
}
```

What were your strategies when trying to figure out if a piece of code is syntactically correct or not?

Did you do any experimentation? Did you reference any documentation?

Key things to think about when looking for syntax errors:
* parentheses, quotes, brackets, and braces are all like shoes, useless without their mate
* consistency is key. If you're looking through code that has inconsistent, indentation, casing, quote types some mental overhead is being used where it doesn't need to be

### Syntax and Style

<span class="vocab">Syntax</span> and <span class="vocab">Style</span> are both essential when it comes to writing code.

<span class="vocab">Syntax</span> refers to the structure of statements in a computer language. Are quotes surrounding both sides of a string? No, then the language will throw an error. If your code isn't working because of a placement of a character, it's a syntax issue.

<span class="vocab">Style</span> doesn't determine if a piece of code runs or not. Its purpose is to make code more readable. Ideally, when you're working on a team, you and your teammates are following similar patterns (conventions) when it comes to things like whitespace (including indentation) or double vs single quotes. What is one of those conventions you've already been using?

Let's take a look at what these two things might look like in action:

Difference in syntax

```
one doesn't work

animals = ['donkey', 'giraffe', 'elephant', 'chimpanzee']

animals = ['donkey', 'giraffe', 'elephant' 'chimpanzee']
```

Difference in style

```
both work below, but which reads better?

animals = ['donkey', 'giraffe', 'elephant', 'chimpanzee']

animals=["donkey",'giraffe','elephant',"chimpanzee"]
```

If you want to find code that is both syntactically correct and using good style the best place to look is going to be the docs (mdn for JavaScript and ruby-doc for Ruby). The code examples are a great place to look to see if you are writing your code in a similar way. Also, keep in mind that things like casing of variables is another good way to stay consistent and maintain good style.

## BREAK

Turn off your mics and videos and walk away from the computer. Stand up, stretch, drink water. Do a few sit-ups, squats, push-ups, jumping jacks, arm circles, stress ball squeezes, or whatever else moves your body.
<hr>

<a name="iteration"></a>
## Iteration

Iteration (or looping for a specified number of times) is a process of repeating a task for each object in a collection. For each of the scenarios below, we'll walk through using props to demonstrate the concept.

### Iteration in Real Life

These are examples that would be programatically challenging because they would require a ton of steps, but are things that we do everyday.

<table>
  <thead>
    <tr>
      <th>Scenario</th>
      <th>Collection</th>
      <th>For each...</th>
      <th>Do this:</th>
      <th>Then:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Grading papers</td>
      <td>papers</td>
      <td>paper</td>
      <td>
        <ol>
          <li>read through it</li>
          <li>mark the score on the top</li>
        </ol>
      </td>
      <td>repeat with next paper</td>
    </tr>
    <tr>
      <td>Feeding animals</td>
      <td>animals</td>
      <td>animal</td>
      <td>
        <ol>
          <li>bring the animal to the food bucket</li>
          <li>allow the animal to eat</li>
          <li>bring animal back to barn</li>
        </ol>
      </td>
      <td>repeat with next animal</td>
    </tr>
  </tbody>
</table>

### Iteration in Programming

By "in programming", we mean things that could be done, with relative ease, by a computer. Like crunching numbers.

<table>
  <thead>
    <tr>
      <th>Scenario</th>
      <th>Collection</th>
      <th>For each...</th>
      <th>Do this:</th>
      <th>Then:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Calculating max heart rate</td>
      <td>birth years</td>
      <td>year</td>
      <td>
        <ol>
          <li>subtract birth year from 2019 to get age</li>
          <li>subtract age from 220</li>
        </ol>
      </td>
      <td>repeat with next year</td>
    </tr>
    <tr>
      <td>Formatting names</td>
      <td>names</td>
      <td>name</td>
      <td>
        <ol>
          <li>capitalize the first letter</li>
          <li>lowercase all remaining letters</li>
        </ol>
      </td>
      <td>repeat with next name</td>
    </tr>
  </tbody>
</table>

<div class="try-it">
  <h3>Try It: Iteration in Real Life and Programming</h3>
  <p>Brainstorm a real life scenario that uses iteration. Fill out the table below and be ready to share.</p>
  <table>
    <thead>
      <tr>
        <th>Scenario</th>
        <th>Collection</th>
        <th>For each...</th>
        <th>Do this:</th>
        <th>Then:</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
      </tr>
    </tbody>
  </table>
  <p>Think back to your grocery store app. What is something you said you'd keep inside of an array? Why might you need to iterate over that collection? Jot down your scenario below.</p>
  <table>
    <thead>
      <tr>
        <th>Scenario</th>
        <th>Collection</th>
        <th>For each...</th>
        <th>Do this:</th>
        <th>Then:</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
        <td><textarea rows="4"></textarea></td>
      </tr>
    </tbody>
  </table>
</div>

### Iteration Syntax

We'll go into breakout rooms to briefly discuss the syntax for iterating in Ruby and JavaScript.

<div>
  Are you a <button class="iteration-toggle" id="fe-show">front end</button> or <button class="iteration-toggle" id="be-show">back end</button> student?
<div class="hidden fe-iteration">
  <p>The code that you see below is written using JavaScript. This syntax is something that you'll see all over the place, so it's important to get used to it. You don't need to memorize every little symbol for now, but knowing how to explain the big pieces is important.</p>
  <h4>Example #1: Grading papers for five students</h4>
  <iframe height="350px" width="100%" src="//repl.it/@rwarbelow/mod0iterationJS1?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
  <div class="things-to-note">
    <h4>Things to Note: For Loop Vocabulary</h4>
    <ul>
      <li><code>var students = ['Megan', 'Jose', 'Xavier', 'Ali', 'Miriam'];</code><br> We use Javascript keyword <code>var</code> to <span class="vocab">declare</span> a <span class="vocab">variable</span> <code>students</code> and assign the <span class="vocab">array</span> of <span class="vocab">strings</span> to the <span class="vocab">variable</span> <code>students</code>.</li>
      <li><code>for (i = 0; i < students.length; i++)</code><br> We use Javascript keyword <code>for</code> to begin setting up our <span class="vocab">for loop</span> which we will break down further.</li>
      <li><code>i = 0;</code><br><span class="vocab">Declare</span> our <span class="vocab">variable</span> <code>i</code> and assign it to the <span class="vocab">integer</span> 0</li>
      <li><code>i < students.length;</code><br> We set up our <span class="vocab">conditional</span> statement that the <span class="vocab">for loop</span> will evaluate before entering the loop. On the first run through <code>i = 0</code>, so this statement evaluates to <code>0 < students.length;</code>, which can be broken down further to <code>0 < 5</code>, which evaluates to true. Think of <span class="vocab">conditionals</span> as questions that always evaluate to true or false.
      </li>
      <li><code>i++</code><br>Our <span class="vocab">incrementer</span> that will add one to i each time we pass through the loop. Another way to think about it is each time <code>i < students.length</code> is true we will increment <code>i</code> by one for the next time we evaluate the <span class="vocab">conditional</span> <code>i < students.length</code> So, after we've run through the <span class="vocab">for loop</span> once, the <span class="vocab">for loop</span> looks like this: <code>(i = 1; i < students.length; i++)</code> the second time through. This can break down further to <code>(i = 1; 1 < 5; i++)</code></li>
      <li><strong>Curly Brackets or Curly Braces:</strong>
      <code><br>
        {
          Within these brackets is where we do some kind of programming/logic to each element of our collection within our loop
        }
      </code><br>
      <strong>Todo:</strong> Google <code>console.log</code> and other console methods that are available to you in a Javascript console.</li>
      <li><code>students[i]</code><br> Access the <span class="vocab">element</span> of the <code>students</code> <span class="vocab">array</span> at <span class="vocab">index position</span><code>i</code> which will change as <code>i</code> changes and we increment through the <span class="vocab">for loop</span>
      As we move through the loop this breaks down to <code>students[0]</code>, next time through the loop: <code>students[1]</code>, next time through the loop: <code>students[2]</code> ...</li>
  </ul>
</div>

  <h4>Example #2: Multiplying By Six</h4>
  <iframe height="350px" width="100%" src="//repl.it/@rwarbelow/mod0iterationJS2?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
  <div class="try-it">
    <h3>Try It: Iteration Syntax</h3>
    <p>Fill in the missing pieces of the iteration example below:</p>
    <iframe height="350px" width="100%" src="//repl.it/@rwarbelow/mod0iterationJS3?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
    <p>Fill in the missing pieces of the iteration example below:</p>
    <iframe height="350px" width="100%" src="//repl.it/@rwarbelow/mod0iterationJS4?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
  </div>
</div>
<div class="hidden be-iteration">
  <p>The code that you see below is written using Ruby. This syntax is something that you'll see all over the place, so it's important to get used to it. You don't need to memorize every little symbol for now, but knowing how to explain the big pieces is important.</p>
  <h4>Example #1: Grading papers for five students</h4>
  <iframe height="350px" width="100%" src="//repl.it/@rwarbelow/mod0iterationRuby1?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
  <h4>Example #2: Multiplying By Two</h4>
  <iframe height="350px" width="100%" src="//repl.it/@TimTyrrell1/RubyExampleNumberIteration?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
  </div>
</div>

<a name="assessmentprev"></a>
## Mod 0 Technical Assessment

This is our final Mod 0 technical session. Your assignment between now and Thursday is to find 80 minutes  to complete the [Mod 0 Technical Assessment](https://fierce-beyond-34376.herokuapp.com).

<div class="instructions assessmentpreview">
  <h1>SAMPLE INSTRUCTIONS</h1>

  <p>This work portion assessment should take you approximately 70 minutes, but we recommend taking an additional 10 minutes to throughly read over the expectations outlined in this document. The timed nature is meant to get you used to working under pressure.</p>

  <p class="important"><strong>First,</strong> fork the assessment checklist. You will use this checklist to ensure that you have met the Mod 0 Technical Assessment expectations.</p>

  <h4>Part I: Creating Directories and Files; Initializing Git and Pushing to GitHub (10 min)</h4>

  <ol>
    <li>Use your terminal to create a directory called <code>...</code></li>
    <li>Inside of that directory, make an empty text file called <code>...</code></li>
    <li>Initialize your directory as a git repository.</li>
    <li>Add your file and commit using the message "Initial commit"</li>
    <li>Create a public repo on Github with the same name.</li>
    <li>Add the remote and push your local repository to Github.</li>
  </ol>

  <h4>Part II: Top Down Design (25 min)</h4>

  <ol>
    <li>Open up your <code>...</code> file in your text editor.</li>
    <li>Break down the process of <code>...</code> <small>(We will leave the situation intentionally vague so that you can choose what angle you feel most comfortable with. Although we are not looking for a specific "answer" for how you break this down, you should be as detailed as possible. It is better to break things down too much than to oversimplify a process. Use the same process and notation that we used during Session 5 with a dash mark and one indent for every new layer.)</small></li>
    <li>Save your file.</li>
    <li>Add and commit your changes.</li>
    <li>Push your changes to Github.</li>
  </ol>

  <h4>Part III: Classes, Objects, Attributes, and Methods (35 min)</h4>

  <ol>
    <li>Inside of <code>...</code>, create a new directory called <code>...</code></li>
    <li>Inside of <code>...</code>, create four files: <code>...</code>, <code>...</code>, <code>...</code>, and <code>...</code><em>(If you're comfortable trying markdown at this point, feel free to use .md instead of .txt).</em> </li>
    <li>Open up <code>...</code> in your text editor.</li>
    <li>Brainstorm one class that might exist in a <code>...</code> and put this at the top of the file.</li>
    <li>List at least four attributes for that class. In parentheses, list the data type for that attribute (string, boolean, integer, float, hash/object, datetime).</li>
    <li>List at least four methods for that class. In parentheses, explain what the method does, including the names of the attributes that it uses or modifies.</li>
    <li>Save your file.</li>
    <li>Add and commit your changes for this class.</li>
    <li>Open up <code>...</code> in your text editor.</li>
    <li>At the top, type the name of an object that is an instance of your class.</li>
    <li>List the values for each attribute.</li>
    <li>List the results of the method being called for this specific object.</li>
    <li>Save your file.</li>
    <li>Add and commit your changes for this class.</li>
    <li>Repeat steps 3-8 with <code>...</code></li>
    <li>Repeat steps 9-14 with <code>...</code></li>
    <li>Push your changes to GitHub.</li>
  </ol>

  <h4 class="important">Done?</h4>
  <p>There is a link to a google form where you'll submit your mod 0 assessment repo at the end of your checklist</p>
</div>

### Other Reminders

* This is your last technical session, next session will be with Emma, where she'll talk more about life in person at Turing
* When you start working on Mythical Creatures in Mod 1, think back to OOP, classes and methods in mod 0
* Moving forward:
  * Keep up the hard work
  * Keep asking questions in your cohort channels
  * Tim, Ellen, Bob and I are still around if you need us
  * Capstone is due in Three weeks - check your calendar, and don't forget to rsvp for the study session tomorrow!

> Quote from Meg Stang (BE instructor) - "I've noticed that the students that do the bare minimum on their mod 0 prework are the ones that usually struggle for at least the first half of the mod."
