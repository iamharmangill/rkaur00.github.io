
# [ My Fourth Blog ]({% post_url 2019-01-28-fouthpost %})
This week I did the error validation in my code. Since in my billing system, I am getting the name and email of customer, and, to ensure that these fields are filled with proper data, I am using express validator.

To add validation module, open terminal and paste this command **npm install --save express-validator**
Code for error validation is:

const { check, validationResult } = require('express-validator/check');

check('name').isLength({ min: 3 }), // It will ensure customer name is not less than three characters.

check('email').isEmail() //It will check whether user has entered valid email address


References: [https://express-validator.github.io/docs/](https://express-validator.github.io/docs/)
