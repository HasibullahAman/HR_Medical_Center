
--------- HR Medical Center Documentation-->Software Requierment Spesficaation--------

1.introduction
        My project Hospital Management system includes registration of patients,
    storing their disease details into the system. My software has the facility to give a
    unique id for every patient and stores the details of every patient. The Hospital
    Management System can be used by entering respective username and password.
    It is accessible either by an administrator or receptionist. Only the respective
    person can add data in the database. The data can be retrieved easily. The interface
    is very user-friendly.

    1.1 Purpose
        A hospital management system is a software designed to manage all the areas
    of a hospital such as medical, financial, administrative and the corresponding
    processing of services ,The system should have a page that can determine the
    appointment time for patients who want to make an appointment with doctors.
    Doctors advise patients to reserve their time to meet new patient a patient can
    close our specialized departments and go to the hospital.

    1.2 Project Scope
        Daily functions like patient registration, managing admission and overall
    management of various departments can be easily performed with higher accuracy
    after the accessing the HR Medical Center website. The modules of hospital
    management software are user-friendly and easy to access.
    Currently HR medical Center is using a manual system to handle the
    hospital process, When patients arrive they make an appointment at the
    reception to consult a Doctor.
    These are being recorded in a file. Then again the patients diagnosed symptoms
    related disease details, ward details and other necessary details are being
    recorded and those files are being stored in special locations.
    We plan to overcome the above mentioned problems through a standalone
    application, to manage the major functions of the Hospital System.
        • A patient should be able to get information about our center without
        visiting our center7
        • Get to know the specialized staff of doctors that our center has
        assembled
        • Know the facilities that are available in our hospital
        • Patients can be informed and benefit from our free services
        • able to schedule appointments with doctors
        • On the other hand, our doctors can give appointments to new
        patients.

    1.3 Terms, Acronyms
        DFD: – Data Flow Diagram
        HR-SRS:- HR Software Requirement Specification
        HRMC: - HR Medical Center
        IDE: – Integrated Development Environment
        SQL: – Structured Query Language
        SRS: – Software Requirement Specification.
        GUI: - Graphical User Interface
        EDM: Entity data Model
        Ms Sql: Microsoft Structured Query Language

    1.4 References
        1. https://en.wikipedia.org/wiki/Health_administration
        2. www.apollohospitals.com
        3. https://www.scribd.com/doc/60567651/apollo
        4. http://www.slideshare.net/HimaniChopra/apollo
        5. http://www.dotnetfunda.com/articles/show/1052/sample-softwarerequirements-specification-forhospital-info-managemen

