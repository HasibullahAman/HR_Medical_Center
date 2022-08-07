
--------- HR Medical Center Documentation-->Software Requierment Spesficaation--------

Need to Work on:
    1. Ability to accept the appointment by the doctor to acknowledge the patient that
    their appointment has been approved.
    2. User should not be allowed to register if he/she tries to provide the already
    registered email ID.
    3. The password should be encrypted and the password field shouldn't be displayed
    in the admin panel.
    4. Implementation of pagination for all the list view across the application.
    5. Bug fix - Bill payment receipt contains multiple record if the patient has
    associated with the same doctor multiple times.
    6. Addition of more fields in the prescription statement to make it more specific
    one.
    7. Addition of more details on payment - such as date of the payment made,
    amount paid, etc.
    8. Complete Other page Like Learn mor the first page, about us, Services
    Component, Specialist blog for every Doctor, Counter section, and Post section.
    9. Our project also has a bug in one part, when a patient registers himself, at the
    same time, he cannot make an appointment with the doctor, and he has to leave
    the dashboard again and log in twice, which I honestly could not solve the
    problem. (N2 description)
    10. Implementation of export button in admin module to export all details to an
    excel sheet.

Prerequisites:
    1. Install XAMPP web server
    2. Any Editor (Preferably VS Code or Sublime Text)
    3. Any web browser with latest version
    Languages and Technologies used:
    1. HTML5/CSS315
    2. JavaScript (to create dynamically updating content)
    3. Bootstrap (An HTML, CSS, and JS library)
    4. XAMPP (A web server by Apache Friends)
    5. PHP

Steps to run the project in your computer:
    1. Download and install XAMPP in your computer
    2. Clone or download the repository
    3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
    4. Start the Apache and Mysql in your XAMPP control panel.
    5. Open your web browser and type 'localhost/phpmyadmin'
    6. In phpmyadmin page, create a new database from the left panel and name it as
    'myhmsdb'.
    7. Import the file 'myhmsdb.sql' inside your newly created database and click ok.
    8. Open a new tab and type 'localhost/foldername' in the url of your browser

SOFTWARES USED:
    • XAMPP was installed on the Ubuntu 20.0 machine and APACHE2 Server and
    MySQL were initialized. And, files were built inside opt/lampp/htdocs/myhmsp
    • Visual Studio Code V (1.69) used as a text editor.
    • Google Chrome Version 103.0.5060.114 was used to run the project.

Starting Apache and MySQL in XAMPP:
    The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To

start Apache or MySQL manually.
    Windows 10:photo is taken from window 10 operating system.16

