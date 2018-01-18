Utts & Heckard CH07
========================================================
author: Created by: Jill E. Thomley
date: Updated: 2018-01-17 20:22:48
autosize: true



Random Circumstance
========================================================

A **random circumstance** is a scenario in which the exact outcome is unpredictable. There are two kinds of random circumstances we can think about.

*  The outcome is not determined until we observe it. 

Example: whether the coin flip at the start of a football game turn out to be heads or tails.

*  The outcome has been determined, but our knowledge of the outcome is uncertain. 

Example: whether or not someone has a BRCA or PALB2 gene mutation. They have it or they do not, but we do not know until we do a test.



What are the Chances?
========================================================

While we cannot predict exactly what will happen for any given random circumstance, we can often determine a set of possible outcomes and attach a **probability** to each outcome.

Sometimes, the probabilities of the outcomes for a given random circumstance depend on another random circumstance. 

Example: the chance of being injured in a car accident depends on whether or not the person is wearing a seatbelt.

We also refer to random circumstances as **random variables** and use them to mathematically model the world. Something that is not random is **deterministic**.



Probability Interpretations
========================================================

For situations that we can imagine repeating many times, the probability of an outcome is the fraction of the time it would happen in the long run. We express probabilities as fractions, proportions, or percentages.

*  **relative frequency probabilties** rely on determining how often each outcome occurs relative to the others, based on logical assumptions and theory <u>or</u> on direct observation of events (empirical or experimental probability) 

*  **personal probabilities** (or **subjective probabilities**) rely on an individual's judgment and experience, often when there is not enough data or circumstance is not repeatable



Defining Events 
========================================================

*  A **simple event** is a unique possible outcome of a random circumstance.
*  The **sample space** of a random circumstance is the set of all simple events.
*  A **compound event** is an event that includes two or more simple events.
*  An **event** is a collection of one or more simple events in the sample space.

Later we will talk about **complementary**, **mutally exclusive**, and **independent/dependent** events.



Probability Rules 
========================================================

For a given random circumstance...

*  The probability of any possible outcome is between 0 and 1
*  The sum of the probabilities for all possible outcomes is 1.

Even personal probabilities must be **coherent probabilities**: the values have to be between 0 and 1 and they cannot contradict one another. If you think you have a 20% chance of getting a job, then you should think you have an 80% chance of not getting it. 

Question: What do probabilities of exactly 0 or exactly 1 mean?



Majors of Students
========================================================

This frequency table summarizes the self-identified majors for students in several of Dr. Thomley's previous STT1810 classes.

<table>
 <thead>
  <tr>
   <th style="text-align:center;"> Major </th>
   <th style="text-align:center;"> frequency </th>
   <th style="text-align:center;"> rel_frequency </th>
   <th style="text-align:center;"> percentage </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> Criminal Justice </td>
   <td style="text-align:center;"> 190 </td>
   <td style="text-align:center;"> 0.3909465 </td>
   <td style="text-align:center;"> 39.094650 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> Political Science </td>
   <td style="text-align:center;"> 135 </td>
   <td style="text-align:center;"> 0.2777778 </td>
   <td style="text-align:center;"> 27.777778 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> Nursing </td>
   <td style="text-align:center;"> 60 </td>
   <td style="text-align:center;"> 0.1234568 </td>
   <td style="text-align:center;"> 12.345679 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> Communication Disorders </td>
   <td style="text-align:center;"> 43 </td>
   <td style="text-align:center;"> 0.0884774 </td>
   <td style="text-align:center;"> 8.847737 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> HLES </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> 0.0761317 </td>
   <td style="text-align:center;"> 7.613169 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> Other </td>
   <td style="text-align:center;"> 21 </td>
   <td style="text-align:center;"> 0.0432099 </td>
   <td style="text-align:center;"> 4.320988 </td>
  </tr>
</tbody>
</table>

The total number of students in the dataset is 486.



Genders of Students
========================================================

This frequency table summarizes self-identified genders for students in several of Dr. Thomley's previous STT1810 classes. Note that students were provided with non-binary options, but no students selected them.

<table>
 <thead>
  <tr>
   <th style="text-align:center;"> Gender </th>
   <th style="text-align:center;"> frequency </th>
   <th style="text-align:center;"> rel_frequency </th>
   <th style="text-align:center;"> percentage </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> Male </td>
   <td style="text-align:center;"> 246 </td>
   <td style="text-align:center;"> 0.5061728 </td>
   <td style="text-align:center;"> 50.61728 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> Female </td>
   <td style="text-align:center;"> 240 </td>
   <td style="text-align:center;"> 0.4938272 </td>
   <td style="text-align:center;"> 49.38272 </td>
  </tr>
</tbody>
</table>

The total number of students in the dataset is 486.



An Example 
========================================================

The random circumstance is the major of a selected STT1810 student. The tables on on the previous slides provide a relative frequency probability estimate. 

sample space = {Communication Disorders, Criminal Justice, HLES, Nursing, Political Science, Other}



A = the event that the student is a political science major

P(A) = 135 / 486 = 0.2778 = 27.78%

P(A) is read as "the probability of event A" or "probability of A".



Example Continued 
========================================================



B = student is from Government and Justice Studies

This compound event includes the two simple events "political science" and "criminal justice".

P(B) = (135 + 190) / 486 = 0.6687 = 66.87%



Rule 1: Complement Rule
========================================================

One event is the **complement** of another if they do not contain any of the same simple events and together they contain all the simple events in the sample space. In other words, they do not overlap and together they cover the whole sample space.

B = student is from Government and Justice Studies

B<sup>c</sup> = student is _not_ from Government and Justice Studies

P(B) + P(B<sup>c</sup>) &rarr; P(B<sup>c</sup>) = 1 - P(B) = 1 - 0.6687 = 0.3313

What is the probability that an event does _not_ occur?



Mutually Exclusive
========================================================

Two events are **mutually exclusive** if they do not contain any of the same simple events. By definition, complementary events are mutually exclusive, but not all mutually exclusive events are complementary.

A = the student is a political science major

C = the student is from the Beaver College of Health Sciences

One student cannot belong to both A and C, but together these two events do not include all possible majors.

Question: Is being Male and a Nursing major mutually exclusive?



Male and Nursing Major?
========================================================


```
                         
                          Female Male
  Communication Disorders     41    2
  Criminal Justice            55  135
  HLES                        20   17
  Nursing                     50   10
  Other                       15    6
  Political Science           59   76
```

Question: What would the table entry have to be if they were mutually exclusive?
