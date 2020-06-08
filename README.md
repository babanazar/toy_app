# Exercises

## 2.2.1

### 1. 
id of "User was successfully created." is 'notice'.
### 2. 
A user with no email is created successfully.
### 3.
A user with invalid email address '@example.com' is created successfully.
### 4.
Yes: "User was successfully destroyed."

## 2.2.2
### 1. 
1. The browser issues a request for the /users/1/edit
2. Rails routes /users/1/edit to the `update` action in the Users controller.
3. The `update` action asks for the User model to retrieve the user with id of 1.
4. The User model pulls the user of id 1 from the database.
5. The User model returns the user of id 1 to the controller.
6. The controller capture the user of id 1 in the `@user` variable, which is passed to the `edit` view.
### 2.
    @user = User.find(params[:id])
### 3.
    edit.html.erb

## 2.2.3
### 1.
id stays there but the message disappears.
### 2.
I was able to successfully create a micropost with no content and no user.
### 3.
I successfully created an article with more than 140 characters.
### 4.
Successfully destroyed.