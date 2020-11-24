# FullStackReact
A full stack React website with Mongodb and express server

To Run this project , you will need to have NPM installed on your computer and mongodb setup already
The Name of the collection for this projects is called articles and the database only contains the name of the article as "name", "upvotes" and "comments" array.
comment is acutally an array with two field of username and text.

name should match the excat name of the blog which is being loaded from article-content.js
A Sample data to be created in Mongodb would look like this:

{

	"name" : "learn-node",
	"upvotes" : 2,
	"comments" : [
		{
			"username" : "David",
			"text" : "I Love this article !!!"
		},
		{
			"username" : "Sammy",
			"text" : "Keep up the Good Work"
		},
		{
			"username" : "Josh",
			"text" : "Nice Work!"
		}
	]
}

// Where learn-node is the name of the articles that's present in article. 

Your can definetly make this project better by adding log-in functionality that would track the people who upvoted the article and comment. so GoodLuck !!!
