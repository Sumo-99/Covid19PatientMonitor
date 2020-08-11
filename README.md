# Covid19PatientMonitor

A web application that is capable of monitoring the health status of isolated quarantined patients, remotely by doctors.
The ideal version would send patient information to doctors, as read from any monitoring devices (pulse oximeter,heart rate monitor, etc.)
This application runs a simulation of mocked data, such that whenever a patients readings fluctuate out of the safe health range, a live alert
would be sent to the doctors monitoring  said patients.

Frontend implemented using HTML,CSS, and React JS
Backend implemented using a Java REST API and ofcourse an SQL database

##User Profiles
Includes separate UI modules for :
<ul>
<li>Patient</li>
<li>Doctor</li>
<li>Admin</li>
</ul>

##User Profile Description
<p>
Patients must sign up, and once they are registered by a doctor or administrator they can view their vital health information through the patient portal.
Doctors are registered under the admin portal. They can :
<ul>
<li>Register Pateints under them, if they have created accounts</li>
<li>View a list of registered patients under the current doctor account</li>
<li>View the vital health information of registered patients</li>
<li>View patient health fluctuation alerts (if any), under the alerts tab</li>
</ul>
Administrators for the sake of this simulation are assumed to already have accounts created
They are capable of adding,updating or deleting both patient and doctor profiles
</p>

## SETUP
You will need
<ul>
<li>HTML 5, CSS 3, Node - to run React JS</li>
<li>Java JRE to run the backend server and REST API</li>
<li>MY SQL versions 8.0.21</li>
</ul>



## RUN
Uncomment the local host url in react/src/App.js, and remove the currently set url (check lines 18,19)

Use <code>npm start</code> to start the application

Hits:
[![HitCount](http://hits.dwyl.com/Sumo-99/Covid19PatientMonitor.svg)](http://hits.dwyl.com/Sumo-99/Covid19PatientMonitor)

<hr>