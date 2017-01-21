# Planning my application
	
	1. Answer Questions
		- What am I building?
		- Who am I building it for?	
		- What features do I need to have?
	2. User Stories
	3. Model my Data
	4. Think Through the pages I need in my app


## Questions

	1. What am I building? I am building a personal site. 
	   A place where I can blog, share examples of my work and 
	   have people contact me.

	2. Who am I building it for? I am building it for myself,
	   but also the community. Sharing what I am learning by 
	   blogging is a great way to learn for myself, but I 
	   teach others in the process. Show potential 
	   employers that I know what I am doing. 

	3. What features do I want to have?
			- Posts
				- Create / Edit / Destroy
			 	- Markdown
			 	- Syntax highlighting
			 	- Comments (Disqus)

			- Projects
				- Create / Edit / Destroy 	
				- Contact 
					- Contact form
					- Sendgrid

			- User (Devise)		


	
## User Stories
	As a blank, I want to be able to blank, so that blank.
		- As a user, I want to be able to create posts so that I can share
		  what I am learning on my blog.
		- As a user, I want to be able to edit & distroy posts, so that
		  I can manage my blog.
		- As a user, I want to be able to write posts in markdown format
		  so that it's easy for me to write posts.
		- As a user, I want to be able to highlight the various syntax of
		  code blocks that I share on my blog.
		- As a user, I want to show the visitors and potential employers
		  examples of my work, or stuff I've built.
		- As a user, I want to able to have visitors contact me through
		  a form on my site.
		- As a user, I want visitors to be able to leave comments on my
		  posts.	         	    


## Modeling my Data

	**Post**
		title:string
		content:string


	**Project**
		title:string
		description:text
		link:string


	**User**

## Think Through the pages I need in my app
	
	- Home

	- Posts#index

	- Posts#show

	- Projects#index

	- Projects#show

	- Contact