Getting into the project:
    -The website that we have created for HR Medical center has a page called Home
    in the first part, which is considered the first page of the site, which can be used
    to refer to all the parts that have been added to the site. and returned twice.
    -Click on any button and you will be redirected to the corresponding page.
    -You can get information about the hospital in the About us section.
    -In the Services section, you can see all the services offered by the hospital.
    -In the Our top Specialists section, you can get to know the top specialists of the hospital and get your information.
    -In the People's Review section, you can find people's opinions about our center.
    -In the Make an appointment now section, you can schedule your appointment
    with your respective doctor, which of course will direct you to the login page.
    -In the Our Post section, you can read articles and scientific topics written by
    doctors or hospital personnel.
    -And in the end, you will have ways to communicate with us.
    -In the Header part of our site, we have an option called contact, when we click
    on this part, it will take us to the contact page.
    ----------------
    Make appointment: If you want to make an appointment with the doctor, you
    can click on the Learn more section or use the Login section.18
    -After you click on the Learn more or Login sections, you will be directed to such a
    page.
    -------------------
    Registration Page: In this section, whether you are a patient, a doctor, or a site
    administrator, you can enter the site from your respective section, or if you are
    sick and do not have an account, you can create a new account for yourself.
    Let's assume that a person named Ahmed wants to make an appointment with his
    specific doctor. When he clicks on Login, he will be directed to this page.
    Ahmad's account here has the following two states:
    ------------------
    Login page: In the second step, if Ahmed already has an account in this center,
    he can use his previous account and enter the system, he can click on the two
    sections below and enter the login page.
    Then Ahmad will enter the login page.
    who can write his email and password, which has the following two modes.
    After Ahmad enters her Email and Password, the system will check if it is in the
    set or not, and if it is correct, she will be directed to the patient's dashboard, and
    if it is not correct, she will receive an error.
    ----------------
    Patient Dashboard Page: Assuming that Ahmad's password was correct, Ahmad will
    enter his dashboard.
    If Ahmed does not have an account, he must create an account for himself in the
    register section, who can write his basic information and create his account in the
    system, and the information entered by the patient will be used by the
    administrator and the doctor.
    The next page to which the patient will be directed:22
    The patient dashboard page has four parts, the first page is the dashboard page
    itself.
    -----------
    Patient Appointment Page: The second page is the page for making an
    appointment with the doctor, where the patient can determine the doctor's
    profile and appointment time.
    -------------
    Patient Appointment History Page: In the Appointment History section, the patient
    can make a previous appointment with the doctor.
    --------------
    Patient prescription page: In the Prescription section, the patient can see the results
    of the meeting with the doctor
    In the Appointment History section, the patient can use the Cancel button to
    cancel the appointment with the doctor.
    The appointment with the patient can be accepted or canceled by the doctor.
    After the patient sets his appointment, he should wait for the doctor's answer,
    and with the doctor's approval, go to the center.
    -----------------
Doctor Activity:
---------------
Doctor login Page: Now, if a doctor visits the site, he must go through the
following steps.
We assume that our doctor (Ali Mohsen) wants to enter his account, write his
email and password in the Login page and enter his dashboard page.24
Doctor Dashboard: If it is correct, the doctor's email and password will be entered
into her account.
-----------------
Doctor Appointment: The dashboard below Daria has three parts, the dashboard
itself through which the doctor can refer to different parts.25
Appointment section, in this section, the doctor can schedule appointments
requested by patients.
In this section, the doctor can close the patient's profile and confirm or reject the
requested appointment.
If the appointment is accepted by the doctor, the doctor and Marish will meet
physically, and the doctor can write the results of his examinations in this section.
Then these details will be visible to the administrator and the patient.26
And when he clicks on the PreScrib button, he will enter the following page, which
you will return to the first page by clicking on Back to dashboard.
Doctor Prescription list: And in the Prescription List section, the doctor can close the
list of the patient's previous visits and the prescriptions she gave to the patient.
-------------------
Admin:
-------------
Admin login: Now, if the admin wants to enter her page, she can use the login
page that is intended for the admin.
----------------
Admin dashboard: After clicking on Login, you will enter the following page
---------------
Admin View Doctors page: The admin dashboard has several options, one of which
is to show the list of doctors in the center.
-----------
Doctor view patient List: And in the View patient section, the admin can close
the list of available patients.
--------------------
Doctor appointment Details: In the Appointment Details section, the admin
can close the appointment details.
-------------------
Doctor Prescription list: In the Prescription list section, the admin can close the
list of patients with the characteristics and type of illness, as well as the doctor's
diagnosis with the prescribed medicine.
-------------------
Admin Add doctor page: In the Add Doctor section, the admin can add a doctor to
the center, and the same doctor can log in to his account using his password and
email.
We can add a new doctor like the picture below.
Admin delete doctor page: In the Delete Doctor section, the administrator can
delete the doctor, by writing the desired doctor's email and clicking on Delete
Doctor, the administrator can delete the desired doctor.
----------------
Client contact: One of the other features of our site is that the client can send
his opinions and criticisms directly to the site administrator.
By clicking on Contact on our home page, we will be redirected to the following
page.
---------------
Admin queries page: Later, the site admin can close the opinions of the person
in Queries section.