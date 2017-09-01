# node-starter
Node.JS - Starter guide (a new idea)

# The problem

On Node.JS there is a lot of ressources available everywhere (Articles, Documentations, Github pages with README.md, Talks on YouTube, etc..). But there is no "official" starter guide to tell you how to really start with all theses ressouces.

And sometimes we made some efforts to bring a lot of ressources at a specific location (Just like : Hey! Here are a thousand resources, good luck). Finally the real problem is to understood what every people need !

For example if a System Administrator come : Does he care about how the event loop work ? No.. He want to know more about our Docker support, about how work NPM (Give him tool like NVM etc..).

And there is a lot of sub cases : 

- Does it start development / programmation ?
- Does it written JavaScript before ?
- Does it come from PHP?
- Is it a team-manager ?
- etc... 

# The solution

The solution is to create an interactive website that will ask you to make choice and answer questions (To define how you are and tell you what ressources are the best). Why not a another README ? (Because we need some back-end logic, and because a graphical website with some animations should be a much better experience for beginners etc). 

We cannot succeed to match 100% of what of the user really need (sure). But this would bring a much better experience for every new Node.JS developer.

# Technical overview

The idea is to link the community links/works to some "tags". For example : 

- express.js tags should be : `http-framework`, `production`, `good-start`
- nvm : `system`, `package-manager`

So on the website all ressources are linked automatically. We can apply the same kind of process for our own Markdown files by writing a JSON files with all tags in (or something similar). 
