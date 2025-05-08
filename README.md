Project: MERN Stack Blog App Deployment on AWS

Project Overview:
This project involves deploying a MERN (MongoDB, Express, React, Node.js) stack blog application on AWS. The objective is to ensure the app runs smoothly in a cloud environment, with a focus on scalability and security. The app consists of both the frontend and backend, with the frontend hosted on Amazon S3 and the backend deployed using EC2 instances.

Steps Taken:
	1.	Cloning the Repository:
	•	First, I cloned the repository from GitHub to my local machine.
	•	The project repository was cloned into a directory named assignment-10.

git clone https://github.com/YHKH/assignment-10.git


	2.	Setting Up the Frontend:
	•	I created a React application for the frontend.
	•	This frontend was responsible for rendering the blog’s interface and interacting with the backend through API calls.
	3.	Uploading the Frontend to Amazon S3:
	•	Once the React app was developed, I created an S3 bucket in AWS to host the frontend.
	•	I uploaded the static files of the React app (e.g., index.html, JavaScript, CSS files) into the S3 bucket.
	4.	Setting Up EC2 for the Backend:
	•	I launched an EC2 instance to serve as the backend for the blog application.
	•	I installed Node.js and other necessary dependencies on the EC2 instance.
	•	The backend was then connected to MongoDB Atlas for database management.
	5.	Configuring Security and Load Balancing:
	•	I set up Application Load Balancer (ALB) for distributing traffic to the EC2 instances, ensuring that the app is scalable and can handle more requests in case of traffic spikes.
	•	Additionally, I configured Auto Scaling Groups to dynamically adjust the number of EC2 instances based on demand.
	6.	Uploading Screenshots for Validation:
	•	I captured a screenshot showing the pm2 process manager, indicating the backend application is running smoothly.
	•	This screenshot was uploaded to Amazon S3, and the link to the image was generated.
S3 Link: pm2-list.png
	7.	Pushing Updates to GitHub:
	•	After completing the necessary configurations, I updated the GitHub repository with the latest changes, including the new README.md file that describes the project setup and details.
	•	The README file provides a step-by-step guide on how the project was developed, including links to key resources and the S3 bucket hosting the frontend.

git add README.md
git commit -m "Update README with project details"
git push origin main


	8.	Final Validation:
	•	Finally, I tested the project by accessing the frontend via the S3 URL and ensuring that the backend API was properly communicating with the database.

⸻

Summary of What Was Done:
	•	Cloned the project repository from GitHub.
	•	Developed the React frontend for the blog application.
	•	Set up Amazon S3 for hosting the static files of the frontend.
	•	Deployed the Node.js backend on an EC2 instance.
	•	Configured Application Load Balancer (ALB) and Auto Scaling Groups for scalability and security.
	•	Uploaded screenshots for validation purposes to Amazon S3.
	•	Updated the project repository on GitHub with all changes and added a detailed README.md file.

This project involved a combination of React, Node.js, AWS services (S3, EC2, ALB, Auto Scaling), and MongoDB Atlas to deliver a scalable and secure blog application.



S3 Link: http://yahya-blogapp-frontend2.s3-website.eu-north-1.amazonaws.com/


