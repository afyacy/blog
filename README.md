Application plan

1. Answer Questions
	- What am I building?
	- Who am I building it for?
	- What features do I need to have?

2. User Stories

3. Model the Data

4. Thinking through the pages I need in the application

## Questions

1. What am I building? I am building a personal site. A place where I can blog, share examples of my work and have people contact me.

2. Who am I building it for? I am building it for myself but also the community. Sharing what I am doing by blogging but also teaching others in the process. Show potential employers that I know what am doing.

3. What features do I want to have?
	- Posts
		. Create/ Edit / Destroy
		. Markdown
		. Syntax highlighting
		.  Comments

	- Projects
		. Create/ Edit / Destroy

	- Contact
		. Contact form
		. Sendgrid

	- User (Devise)

## Use Stories

As a blank, I want to be able to blank, so that blank.

	- As a user, I want to be able to create posts so that I can share what I am doing on my blog.
	- As a user, I want to be able to edit & destroy posts, so that I can manage my blog.
	- As a user, I want to be able to write posts in markdown format so that it's easy for me to write 		  posts.
	- As a user, I want to be able to highlight the various syntax of code blocks that I share on my 	  	  blog.
	- As a user, I want to show the visitors and potential employers examples of my work.
	- As a user, I want to be able to have visitors contact me through a form on my site.
	- As a user, I want visitors to be able to leave comments on my posts.


## Modeling the Data 

*Posts
	title:string
	content:string
*Projects
	title:sting
	description:text
	link:string
*Users


##Thinking through the pages I need

- Home
-  Posts#index
- Posts#show
-  Projects#index
- Projects#show
- Contact