This project is a web-based voting application that allows users to register, log in, and cast votes for candidates in an election.
The application is built using Node.js with Express for the server, MongoDB with Mongoose for the database, and JWT for authentication.
It includes features for user registration, login, vote casting, and vote counting, with role-based access control to ensure only authorized actions are performed.

# Features
# User Registration:

Users can sign up with their personal details, including name, age, email, mobile, address, Aadhar card number, and password.
Each user can be assigned a role of either 'voter' or 'admin'.

# User Login:

Users can log in using their Aadhar card number and password.
JWT tokens are generated upon successful login to secure subsequent requests.

#Role-Based Access Control:

Admins have additional privileges, such as adding, updating, and deleting candidates.
Only voters can cast votes, and they can vote only once.

# Candidate Management:

Admins can add, update, and delete candidates for the election.
Each candidate has details such as name, party, age, and a vote count.

# Voting:

Voters can cast their votes for a candidate.
The application ensures that each voter can vote only once.

# Vote Counting:

The application provides endpoints to fetch the total vote counts for each candidate.
Admins can access the vote counts to see the election results.
