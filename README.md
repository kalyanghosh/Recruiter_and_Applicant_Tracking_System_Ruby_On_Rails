# Recruiter_and_Applicant_Tracking_System_Ruby_On_Rails
This repository contains code for the application <b>"Recruiter_and_Applicant_Tracking_System"</b>. This web application is built on the <b>Ruby_on_Rails web framework</b> and adopts the <b>MVC</b> and <b>REST</b> architectural paradigm.

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions


Functionality implemented so far:

ADMIN: 

1.  A user is preconfigured with the below credentials.

    email: <b>Admin@ncsu.edu</b>

    password: <b>12345abc</b>

2.  New users can be created using the Sign Up functionality.

3.  After logging in with the preconfigured credentials, the admin can can perform the following functionalities.

    3.1 Edit profile

    3.2 Create company

    3.3 View the list of users and their profile details (except password)

    3.4 View the list of companies, along with detailed information

    3.5 View the list of applications, along with detailed information

    3.6 Log Out of his profile

    3.7 See all the user profiles

    3.8 Create and delete user profiles
    
    3.9 Edit Company Information
    
    3.10 Edit Recruiter information
    
    3.11 View the list of jobs and detailed requirements.
    
    3.12 Delete companies/users (recruiters or job seekers)/jobs/applications from the system

  To assist in understanding what we have so far, here is a series of pictures.

<h2>1. Login page</h2>
<a href="https://ibb.co/jO6yiH"><img src="https://preview.ibb.co/cor9qx/image.png" alt="image" border="0"></a>

First, the user would be treated to the Login homepage.  The Admin would enter their email and password in the textbook and then click the "Log In" button.

<h2>2. Admin Home page</h2>
<a href="https://ibb.co/jqar3H"><img src="https://preview.ibb.co/dYDNAx/image.png" alt="image" border="0"></a>

The Admin now has access to the following options:
    <h3>1. Creating a Recruiter Account</h3>
    <h3>2. Creating a Job Seeker Account</h3>
    <h3>3. Create a new Company</h3>
    <a href="https://ibb.co/fz77Ax"><img src="https://preview.ibb.co/dRWZqx/image.png" alt="image" border="0"></a>
    <h3>4. View all Companies and their information</h3>
    <a href="https://ibb.co/iLVSAx"><img src="https://preview.ibb.co/d49yHc/image.png" alt="image" border="0"></a>
    <h3>5. View all Jobs and their information</h3>
    <a href="https://ibb.co/irBCcc"><img src="https://preview.ibb.co/iEL5xc/image.png" alt="image" border="0"></a>
    <h3>6. View all Applications and their information</h3>
    <a href="https://ibb.co/fnmOiH"><img src="https://preview.ibb.co/dEBpOH/image.png" alt="image" border="0"></a>
    
 Admins can also edit their own profile and delete companies, other users, jobs, and applications from the system.
 <a href="https://ibb.co/kCc7Ax"><img src="https://preview.ibb.co/hiH7Ax/image.png" alt="image" border="0"></a>
 
<h2>3. Sign In Page</h2>
<a href="https://ibb.co/efeb3H"><img src="https://preview.ibb.co/f4WCcc/image.png" alt="image" border="0"></a>

Finally, new users and the Admin can sign up a Recruiter or Job Seeker by entering their name, email, and password.


<h2> RECRUITER </h2>

The below functionalities have been implemented.

4. New Recruiters can be created using the Sign Up functionality.

After Signing Up, The Recruiter can perform the below functionalities:

 4.1 Log in with email and password

 4.2 Edit their own profile to choose an existing company or add a new company. Each recruiter can only work for one company

 4.3 Edit company information

 4.4 Publish jobs

 4.5 Edit job information that they have posted. Cannot edit jobs posted by other recruiter

 4.6 Close a job

 4.7 View applicants for any job in the company.

NOTE :Change job seekers’ submittal status for those seekers who have applied to jobs which the recruiter has posted- This  functionality could not be implemented

<h2> JOB SEEKER </h2>

5. The below functionalities have been implemented.

    5.1. Anyone can sign up as a Job seeker

    5.2. Log in with email and password.

    5.3. Search available jobs using filters, such as company name, industry, company size, location (We have implemented the method but   the filter functionality is not properly working)

    5.4. View company information.

    5.5. View job information.

 5.6. Submit an application for a certain job

NOTE:Upload their resume or other supporting documents and link to corresponding application. (This functionality could not be implemented )



<h2> TESTING </h2>

RSpec Testing could be done for only 1 Model (Company.rb)

<h2> DEPLOYMENT </h2>

The application is hosted on Heroku.


We appreciate any feedback you might have for this very basic application.
