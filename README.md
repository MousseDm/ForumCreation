# ForumCreation
Excecution plan for the Web Forum Application
1.	Overview
The web forum application would include several functionalities: 
	Register and Log in: every user can sign up for an account with an email address, with unique id number. Fulfilling their profile can make others know them easier and better.
	Posting on forum and replying: In the home page, people can post about their lives, showing their works and others. The posts can be labeled with tags to let others search about them. They can also comment on others’ posts and reply to them.
	Create groups: If people meet anyone they want to make friend with or decide to do some work together, they can create a group and invite others to join after they agreed. They can upload files, photos.etc to the group which help them cooperate and communicate.
	Edit/delete posts: Users can edit or delete their own posts
	Search for tags or posts: Users search tags or posts

2.	User and Admin
	User would be able to access all the functionalities listed above. They can also report others’ posts to the admin if they think those obey the rules.
	Admin would remove inappropriate content or ban users if necessary

3.	Backend chosen: Rails
Rails provides a structured and intuitive frame work, which is good for prototyping. Rails’ ecosystem supports a wide range of plugins and tools, which can simplify implementation

4.	Additional functions
	Wired job pickup module - Mainly for individual professionals such as painters/animators/music creators or individual production teams. The creators can show their previous work in their posts, and if other people like their work, they can create a plan and pitch it to invite the creators with explanations and remuneration about their plan. The forum can keep the remuneration during the process and pay to the creator after planners’ approval of the mission. 
	Making life easier module – People can post a call ahead of time to find someone to carpool with them to the airport, famous attractions, school .etc and save money(or meet new people). They can also try to get someone to collect their deliveries or pick up their takeaways if there is accidentally someone in the same area and willing to help them to get little extra money.
	Voice function for group chats – people can start a voice call in a group and allow group members to join, which would make their communication easier and faster

5.	Technology Stack
	Backend: Rails and PostgreSQL
	Frontend: CSS framework and js
	Development tools: Git

6.	Backend Structure
	Models: User,Post, Comment
	Controllers: UserController, PostController, CommentController, (GroupController, ProjectController)

7.	Frontend Structure
	Header: navigation
	PostList: shows all the posts
	PostDetail: display a single post with its comments
	CommentForm: allow users to post comments
	(GroupChat: allow group members to chat and share files)
	(ProjectCreation: allow people to start a project and invite creators; allow creators to receive invitation and join the project. Allows users to pay through the forum)
