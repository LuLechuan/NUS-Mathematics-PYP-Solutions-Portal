# NUS-Mathematics-PYP-Solutions-Portal
_For easy addition of Past Year Paper Solutions of NUS Mathematics Modules (MA)_

## Meta Details
_A Summer Project for CP2106: Independent Software Development Project (Orbital)_
* __Project Title__: NUS Maths PYP Solutions
* __Project Team Members:__ __Lu Lechuan__ (NUS Comp Sci), __Xu Weichen__ (NUS Applied Maths)
* __Member Contribution__
  * __Lu Lechuan__ (Front-End Development with JQuery, Mathjax, Bootstrap, Vue.js)
  * __Xu Weichen__ (Back-End Development with Express, MongoDB, Mongoose, Passportjs)
* __Project Duration & Breakdown:__
  * __May 2017__: Learning HTML5, CSS, Javascript, Introduction to Expressjs, MongoDB, JQuery, Ajax
  * __June 2017__: Learning Expressjs, MongoDB with Mongoose driver, Learning Bootstrap
  * __July 2017__: Obtain and Customize the Drywall Framework, implementation of Maths PYP related features
  
## Project Details
__ A Node.js based Web Application using Expressjs and Remote MongoDB__

_Based on [Drywall: A Website and user system starter](https://github.com/jedireza/drywall/)_

__The Major Dependencies are:__

| On The Server | On The Client  | Development |
| ------------- | -------------- | ----------- |
| Express       | Bootstrap      | Grunt       |
| Jade          | Backbone.js    |             |
| Mongoose      | jQuery         |             |
| Passport      | Underscore.js  |             |
| Async         | Font-Awesome   |             |
| EmailJS       | Moment.js      |             |

__Website Features:__
 * Contact page has form to email.
 * Login system with forgot password and reset password.
 * Email notification during signup flow.
 * User system with separate account and admin roles.
 * Admin groups with shared permission settings.
 * Administrator level permissions that override group permissions.
 * Global admin quick search component.

__Maths PYP Solutions Related Features:__
 * CRUD Functionality for Maths Modules
 * Online/Offline Functionality for Maths Modules
 * CRUD Functionality for Answers
 * Admin permission to access all answers, all module details, own answers; ability to write answers
 * User permission to access own answers and ability to write answers
 * Organization of modules into tree like structure
 * Dynamically generate webpages for easy addition of future answers
 * Allows Display of LaTex on Webpages
 * Limits access of non-users, and users (non-admins) to certain webpages
 * Added ReCaptcha to deter spam
 * Integrated with Bootstrap for mobile friendly development
 
 _......and a lot of other small features to optimize the UX_
 
