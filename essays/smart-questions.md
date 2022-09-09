---
layout: essay
type: essay
title: "Asking the Right Questions, the Smart Questions!"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

## Is there such thing as a stupid question?

We've all heard of the saying "In the wrong place at the wrong time" but have you ever heard of "the wrong question at the wrong time?" Of course not, but if you have, maybe what was being asked wasn't a smart question. Asking help from others is an invaluable resource that should be taken advantage of whenever the opportunity arises like in a class when you didn't quite understand a topic that the professor just went over. Instead of asking the professor to simply repeat that last part, it is more beneficial to specify where the disconnect of knowledge happened such as not understanding how a class works in JavaScript. While you can ask if they could go over classes again, if the confusion lies within constructors, ask specifically about constructors like when do we have variables in the constructor or when do they don't? The point is, asking questions doesn't hurt but asking smart questions are guaranteed to benefit you and will prove to be a valuable resource.

## Smart Question vs This?
### var functionName = function() {} vs function functionName() {}

```
I've recently started maintaining someone else's JavaScript code. I'm fixing bugs, adding features and also trying to tidy up the code and make it more consistent.

The previous developer used two ways of declaring functions and I can't work out if there is a reason behind it or not.

The two ways are:

var functionOne = function() {
    // Some code
};
function functionTwo() {
    // Some code
}

What are the reasons for using these two different methods and what are the pros and cons of each? Is there anything that can be done with one method that can't be done with the other?
```
 
Going through Stack Overflow, I stumbled upon this post asking the difference between these two ways of declaring functions. At first, I was going to skip this post and look for a longer post because my initial thoughts were longer post equals smarter question but upon reviewing it more, I realized that this was a smart question. The author had a title that encapsulates the question being asked, a base level of knowledge and supporting background information was provided, and overall seems like a genuine question that they wanted clarification on from someone who is more knowledgable on the topic.
[Link to Post 1](https://stackoverflow.com/questions/336859/var-functionname-function-vs-function-functionname)

### What do nth prime of a number mean?
```
Given an input n, find out the nth prime?

MyApproach

What I understood

For Example,

For number 2 its nth position is 1

For number 3 its nth position is 2 // For this input I get Expected output 5.

For number 5 its nth position is 3

public int computePrime(int n)
{
    int c=0;
    boolean b=isPrime(n);
    if((b==true))
    {
        c++;
    }
    return c;

    //write your code here

}
public boolean isPrime(int n)
{

    for(int i=2;i<=n/2;)
    {
        if(n%i==0)
        {
            i++;
        }

    }
    return true;
}
For Input

Parameters  Actual Output   Expected Output
'3'          1               5
My Qn is Can anyone guide me what the statement mean.Am I correct in understanding the problem.I am not asking you to code for me.I will do it
```
On the opposite end of the smart question spectrum would be this post, asking "What do nth prime of a number mean?" First off, the title doesn't have proper grammar but let's give it the benefit of the doubt and continue reading. It is pretty obvious even without them forming full sentences that they have some confusion and would would like clarification about the nth prime of a number. However, a code snippet is also included in the post without any specific requests or background on it which misleads commenters into believing that the author would like help with the code since Stack Overflow is a coding forum after all. This leads the author to become combative in the replies to comments including code that others took their time to post. 
[Link to Post 2](https://stackoverflow.com/questions/33595892/what-do-nth-prime-of-a-number-mean)

### Differences between the two questions
I wanted to talk about these two questions because of the two constrasting feelings with the posts. As I mentioned earlier, the first post was clear, concise, and seemed like the author has a genuine question that they wanted advice on. Compared to the not so elegant second post, the author was more aggressive and rude when it came to the reponses they got. You could also see the difference between the two questions through the quality of responses each post got as the first post had much more lengthy comments from people who wanted to help clear up any confusion that the author had while the second post when had someone straight up say "Ever heard of google?"

## Smart Questions, Smarter Me
When it comes to smart questions, I hope to never be like the author of the second post. Just the way that the author was so aggressive to the people helping them does not sit right with me and shouldn't be encouraged and also reinforces the idea of communication is key. Without properly expressing the goal of their question, one cannot receive the proper answers that they are seeking. This also includes providing useless or irrelevant information in the post or replies to other comments as it does not provide any value and takes away from the post.

Another take away for me would be how to present myself online as the people who are taking their own time to help me out with any future questions that I might have, I should be respectful and appreciate that they are willing to help. I wouldn't want to be viewed as aggressive or combative like the author of the second post and wouldn't want to seem unprofessional as well since a lot of these commenters are much more knowledgable than me. #humbled

This picture sums up what I learned. But now I know how to fix them.
<img width="300px" class="rounded float-start pe-4" src="../img/smart.jpeg">

