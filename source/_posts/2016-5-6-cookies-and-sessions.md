---

layout: post
title: "Cookies and Sessions"
date: 2016-5-6
description: "Blog Post: Cookies and Sessions"

---

Cookies and Sessions

	As I have discussed many times before. Computer science and programming are all about organization and efficiency. Running programs, visiting websites, and creating code all require a level of awareness regarding the types of information you want to be accessed, stored, or created. This task has become increasingly difficult with the exponential increase in technology usage. That is why many programs and websites have begun to use cookies and sessions. 
	HTTP, the protocol used in our everyday internet use, is considered to be a stateless protocol. This means that, within the code, there is nothing that requires the browser to identify itself with each request. Because of this statelessness, it can be difficult for programmers to create a state when it is necessary. This is where cookies come in. Cookies are small bits of information that can be stored on a user’s computer after accessing a page. These pieces of information can then be used on every subsequent visitation. This allows for easy and fast access to a user’s favorite sites. Cookies were very effective for some time, until a major flaw was recognized: the client/user could read these cookies, even though the information within them was only pertinent to the server. This meant that anyone with that information (now much more easily accessed from the client’s computer) could impersonate the user on sites that utilized the cookie’s information
	As a solution, sessions were created. Sessions are identical to cookies, except for the use of session ID’s. Instead of storing the relevant information on a user’s computer, a session ID is stored in its place. Just as a cookie works, when a user accesses a site, the session ID is accessed and correlates to an identical ID on the server side. This allows the server to be the only component that stores information, helping to prevent the impersonation of users.



Sources:
http://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work

http://shiflett.org/articles/the-truth-about-sessions

http://rubylearning.com/blog/2009/09/30/cookie-based-sessions-in-sinatra/


