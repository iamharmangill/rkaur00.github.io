
# [ My First Blog ]({% post_url 2019-01-28-fouthpost %})
This week I did the error validation in my code. Since in my billing system, I am getting the name and email of customer, and, to ensure that these fields are filled with proper data, I am using express validator.

To add validation module, open terminal and paste this command **npm install --save express-validator**
Code for error validation is:

const { check, validationResult } = require('express-validator/check');

References: [https://express-validator.github.io/docs/](https://express-validator.github.io/docs/)
