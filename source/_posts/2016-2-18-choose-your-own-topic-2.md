---

layout: post
title: "Choose your own topic: case vs. if"
date: 2016-02-18
description: "Blog Post: Choose your own topic"

---

Case vs. If: Blog Post


	Ruby offers users a plethora of options when it comes to organization, structure, and function. For every possible outcome, there are numerous ways of achieving the desired result. Methods in particular offer a number of strategies for obtaining said result, thereby leading to discrepancies when answering the question of which method is the most efficient. This is especially true of the if/else statement and the case statement. In this post, we will examine both methods and determine which is more efficient for different situations. 
	The if/else statement is an easily readable and effective method for comparing values against specified criteria. It is structured in a way that reads “if A meets the criteria of B, function C will occur. Otherwise, D will occur.” A program that includes an if statement will check to see whether or not A does in fact meet B’s specifications. If this statement yields a positive result, the following function C will be performed. If A is not within the parameters of B, function D will be performed instead. If statements are easily readable, as they are built in a way that resembles a complete statement in English, therefore making it easy to change, however it can be cumbersome to write if statements for a high number of objects.
	The case statement is a different effective method within Ruby and is similarly used to compare values. The structure of this method establishes two variables: the case and the result. Using a series of when statements, this method then cross-checks a series of paired cases and results. If at any point, the desired result is found, it’s respective case will be matched and the method will establish those as the new values of the variables. Clearly, this method is much more complex than the seemingly simple if/else statement above. This is generally true, yet case statements prove to be significantly more useful when utilizing a multitude of values/variables. Instead of having to write out if statements for every value, the case statement provides a faster alternative. 
	In short, while each method possesses its benefits and costs, if statements are an easily readable and functional method for shorter and less intensive situations whereas case statements can be very effective methods for longer, more complicated situations. 

Sources:
http://midwire.github.io/blog/2011/08/26/ruby-performance-case-vs-if-elsif/
http://www.daniellesucher.com/2013/07/ruby-case-versus-if/
http://www.techotopia.com/index.php/The_Ruby_case_Statement