Faceless

https://face-less.herokuapp.com/

This is a social media where a user can remain anonymous and post to a message board. Our inspiration for this project was drawn from Unit 2 Projects where majority of the websites required users to login/sign up and we felt it was restrictive to the user experience so the alternative was to:
A) prevent lurking (people who only access the site and don't contribute)
B) Make users contribute to gain access to the message board and thus creating a community with lots of contents
C) Users are given a randomly generated username in order to stay anonymous and still be able spill their deepest darkest SECRETS.
D) This app was built using a MERN stack (Mongo, Express, React, Node.js)


Key Features:
Randomly Generated Usernames
Users can only vote once on each post (until refresh)
Users can only access the message board after a post

FUTURE:

There's plenty of room for development, 

Use different components for each of the functions within the app

We can most definitely improve on its aesthetics and sorting functions to sort the posts

In the future, we'd like to also implement some type of community/location based post visability as well as dates/times for comments and randomly generated usernames for comments

When we get 100,000 posts per DAY, we will implement a feature that will render x more posts upon clicking see more

Be able to link pictures online(easy work we'll do this quickly)

Users cannot vote on a post that is just uploaded... we need to implement a live refresh

Format the comment section so it is easier on the eyes

change position of vote buttons

button for dark mode

click on the face in order to get new posts that allows you to see new posts/vote

currently, users can just go to the site and do fake requests and input whatever votes/username they want by submitting requests to the server side... so they can essentially bypass the client side code.. we'll find a way to fix that!
a friend posted this: 

formData = new FormData();
formData.append('username', 'ez');
formData.append('body', 'like this');
axios.post('/posts', formData, {headers: {'Content-Type': 'form-data'}}); will need to fix!

-Cavell W and Ryan F

