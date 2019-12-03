# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.


## Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 



COMPLETED CODEPEN LINK!!!
https://codepen.io/Khowe701/pen/Exaagod?editors=1100

    1. What is Semantic HTML? 
    Semantic HTML gives the HTML meaning rather than just presentation.
    2. What is HTML used for? 
    HTML is used for creating the building blocks of webpages.
    3. What is an attribute and where do we put it? 
    an attribute gives specificity to an element and is put after the beginning tag.(<p id="kj">)
    4. What is the h1 tag used for? How many times should I use it on a page?
    The h1 tag is a headline tag that is used for showing importance on a page. Generally used for the title, so often only once.
    5. Name two tags that have required attributes
    IMG    Input
    6. What do we put in the head of our HTML document? 
    it can be quite a few things, generally the title of the document.
    7. What is an id? 
    it gives an element a unique identity to call from when styling the page.
    8. What elements can I add an id to? 
    Any
    9. How many times can I use the same id on a page?
    as many as needed but everything with that id will be styled the same due to specificity in CSS
    10. What is a class? 
    specifies a class name for one or more elements.
    11. What elements can I add a class to? 
    any
    12. How many times can I use the same class on a page? 
    as many as needed, and can often times be used to group similar types of data.
    13. How do I get my link to open in a new tab?
    arget="_blank" attribute to a link
    14. What is the alt attribute used for? 
    gives alternative text to an attribute.
    15. How do I reference an id?
    #idName
    16. What is the difference between a section and a div
    a section means the content inside is grouped where a div is simply a tool used to style content differently.
    17. What is CSS used for? 
    CSS is used to style a webpage and give it life.
    18. How to we select an element? Example - every h2 on the page
    h2{

    }
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
    an id you would generally want to give to one item as it is the most specific you can get in HTML whereas a class could be given to any content that relates to one another.
    For example, if i were talking about countries i could give each country a specific id but they would all be in the class="country"
    20. How do we select classes in CSS?
    .className
    21. How do we select a p element with a single class of “human””?
    22. What is a parent child selector? When would this be useful?
    the parent element is the head element with the child being an element that falls underneath of that one. You could select all classes in a section with parent > child selector. 
    23. How do you select all links within a div with the class of sidebar?
    .sidebar  or  div, .sidebar
    24. What is a pseudo selector?
    it allows a different style to be used when a condition is met. For example :hover
    25. What do we use the change the spacing between lines?
    line-height property
    26. What do we use to change the spacing between letters?
    letter-spacing property
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
    :capitalize, :lowercase, :uppercase
    28. How do I add a 1px border around my div that is dotted and black?
    div{
        border:1px dotted black
    }
    29. How do I select everything on the page? 
    *{

    }
    30. How do I write a comment in CSS?
    /*comment here*/
    31. How do I find out what file I am in, when I am using the command line? 
    pwd
    32. Using the command line - how do I see a list of files/folders in my current folder?
    li
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
    type rm. you have to be careful because there is no failsafe, if you do this its gone.
    34. Why should I use version control? 
    to manage changes to your code so you can change it back if a mistake is made.
    35. How often should I commit to github?
    whenever you get a piece of working code so you can reopen if you break it somehow.
    36. What is the command we would use to push our repo up to github? 
    git push
    37. Walk me through Lambda's git flow.
    1.Find the repository 2.Fork 3.Clone into your own directory 4.Branch using git checkout -b "first-last" 5.once changes are made- git add , git commit , git push -u origin branch name 6. submit pull request.