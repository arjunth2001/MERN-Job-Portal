# MERN Job Portal

## Job Portal made with MERN Stack for Assignment 1 of DASS Course

### Submitted by T.H.Arjun, 2019111012

To run:

- Set `mongoURI` in `./backend/config.js` to the mongo uri of DB. It is currently set to `mongodb://127.0.0.1:27017/job_portal`. Set the secret for authentication middleware also in the same file.

- Run mongo if doing locally or give the atlas URI in config.
-

- Open one shell/ terminal window in the folder
  - `cd backend`
  - `npm install`
  - `npm run start`
- Open another shell/ terminal window in the folder
  - `cd frontend`
  - `npm install`
  - Either do `npm run start` to run using node or `npm run server` to run using nodemon

> Navigate to localhost:3000/ in your browser.

### Bonus!!

#### The following bonuses have been implemented

- Profile Picture Upload for Applicant and Recruiter
- Resume upload / download on the Profile page of Applicant
- Resume download in Applications list for a particular Job on the Recruiter Account
- Emailing on the acceptance of an Application
- Fuzzy Search

The backend folder contains the backend code and frontend folder contains the frontend code.
