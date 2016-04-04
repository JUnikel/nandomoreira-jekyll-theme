---

layout: post
title: "Ruby Classes"
date: 2016-4-4
description: "Blog Post: Ruby Classes"

---

Ruby Classes: Blog Post

When coding in Ruby, organization is the key to a successful program and an effective result. Though Ruby gives the programmer access to a plethora of commands and methods, certain methods have proven to be faster and more accessible in different situations. Object Oriented Design is one of these methods of coding. While it has disadvantages in specific situations, Object Oriented Design is an easy and reliable way to organize methods and objects through the use of classes.
A class gives the programmer the ability to sort objects into predefined methods that can be easily called later in the code. This means that a user can create a complicated or important method at the beginning of the code and access it many more times throughout the program. This is a key component of the organization of a text as it completely eradicates repetition – important pieces of the code can be confined to a single line and therefore can be found with ease when reviewing or editing later on. However, this type of coding is not without its drawbacks: in relatively short or non-repetitive code, it can be difficult, long, or even unnecessary to use classes as they have no use later in the code. 
The code at the bottom of this post is an example of a very simple class with two different methods. To begin, the class is defined (“Greeting” indicates the name of the class). Within this class there are two methods, “introduce” and “farewell.” The code inside of these methods is what will be performed when the programmer calls upon those methods later on. The class then ends and is followed by the creation of a new instance of this class, “newgreeting.” Once this is complete, the user can call upon those methods any number of times. 
Evident by its simplicity and organizational strength, Object Oriented Code is a viable and useful way to shorten long and complicated code. It should certainly possess a place in the tool belt of all programmers working in Ruby. 

	class Greeting
		def introduce(name)
			@name = name
			puts "Hello, #{@name}!"
			puts "I am your computer and I am here to help."
		end

		def farewell
			puts "Bye, #{@name}!"
			puts "It was nice to meet you!"	
		end

	end

	newgreeting = Greeting.new

	newgreeting.introduce("Jackson")
	newgreeting.farewell



Sources:
http://phrogz.net/programmingruby/tut_classes.html

http://www.tutorialspoint.com/ruby/ruby_classes.htm

http://www.wellho.net/solutions/ruby-basic-class-definition-and-use-in-ruby.html


