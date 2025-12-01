Github Flow - The simplest guide in the galaxy ★

“The simplest guide in the galaxy”, it must be click-bait right ? No… or maybe. In the first part of this guide, I am actually going to present you with the absolutely simplest and most minimal approach presentation of the github-flow. I am also later, presenting a bit more for the curious developer or hobbyist coder. If you are “small team developing”, make it easier for you, not harder.

The flow in the three simple steps that will make you a star
Main branch - Think of it like your backbone, the stable branch ready to deploy
Feature branch - Experimental or development of features. Here lives all your ideas and implementations
Pull request + merge - Landing working features back into your backbone, the main branch


Of course we need a pictorial view to simplify this for all the visual learners out there. Imagine you start with the best idea of your life at the star. The line emerging from it, is the applications life line reaching into infinity and forever living as the application that set the ‘branch’ standard.
  Playful illustration of github flow.
Done! (if you just came here for the “simplest part in the galaxy” of course)



In orbit to be a github flow star ★

Lets play with the thought that we really can have this simplicity, and still remember a few extra small guidelines and tips without complicating our work flow. In this second part of the guide, I will share a few small tips and guidelines I learnt by diving into the nits and bits of a small team work flow thinking.

Never ever commit something directly to main
Even for a small team, a ‘commit’ to main, can have a big impact on everyone's code, think of your Main as the planet all the developers live on. We need it intact. Always follow the correct flow. BRANCH →  PULL REQUEST →  MERGE. Where the branch comes from main, and merges back to main, nothing more, nothing less.
Keep feature branches small and short lived 
A small and short lived branch will have a small code base. Less code that is more specialized to your assignment, will have less probability to cause severe merge-conflicts. Think of them like satellites with a single job. By keeping them short, we avoid collisions (conflicts in code).
Use consistent naming for your branches like:
Features:
feature / map-view
feature / dockerization
feature / authentication

Fixes:
bugfix / missing-recipes
hotfix / favorites-crashfix

Main:
‘Main’ of course - don't touch it manually. It's your backbone, and probably in a later stage of the project what you are demoing, or even running live with users.
Code Reviews keep our planet safe
It's code practice to let at least one teammate review your code in a pull request. It minimizes the probability to introduce bugs not observed and spreads knowledge between members whose code later will collaborate.

Clear commit messages
Keep it descriptive and short so everyone understands just what you did without even looking at the code. This simplifies reviews a lot.



It does not feel ★like with simplicity.
We are now at the last little part of this (partly)technical guide. Lets summarize with some other thoughts to give you the bigger picture of why I think this covers so many basics in such a small guide. 

Everytime we write code  as developers or hobby coders, we engage in this abstract world of creating our ‘dreams’ through a keybord. We utilize all the tools, libraries, frameworks, languages and techniques that we know. We think in a computational way, and sometimes complex patterns. The more complex code we write, the more complex work flows we have, the easier it is to make mistakes. It is also harder to introduce new team members when the complexity rises.

There are other ways to work with github like the git flow. You can have development branches, production branches and other strategies. But do you need them ? If you don't know, you probably don't. If you don't implement it, you can't make it wrong, and you don't have to put in all the work to just version handling your code.

What I am basically saying is that simple is good. Or should I say simple and safe. There have already been some really smart people developing github and its flows and functions for us. So for the ‘eager learner’, there is a full documentation to dive into at  docs.github.com/en.

For the ‘eager coder’, this is a safe way of working with github for your small team project. There are ways to get branches back and roll back versions and code if something happens. Focus your team's energy on creating fantastic code while keeping the github process simple.


Happy coding, and be a github ★ by dont complicating it.
