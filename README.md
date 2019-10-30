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

** Link to Codepen assignment:  https://codepen.io/ScottAhlstrom/pen/WNNZrJz?editors=1100



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

1. What is Semantic HTML? 
        Gives your markup and tags meaning.
    2. What is HTML used for? 
        To create pages for the web - a Hypertext Markup Language
    3. What is an attribute and where do we put it? 
        Attributes give additional information about an element. They are placed in the opening tag. 
    4. What is the h1 tag used for? How many times should I use it on a page?
        Usually used for a title or header of a page, and should only be used once.
    5. Name two tags that have required attributes
        input & select
    6. What do we put in the head of our HTML document? 
        you can have <title><style><link><script> among others
    7. What is an id? 
        The id attribute specifies a unique id for an HTML element. It is defined with a # mark
    8. What elements can I add an id to? 
        The id can be added to any HTML element, but can only be used once
    9. How many times can I use the same id on a page? 
        only once
    10. What is a class? 
        An attribute that specifies one or more class names for an HTML element, used to point to a class in a style sheet.
    11. What elements can I add a class to? 
            can be used on any element
    12. How many times can I use the same class on a page? 
            as many as wanted
    13. How do I get my link to open in a new tab?
            by adding a target="_blank" attribute to your link (anchor tags)
    14. What is the alt attribute used for? 
            It provides an alternate text or description for an image
    15. How do I reference an id?
            by a # sign
    16. What is the difference between a section and a div
            a <section> tag has semantic meaning, describing more meaning or defining sections in a document. <div> tags have no meaning and typially are used for grouping elements for styling in css.
    17. What is CSS used for? 
            It describes the presentation of web pages, like colors, fonts, layouts, etc.
    18. How to we select an element? Example - every h2 on the page
            in CSS, you would enter h2 {}
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
        A class can be used multiple times, and you can even have multiple classes on a single element, however, you can only have a single id tagged to an element (can only be used once) for styling in CSS. A class could be used with a <section> tag or <div> and an id could be more specific with that class, on a <p> tag for example
    20. How do we select classes in CSS?
            by using the dot key '.'
    21. How do we select a p element with a single class of “human””?
            .human p {}
    22. What is a parent child selector? When would this be useful? 
            it selects all elements that a direct child of the specified element
    23. How do you select all links within a div with the class of sidebar?
            .sidebar div a {}
    24. What is a pseudo selector?
            it is a keyword added that specifies a special state of a selected element, for example, :hover.
    25. What do we use the change the spacing between lines?
            by using the line-height property in CSS
    26. What do we use to change the spacing between letters?
            by using the letter-spacing property in CSS
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
            by using the text-transfrom property in CSS
    28. How do I add a 1px border around my div that is dotted and black?
            you would enter the div{add border-style: dotted; border-width: 1px; border-color: black;}
    29. How do I select everything on the page? 
            the * selector
    30. How do I write a comment in CSS?
            by starting with /* 'comment' and ending with */
    31. How do I find out what file I am in, when I am using the command line? 
            pwd
    32. Using the command line - how do I see a list of files/folders in my current folder?
            ls
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
            rm <file> You need to be careful, becuase once removed/deleted, it is completely gone. It is not even your trash, and there is no question or confirmation of the file being removed. 
    34. Why should I use version control? 
            Version control allows for collaboration of a project with multiple users and allows changes to be saved and verified with other areas of the project
    35. How often should I commit to github?
            roughly every 20 minutes...frequently!
    36. What is the command we would use to push our repo up to github? 
            git push
    37. Walk me through Lambda's git flow. 
            First fork the repo
            Then clone the repo - git clone URL
            Then make some changes and run a git status
            Then stage the changes using git add .
            Then committ the changes using  git commit -m “our message”
            Then use git push to publish your local commits
            Now we should be able to see these changes
            You can check the status in between by using git status

Stretch Questions

    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 


** Link to codepen assignment:  https://codepen.io/ScottAhlstrom/pen/WNNZrJz?editors=1100

