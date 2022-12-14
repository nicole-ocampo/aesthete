# aesthete
Aesthete is a web application catered towards artists. It is a new reimagined social media platform that houses incredible works from various people. Interactions can be made through liking and commenting on one's posts. A search feature may also be utilised in order to look for a specific user, or a specific tag.


# Main Features
1. Register an account
2. Access feed
3. Upload a post
4. Like/Unlike a post
5. Comment on a post
6. Edit a post/comment
7. Delete a post/comment
8. View profile
9. Search for a user/tag
10. Delete account

# Dependencies
- Nodejs
- MongoDB
- express
- multer
- bcrypt
- body parser
- hbs

# Demo
https://www.youtube.com/watch?v=sTXBBd_k31Q

# How to Run
This web application requires an internet connection in order to properly load google fonts.
This application is now accessible at: ~~https://aestheteforartists.herokuapp.com/~~

For local run:
1. Clone the repository to your local directory using the command prompt, or GitHub Desktop.
2. Navigate to the project folder using the command prompt and run `npm install` to install the dependencies.
3. Import the dummy database. Using MongoDB Compass, create a database named `aesthete`
4. Create the following colections: users, posts, likes, and comments. 
5. Import the files from the project folder > models > importdb, to each respective collection.
6. Once the database is setup, navigate to the project folder and run the `supervisor index.js` on the command prompt.
7. The server should now be up and running. On your browser, go to localhost:/3000.
8. The main index page should be displayed, and the application should be ready to use.


# How to Use
1. You may log-in to the application using the following credentials:
```
username: nini3
passsword: Ninisample1!
```

You may also log in using other users' credentials as listed below:
```
username: kageyamatobio
passsword: Volleyball1! 

username: shoyohinata
passsword: Ilovevb1! 

username: oikawa1
passsword: Iamthebest1! 

username: satorugojo
passsword: Gojosupremacy1! 

username: chernew
passsword: Cherpw1! 

username: tokkyu
passsword: Tokkyupw1!
```

Alternatively, you may also register an account. It is **important** not to leave any fields blank. In addition, password must be 8-15 characters long, containing one uppercase letter, one special character, and one number. When you are newly registered, you do not have a default profile photo, cover photo, bio, and website. Hence, you will be redirected to the edit profile page regardless whether you are a new user or not.

<br>

2. You may choose to navigate to the other pages, such as the feed and your own profile, using the menu bar.
3. Your feed consists of suggested tags from the authors, randomly suggested users, as well as posts from every user.
4. You may check the post itself by clicking the thumbnail, and you will be redirected to the post page. This page consists of the photo, the caption, the user who posted it, the number of likes, and the number of comments.
5. You can like the post if you wish to do so. However, you cannot do this twice.
6. You may also unlike a post, but only if you've liked it previously. 
7. You can post a comment, edit your own comment, or delete your own comment. You may also view the profiles of the user who posted it, as well as the profiles of the users who commented. 
8. You can edit your profile by clicking the edit profile button on your profile page.
9. To utilise the search feature, it is important to note the use of *#* and *@*
```
- To search for a hashtag, use # prior to your query. (i.e. #anime)
- To search for a user, use @ prior to your query (i.e. @chernew)
```

10. To upload a post, you may choose any photo of your liking, and post any caption. However, when enclosing tags, it is important to separate each tag by a comma *,* ONLY. `(i.e anime,manga,color)`
11. You may logout using the controls from the menubar. Alternatively, you may also delete your own account from the edit profile page.


# Authors
- Ocampo, Andrea Nicole
- Pioquinto, Cherrie Luz

# Disclaimer
This application is created for a school project under our web development class. This project is meant to teach us the basics of being a full-stack developer.
