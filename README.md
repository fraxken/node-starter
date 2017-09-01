# node-starter
Node.JS - Interactive starter (ressources?) guide 

(Note: Sorry my english is not very good).

# The problem

On Node.JS there is a lot of ressources available everywhere (Articles, Documentations, Github pages with README.md, Talks on YouTube, etc..). But there is no "official" starter guide to tell you how to really start and find the right ressource.

And sometimes we made some efforts to bring a lot of ressources at a specific location (Just like : Hey! Here are a thousand resources, good luck). Finally the real problem is not fixed...

For example : if a System Administrator come (maybe he have to manage some Node.JS instances in production for his work) : Does he care about how the event loop work ? No.. He want to know more about our Docker support, about how work NPM (Give him tool like NVM etc..).

And there is a lot of sub cases : 

- Does it start development / programmation ?
- Does it written JavaScript before ?
- Does it come from PHP?
- Is it a team-manager ? (Talk to him about LTS cycle, NodeSource cases studies etc..) 
- etc... 

# (A possible) solution

Creating an interactive website that will ask you to make choice and answer questions (To define how you are and tell you what ressources are (probably) the best). Why not a another README ? (Because we need some back-end logic, and because a graphical website with some animations should be a much better experience for everyone). 

We cannot succeed to match 100% of what of the user really need (sure). But this would bring a much better experience for every new Node.JS community member (developer or not).

## Technical overview

The idea is to link the community work to some "tags". For example : 

- express.js tags should be : `http-framework`, `production`, `good-start`
- nvm should : `system`, `node-manager`

And we can also add a country tag. For example in French we have some very good talk of Christophe porteneuve (And some others talks from Devoxx about Electron, Express and many others...). 

On the website all ressources should be linked automatically depending of the profil choices. We can apply the same kind of process for our own Markdown files by writing a JSON files with all tags in (or something similar). 

## Questions structure 

Every questions have a priority and a tag property. That's not totaly clear how questions have to be chained between them right now (I continue to think about it to simplify the whole process and avoid unnecessary work). 

![img](http://i.imgur.com/QhohhOE.png)

I think priority and tags and not enougth properties (We need a third argument to maybe define the context).
