# Hamba Uhambe Travel Blog
![Website]()

Hamba Uhambe is a travel blog where I post stories of various travels and trips I have taken in my life as a form of a journal to share with my family. Hamba Uhambe is Zulu for Go for a walk.

# Table of Contents

- [UX](#ux)
- [Features](#features)
    * [Existing Features](#existing-features)
        - [Home Page Features](#home-page-features)
        - [Category Page Features](#category-features)
        - [Sign Up Form Features](#signup-form-features)
- [Testing](#testing)
    * [Home Page](#home-page)
    * [Responsiveness Testing](#responsiveness-testing)
    * [Validation Testing](#validation-testing)
    * [Bugs](#bugs)
- [Developement Cycle](#developement-cycle)
    * [Commit Diary](#commit-diary)
- [Technology Used](#technology-used)
- [Deployment](#deployment)
- [Credits](#credits)
    * [Content](#content)
    * [Media](#media)

## UX
The design of this site has been focused around simplicity and convinience. The home page is paginated to make exploring the posts easy and interesting. The posts are categorized to easliy choose stories that are more in line with the readers interest.

The goals for the first time user are to experience an easy to use and interesting story making the user want to come back and read more.

[Back to Table of Contents](#table-of-contents)

## Features

## Existing Features

### Landing Page Features
* Homepage - Navbar with title, and links to category page and login, logout or sign up pages. Shows 6 posts before the rest are shifted to the next page.
![Home Page](https://github.com/deanwraith/travelblog/blob/main/static/images/homepage.png)
* Category Page - The dropdown bar automatically populates with categories added to the admin panel. each specific category page includes all the posts under that category.
![Category Page](https://github.com/deanwraith/travelblog/blob/main/static/images/categorypage.png)
* Login Form - Allows the user to log in so that they can like or comment on the various posts.
![Login Form](https://github.com/deanwraith/travelblog/blob/main/static/images/login.png)
* Sign Up Form - Allows new users to sign up with an email and password to like and comment on posts.
![Sign Up Form](https://github.com/deanwraith/travelblog/blob/main/static/images/signup.png)

[Back to Table of Contents](#table-of-contents)

## Testing

### Home Page
| Function | Description | Result:Mobile | Result:Desktop |
| --- | --- | --- | --- |
| Header link | Links back to landing page when clicked, on all pages | Passed | Passed |
| Category Dropdown | Dropdown displays categories added and names link to categories page | Passed | Passed |
| Category Page | Posts with selected category show on specific page | Passed | Passed |
| Post display | Post display on homepage shows details and title links to post | Passed | Passed |
| Post Page | Posts displayed with content. User can like and comment on post | Passed | Passed |
| Login Page | User can log in if they have an account. Are redirected to Sign up page if not. | Passed | Passed |
| Sign Up | Allows user ability to register an account to be able to like and comment | Passed | Passed |
| Facebook Icon | Redirects to Facebook in a new window when clicked, on all pages | Passed | Passed |
| Twitter Icon | Redirects to Twitter in a new window when clicked, on all pages | Passed | Passed |
| Instagram Icon | Redirects to Instagram in a new window when clicked, on all pages | Passed | Passed |

[Back to Table of Contents](#table-of-contents)

### Responsiveness Testing
Responsiveness testing was done using several mobile devices of different size to see the site effectiveness at different resolutions. 
The devices used were:
* Iphone SE
* IPad
* HP Elite Book Laptop as well as the Inspect function on Google Chrome Browser to test most resolutions and devices.

### Validation Testing
* HTML
    * [W3C Validator](https://validator.w3.org/)
    All HTML code was checked using this validator and was returned without any issues.
* CSS
    * [Jigsaw Validator](https://jigsaw.w3.org/css-validator/)
    All CSS code was tested using this validator and was returned with no issues.

### Bugs
* Any bugs

[Back to Table of Contents](#table-of-contents)

## Developement Cycle
### Commit Diary
    * 17:07 30/07/2021 - Initial Commit
    Added boiler plate HTML and assets folder which includes the style.css file and a folder for media resources to be added at a later stage.
    
[Back to Table of Contents](#table-of-contents)

## Technology Used

* HTML5
* CSS3
* Javascript
* Bootstrap
* Django
* Heroku
* Cloudinary
* Github
* Gitpod

## Deployment

The site has been deployed using Heroku.

* In the Github repository page for deanwraith/rock_paper_scissors_game the settings tab was selected.

[Back to Table of Contents](#table-of-contents)

## Credits

### Content
    * Google fonts - The special fonts used for the project were sourced from Google fonts.
    * Font Awesome - The icons used in the project were sourced from Font Awesome
    * W3Schools - Used the resources as a guideline for various functionality and styling.
    * Code Institute - Used the I Think Therefore I Blog walkthrough as a guideline.
    
### Media
    * Images are my personal images taken on my various outings.

[Back to Table of Contents](#table-of-contents)