2. Over All Description
    2.1 Product perspective
        Our website is intended to use in order to improve medical treatments and
        make it easy for healthcare workers to store patient history and make
        appointments online etc.
        hospitals still spend considerable time and money on managing patient data and
        scheduling appointments etc. The reason for this is that hospital requirements
        differ greatly from those of other companies. Our health care system is an online
        application tailored to the needs of a hospital.
        The fully functional automated hospital management system which will be
        developed through this project will eliminate the disadvantages caused by the
        manual system by improving the reliability, efficiency and performance. The usage
        of a database to store patient, employee, stock details etc. will accommodate easy
        access, retrieval, search and manipulation of data. The access limitations provided
        through access privilege levels will enhance the security of the system. The system
        will facilitate concurrent access and convenient management of activities of the
        medical center.

    2.2 Product features

        2.2.1 Registration: When a patient is admitted, the front-desk staff checks to see if
        the patient is already registered with the hospital. If he is, his/her Personal Health
        Number (PHN) is entered into the computer. Otherwise a new Personal Health
        Number is given to this patient. The patient’s information such as date of birth,
        address and telephone number is also entered into computer system.
        2.2.2 Admin: This module provides all main hospital entry details such as
        consultation details, specialization of the doctor, consultancy fees and service fees.
        2.2.3 Pharmacy: All medical items are covered in this module. This module
        supports Item Master, Drugs receipts, problem handling, material return, retail
        bill generation, inventory maintenance. It also helps to meet both IPD and OPD
        Pharmaceuticals requirements.   

        2.2.4 Patient Module: The different functionalities of the module are listed below:
            • Search Reposts
            • Search his record
            • Make appointment
            • Use our free service

        2.2.5: Doctors Module:
            • Add patients report
            • Give Prescriptions
            • Accept/reject appointment
            • Take appointment time for patient

    2.3 User Class and Characteristic
        In our healthcare system we have three main users i.e. patients, doctors, admin.
        Following are the main functionalities and characteristics of them.

        2.3.1 Patients: patient shale to be able to:
            • Create his/her Account
            • Book an appointment
            • Cancel an appointment
            • Search medicine

        2.3.2 Doctors: Doctors shale to be able to:
            • Create his/her Account
            • Edit Personal Account
            • Add New patient
            • Cancel appointment
            2.3.3 Administrator: Admin shale to be able to:
            • Active or de active a doctor
            • Create a doctor’s account10

    2.4 Operating Environment
        1) The System shall operate correctly with the following web browsers: Firefox
        versions 28 through 48; Google Chrome (all versions); and Apple Safari
        versions 8.0 through 11.1
        2) The system shall use MYSQL database for storing and maintaining record of
        the health care patients, doctors and their appointments etc.
    2.5 Design and implementation constraints
        1) The system shall use the open source tools.
        2) The system should work on any internet browser with GUI whether the
        underlying Operating System is Windows.
    2.6 Assumptions and Dependencies
        Following are the assumptions and dependencies for our software system:
    2.6.1 Usability: It is assumed that all user web pages should be in accordance
    with standardized colors and fonts. The users will receive on the-spot
    instructions on the step in the presentation of the Web pages.
    2.6.2 User Request: The database of the system will manage without default
    a maximum of 50 users.
    2.6.3 Requirements: It is assumed that requirements will not change for the
    software project over time
    And some other Assumptions:
        ● Each user must have a valid user id and password
        ● Server must be running for the system to function
        ● Users must log in to the system to access any record.
        ● Only the Administrator can delete records.

3. System Features
    Following are the main features of our healthcare system.

    3.1 Registration: This module allows patient information to be recorded and IPD
        and OPD patient Inquiries to be handled. After registration, a unique ID is produced
        for each patient. This helps to manage customer relationships and maintains the
        patient's medical history.

    3.2 Reception Module:
        • Doctor visit schedule
        • Doctor Appointment Scheduling
        • Enquiry of patient
        • Find history of patient enquired
    3.3 Admin: his module provides all main hospital entry details such as consultation
    details, specialization of the doctor.

4. Non-Functional Requirement

    4.1 Performance
    The average response time per every user click shall be less than 4 seconds.
    And the maximum average time per every click shall be less than 6 seconds.

    4.2 Usability
    The system user interface shall be user friendly. i.e. the minimum amount
    of time taken by novice user to learn the system shall be 15 minutes.

    4.3 Maintainability
    The system can make new changes on the basis of the requirements, if
    demanded after completion of the system. The maintainability of the system can12
    be done by integrating new modules and offering new solutions for the raised
    problems.

    4.4 Reliability
    • The system shall have less than 6 hours downtime per two months
    • Maximum Bugs per 1000 lines should not be greater than.

5. External Interface Requirements

    5.1 User Interface
    I will extend some picture of my project when I complete it.

    5.2 Hardware Interface
        • Processor: Pentium IV AND motherboard
        • RAM: 512 or Above
        • Hard disk: 40 GB or above
        • Input Device: Key bord, Mouse
        • Output Device: Monitor, VGA

    5.3 Communication Interface
        • NIC (Network Interface Card) - It is a computer hardware
        component that allows a computer to connect to a network.
        NICs may be used for both wired and wireless connections.
        • CAT 5 network cable- for high signal integrity
        • TCP/IP protocol- Internet service provider to access and share
        information over the Internet.
        • Ethernet Communications Interface- Ethernet is a frame-based
        computer network technology for local area networks (LANs)
        • Ubiquitous, easy to set up and easy to use. Low cost and high
        data transmission rates.