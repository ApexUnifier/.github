# Development Guidelines
## Branch Structure
So we would be following Three branch structure `main` , `develop` and `release`

### main
This branch is meant for backup so never push here
- `note` this branch will have code one version lower
### develop
We would working on this branch !
- Fork the branch then fork your forked branch to your `local system`
- make local branches at your system for the issues your working on once the issue is solved merge it with develop branch at your local
- push it to your forked repo at github and then send `pull request`
- `note` never push the local made branches for issue at your `local system`
- `note` uncheck fork main only box to fork all the branches while forking in your github from main organisation repo
  `for example` if i am asked to add forget password feature i will make seperate branch for feature at my local once the work is done i will merge it with develop in my local then push it to forked repo at github and will send `Pull Request` to develop branch in main project
### release 
This branch will have production code
### merge conflicts
- all the issue related to merge conflicts will be managed by me so focus on the issue assigned to the particular developer <br> `happy coding :)`
### Testing Guidelines
- Use `Red Green Refactor` method To write test
- write test for module you are going to develop make seperate folders for tests
- make seperate folder for module in the test folder
- `for example`  if you are writing test for module name `document.js` then make folder of name `document` and write tests there.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
