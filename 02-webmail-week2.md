# Assignment 1 

1. Each email is taken from a template literal.  The code for template literal is obviously looped to how many emails there are.

1. Each email is composed of a picture, full name, Subject line, body.  This data must be obtained from a json file downloaded from www.mockaroo.com. Steps to download it are below:

   1. goto www.mockaroo.com

   1.  Based on the email template, delete unused fields: id, gender, ip_address, 
   1. Click "Add another field", rename field to 'avatar' then click folder to select type -- choose avatar
   1. Add another field, rename field to 'subject' -- choose Catchphrase
   1. Add field, rename field to 'body' -- choose paragraph
   1. Add field, select date
   1. Add field , select time
   1. Below button, select only 10 rows; change format to JSON; download data.

1. Include your script 
```<script src="scripts/myapp.js"></script>```

1. Delete all the emails except for one-- we'll need that to include in our template.


1. Replace html code from email with our template literal
   1. Identify which block of html code we can use as our template and cut it out and put it in our myapp.js file.  Remember we need a some parent html tag to innerhtml into eventually so cut wisely.  Store this block into a variable.
   1. get the parent node via queryselector that we'll innerHTML into
   1. innerHTML into it our template literal -- the result should still look the same

1. replace default data from email with ours.  As a test just use first record from objects.

1. You may have noticed some of your emails look a little long.  Make it so that it displays a a max of 100 characters followed by '...'

1. Make the first email (if one exists) active by adding the class 'email-item-selected' to it

1. Make the body show the actual body of the selected email object.

1. If you select an email, make it look selected

1. Make it so that if you click Compose button, form shows where one can enter input, upon submit, it will display