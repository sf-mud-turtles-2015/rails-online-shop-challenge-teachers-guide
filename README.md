# Teachers Guide to the Rails Online Shop challenge (Phase 3)

### Goals and Process

The goals of this challenge are to:
- Practice agile, iterative development 
- Experience a 'real world', professional development project
- Build a readable, extensible, and maintable code base 'The Rails Way'
- Build a 100% test covered app
- Build a usable and beautiful responsive layout
- Practice onboarding/being onboarded onto a new code base

App requirements are provided by the 'client' and code review and technical consultion is provided by the 'senior engineer'.  The 'client' and 'senior engineer' roles are played phase 3 teachers.

The senior engineer signs off on the code base for an iteration before a pair can have their next meeting with the client and find out what feature they are building next.

This structure serves to hold students accountable for code and app quality, test coverage, writing code 'The Rails Way', agile and incremental development processess, and implementing high quality UX and visual design.  Conversely, the structure holds teachers accountable for providing frequent feedback on the students' code base and frequent 2-student-to-1-teacher ratio interactions. 

This challenge is based on Agile Web Development with Rails 4 (by Sam Ruby, Dave Thomas, and DHH).  There are 18 copies of the book available to support student learning and to support the teachers running the challenge.  All the info a teacher needs to teach this challenge is in the book.

Here is an [example](https://docs.google.com/spreadsheets/d/14r-3aPGNZcPXPXZegyDX259XGLzgOLpKd58XnafFVrw/edit#gid=0) of a tracking spreadsheet where the teacher playing the senior engineer tracks which pair has sign-off for an iteration.  The client uses the spreadsheet to know when they should drop in on their dev team.

### Iterations

#### Iteration 1: User Stories, wireframes, and data requirements

##### Requirements for senior engineer sign off
- User stories 
- Wireframes
- Data model

Tips: Watch out for feature and scope creep, look for reasonable UX in the wireframes, and look out for unwarranted implementation details and assumptions.  Encourage the students to move through this step as quickly as possible and not be too attached, 'cause it will probably change a lot!

#### Iteration 2: Products CRUD for the merchant


##### Requirements for senior engineer sign off

- Functional app deployed to heroku
- 100% test coverage
- Unit tests on the model
- Controller tests
- Validations
- Coding 'The Rails Way'
- Proper git workflow and commit messages

##### Client meeting script:

#### Iteration 3: Responsive layout with an inventory view for the merchant and a shop view for the shoppers

##### Requirements for senior engineer sign off

- Beautiful, usable, responsive layout
- UX for inventory view should be tabular, very functional, designed to help the merchant move through lots of data quickly
- UX for the shopper's view should be visual, maybe a grid of product images, should encourage spending time and slow browsing
- Use a CSS reset
- Use a CSS responsive grid
- Use some organizing CSS methodology, either some flavor of semantic CSS or the Atomic pattern
- Try using Sass (not required)

Tips: Hold the students to a high standard!  The UI should look like something you would not be embarassed to show an actual client.

##### Client meeting script:

#### Iteration 4: Shopping cart

##### Requirements for senior engineer sign off

- Each product should have an 'Add to cart' button
- Clicking the 'Add to cart' button should go to a page showing the current cart
- Functional app deployed to heroku
- 100% test coverage
- Unit tests on the new models
- Controller tests on the new controllers
- Validations on the new models
- Coding 'The Rails Way'
- Proper git workflow and commit messages
- At least one feature test on the shopping cart
- Optional: Feature tests on the CRUD

##### Client meeting script

#### Stretch Iterations

- Ajaxify the shopping cart
- Removal of products from the shopping cart
- Implement checkout functionality and integrate Stripe for payment processing
- Image upload for the admin with carrierwave gem
- Send a confirmation email for the order
- Authentication with devise gem or omniauth gem
- Authorization with pundit gem
