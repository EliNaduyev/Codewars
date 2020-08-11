<p align="center"><img src="screenshots/codewars_logo.png" heigth="350" width="350"/></p>

Codewars it is a learning environment that offers the user another way to learn and improve his programming skills. In this way, users face each other in real time code competitions. Those competitions not only improve his programming skills and logical thinking but also allows him to understand better what his programming level relative to other users in the world.

**Live Demo (not mobile friendly):** https://codewars-project.netlify.app/

<img src="screenshots/home_page .png"/>

After the registration users will required to pass the "Level Test" which will determine their programming level and immediately afterwards they can start competing with other users around the world whose programming level is the same.

<img src="screenshots/war_room.png"/>

At the war page each user can see random challenge and the online editor where they could write their code. In addition, there is a "run code" button to check the code before submitting, timer and "submit" button. After clicking on the "submit" button starts countdown of 15 seconds, It would be the maximum time for the opponent to finish his code, after a 15 seconds the answer will be submitted automatically to the assessment tool and each user will be transferred to a result page where he will get his score.

<img src="screenshots/profile.png"/>

Each user can navigate to his profile page and see his personal information, statistics, last wars and his friends list. Also, users can navigate to other users profile pages, send friend requests, see theirs personal information, statistics and etc.

### Technologies
* React at the client side
* NodeJS & Express at the server side
* MongoDB & Mongoose
* Asynchronous tasks, Axios
* Socket.io
* Joi
* Nodemailer & Google API's

### How to install
Clone the repository:
```
git clone https://github.com/EliNaduyev/Codewars.git
```
Enter the clonned folder:
```
cd Codewars
```
Enter the client folder:
```
cd client
```
Install the dependencies:
```
npm install
```
Run the application:
```
npm start
```
Local app should open automatically, if it is not, open the browser at http://localhost:3000/

