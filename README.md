# Business website // 2 weeks
The repository includes a website to sell ambiguous things
Project realised in collaboration, during the 12 weeks web development bootcamp with the NYCDA.


Task:
Work in groups of two or three. Choose a business, then build a website for that business. The business can be real or imagined.

___PART 1___

Site requirements:
- A minimum of four separate pages
- Use photographs
- Using JavaScript and jQuery, add at least two interactive elements to the site. Options include, but are not limited to:
   - animated drop down navigation bars
   - a photo gallery that, on click, displays large versions of the photos

Git requirements:
- When creating each page, create a separate branch on git. Add your commits to that branch. Then, when the page is complete, issue a pull request. Your other team member(s) must review and then merge that branch into master. Branch names should be named after features. Do not push directly to master, aside from your initial commit.

___PART 2___

Static Website on Node.js

Important Notes
- Remember to add "node_modules" to your .gitignore file. Otherwise, a lot of other people's code is going to end up in your repository.
- If you did not originally create the repo, you must "fork" it on github, which will make a copy and put it on your github.
- express.static() looks for 'index.html' by default, so rename your home page to that. Alternatively, serve a different default file using the following syntax:

app.use(express.static('myStaticPath', {
    index: 'myNonDefaultHomepage.html'
}));


Instructions
- Take the website that you built previously, and create a new branch on git so the old version is still available for grading / reviewing.
- Put your website on a Node.js server, so that it can be reached at http://localhost:3000.
- Your Node.js server does not need any routes, since the entire website is static content.
- Check each of your links and images to ensure that they still work.
- Express by default looks for `index.html` for the first page.
