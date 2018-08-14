# SPO recruitment task for frontend developers

Hello! If you are here then you reached the coding challenge for frontend developers at SPO! 
Bellow you will find some description, which is very close to the stuff, that we are actualy working on at SPO.

The souce code of the solution should be provided as a bunch of files. It is highly recommended to use some build tools (preferably gulp or webpack) and push all the sources to a git repository so you will be able to demonstrate also your ability of working with build tools and git itself. Please note that **code quality** is also important for us.

Good luck to you and hope you will enjoy the process while solving this task!


## Make a registration form

Please show your knowledge and experience of creating a form. Please choose ReactJS (or if you like, React Native) as a library/framework which will help you to get the work done.
Please demonstrate your ability to work with React and use the best practices of developing applications using React.


### Technical requirements

1. When the application is started the user sees the following page: ![alt text](https://github.com/servicepartnerone/spo-coding-challenge/blob/master/form.png)

2. Input data validation should be done for each field once the user finishes his/her input (on blur event) and once again for all data just when the submit button will be clicked by the user. In case of validation errors the messages should be displayed below the invalid field:

![alt text](https://github.com/servicepartnerone/spo-coding-challenge/blob/master/form_with_errors.png)

3. After the user fills only **valid data** and clicks on submit button the alert box will pop up with the input data.

4. If you want to make it even fancier, you create a multi step form. On the first page, ask the user for first name and last name and have a next button.
On the second page, ask the user for username, password and email. On submit, the alert box will pop up with all the input data.

5. Why not suggesting the user a username ? It could be based on his first and last name and would be filled directly into the username input field.

### Validation rules

* All fields are mandatory

1. **First Name** - should contain only small and capital letters, no numbers, special characters, etc.
1. **Last Name** - same as the **First Name**
1. **Username** - should contain only small letters. May contain also numbers, the "." and "\_" characters
1. **Password** - should contain anything and should be more than 8 characters in length
1. **Email** - must be a valid email address
