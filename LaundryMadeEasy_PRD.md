# LaundryMadeEasy

## Product Requirements Document (PRD)

**Document version:** 1.0\
**Date:** 25 November 2026\
**Product type:** Web and mobile application\
**Primary users:** University students and laundry service providers\
**Status:** Proposed product / initial requirements

------------------------------------------------------------------------

## 1. Product Overview

LaundryMadeEasy is a web and mobile application intended to make laundry
management easier, more organised, and more reliable for university
students. The platform will allow students to book laundry services,
document the clothes they submit, track the progress of their orders,
and communicate with laundry service providers.

Laundry service providers will be able to receive orders, confirm
clothing items, update order statuses, and maintain accurate records.
The product is designed to reduce misplaced or mixed-up clothes, improve
communication, and give students more time to focus on their studies and
other activities.

## 2. Problem Statement

University students often struggle to manage laundry regularly because
of busy academic schedules and other daily activities. Students who use
laundry services may also find it difficult to remember exactly which
clothes they have submitted, keep track of their orders, or know when
their clothes are ready.

Poor documentation and communication can lead to misplaced or mixed-up
clothes, delayed returns, and uncertainty about the status of laundry
orders. There is a need for a simple system that helps students and
laundry providers document, manage, and track laundry transactions.

## 3. Proposed Solution

LaundryMadeEasy will provide a central platform through which students
can:

-   Find and access participating laundry services.
-   Create laundry orders and record each clothing item submitted.
-   Specify item details such as type, colour, quantity, and special
    instructions.
-   Receive a digital receipt and unique order reference.
-   Track the progress of laundry orders.
-   Receive notifications when an order changes status or is ready for
    collection.
-   View previous orders and report missing or damaged items.

Laundry attendants and business owners will be able to manage incoming
orders, confirm item counts, update order progress, and keep accurate
service records.

## 4. Product Objectives

LaundryMadeEasy aims to:

1.  Make laundry booking easier and less stressful for university
    students.
2.  Provide accurate digital documentation of clothes submitted for
    washing.
3.  Allow students to monitor the status of their laundry at each stage.
4.  Reduce cases of missing, mixed-up, or unaccounted-for clothing.
5.  Improve communication between students and laundry service
    providers.
6.  Help laundry businesses organise orders and maintain service
    records.
7.  Give students more time to focus on their studies and other
    important activities.

## 5. Target Users

### 5.1 Primary users

-   **Students:** People who need to do laundry and want a convenient
    way to book services and track submitted clothes.

### 5.2 Operational users

-   **Laundry attendants/workers:** People responsible for receiving,
    washing, drying, ironing, folding, and returning clothes.
-   **Laundry business owners:** People who manage laundry operations,
    staff, service offerings, pricing, and customer satisfaction.
-   **System administrators:** People responsible for managing the
    platform and its users.

### 5.3 Supporting users

-   **Payment providers:** External services that process payments made
    through the platform, if in-app payment is supported.

## 6. Stakeholders

The five major stakeholders identified for LaundryMadeEasy are:

1.  **Students:** Use the application to request laundry services,
    submit clothing details, make payments where supported, and track
    orders.
2.  **Laundry workers:** Receive and process clothes, verify item lists,
    update order statuses, and prepare completed orders for collection.
3.  **System administrators:** Manage platform operations, user access,
    and system configuration.
4.  **Laundry business owners:** Manage their laundry businesses, staff,
    services, prices, orders, and customer experience.
5.  **Payment providers:** Support secure processing and confirmation of
    payments made through the platform.

## 7. User Research: Student Survey

A preliminary survey was conducted with 10 students to understand their
laundry habits, challenges, and preferred application features.

### 7.1 Survey questions

1.  What is your level and gender?
2.  Where do you currently do your laundry?
3.  How often do you do laundry?
4.  Do you use a laundry service?
5.  Have you ever lost, mixed up, or been unsure of clothes given out
    for laundry?
6.  If yes, how did it affect you?
7.  How do you currently keep track of clothes given out?
8.  How satisfied are you with your current laundry process, on a scale
    of 1--5?
9.  Which features would you want most?
10. Would you use a web or mobile application for this?

### 7.2 Survey responses

  ----------------------------------------------------------------------------------------------------------------------------------
  Student      Level Gender   Laundry    Frequency   Uses        Clothing issue Effect /      Satisfaction Preferred feature Would
                              location               laundry     experienced?   tracking            (1--5)                   use
                                                     service?                   method                                       app?
  --------- -------- -------- ---------- ----------- ----------- -------------- ----------- -------------- ----------------- -------
  1             100L Male     Hostel     Weekly      Sometimes   Yes            Wrong                    3 Clothes tracking  Yes
                                                                                clothes                    list              
                                                                                returned;                                    
                                                                                uses memory                                  

  2             200L Female   Home       Every 2     No          No             No impact;               4 Pickup/delivery   Maybe
                                         weeks                                  keeps no                   alerts            
                                                                                record                                       

  3             300L Male     Laundry    Weekly      Yes         Yes            Lost                     2 Order history     Yes
                              service                                           clothes;                                     
                                                                                uses phone                                   
                                                                                notes                                        

  4             400L Female   Hostel     Monthly     No          No             No impact;               3 Payment           Maybe
                                                                                uses memory                                  

  5             500L Male     Laundry    Weekly      Yes         Yes            Delayed                  2 Clothes tracking  Yes
                              service                                           return;                    list              
                                                                                uses                                         
                                                                                notebook                                     

  6             200L Male     Home       Every 2     No          No             No impact;               4 Payment           Maybe
                                         weeks                                  keeps no                                     
                                                                                record                                       

  7             300L Female   Hostel     Weekly      Sometimes   Yes            Wrong                    3 Laundry service   Yes
                                                                                clothes                    ratings           
                                                                                returned;                                    
                                                                                uses memory                                  

  8             100L Female   Laundry    Monthly     Yes         Yes            Lost                     1 Clothes tracking  Yes
                              service                                           clothes;                   list              
                                                                                uses                                         
                                                                                notebook                                     

  9             400L Male     Hostel     Weekly      Yes         No             No impact;               4 Order history     Yes
                                                                                uses phone                                   
                                                                                notes                                        

  10            500L Female   Home       Rarely      No          No             No impact;               3 Pickup/delivery   No
                                                                                uses memory                alerts            
  ----------------------------------------------------------------------------------------------------------------------------------

### 7.3 Preliminary findings

Based on the 10 responses:

-   **5 out of 10** students reported having experienced lost, mixed-up,
    or uncertain laundry items.
-   **5 out of 10** students use laundry services either regularly or
    sometimes.
-   **5 out of 10** students said they would use a web or mobile
    application; **4** said maybe, and **1** said no.
-   Students currently rely on memory, notebooks, phone notes, or no
    record at all to keep track of clothes.
-   Clothes tracking was the most frequently selected feature, followed
    by order history, pickup/delivery alerts, payment, and service
    ratings.
-   Satisfaction ratings ranged from 1 to 4, with an average of **2.9
    out of 5**.

These findings suggest that clothing documentation and order tracking
are important areas to address. The survey is preliminary and based on a
small sample of 10 students, so it should not be treated as
representative of all university students.

## 8. Product Scope

### 8.1 MVP scope

The first version should prioritise the core workflow needed to document
and track laundry orders:

-   Student and laundry staff account registration and login.
-   Creation of laundry orders.
-   Recording clothing type, colour, quantity, and notes.
-   Digital order receipt and unique order ID.
-   Attendant confirmation of received clothing and item count.
-   Order status updates.
-   Student order history and order tracking.
-   Basic notifications for important order status changes.
-   Basic administrative management of users, services, and orders.

### 8.2 Future enhancements

The following features may be introduced after the core workflow is
working reliably:

-   QR-code scanning at drop-off and collection.
-   In-app payments and payment-provider integration.
-   Pickup and delivery scheduling.
-   Recurring laundry reminders.
-   Ratings and reviews for laundry providers.
-   Photo attachments for clothing items.
-   Missing or damaged item dispute management.
-   Advanced business analytics and reports.
-   Multiple laundry business listings and service comparisons.

## 9. Functional Requirements

Functional requirements describe what the system must do.

### FR-01: User Accounts

-   Users must be able to register and log in.
-   The system must support appropriate roles, including students,
    laundry attendants, business owners, and administrators.
-   Users must be able to manage profile information such as name,
    hostel or room, phone number, and email address.
-   Users must be able to reset forgotten passwords.
-   The system must restrict role-specific functions to authorised
    users.

### FR-02: Laundry Order Creation

-   Students must be able to create a new laundry order.
-   Students must be able to select a drop-off date and time or an
    available service slot.
-   Students must be able to add clothing items with details such as
    item type, colour, quantity, and special instructions.
-   Students may attach photos of clothing items where supported.
-   Students must be able to choose a service type, such as washing,
    ironing, wash and iron, or dry cleaning.

### FR-03: Documentation and Receipts

-   The system must generate a unique reference ID for every order.
-   The system must generate a digital receipt containing the order
    details and item quantities.
-   Laundry attendants must be able to confirm the clothing items and
    quantities received.
-   Any difference between the submitted item list and the items
    received must be recorded.
-   The system must maintain an order history for each student.
-   The system should support a QR code linked to an order for
    verification.

### FR-04: Order Tracking

-   Students must be able to view the current status of each order.
-   The system must support the following order statuses: Received,
    Washing, Drying/Ironing, Ready, and Collected.
-   Authorised laundry staff must be able to update order statuses.
-   Students should receive notifications when important order status
    changes occur.
-   The system should support QR-code scanning at collection to help
    confirm handover.

### FR-05: Scheduling and Reminders

-   Students should be able to book available pickup or drop-off slots
    where the service supports scheduling.
-   Students should be able to set recurring laundry reminders.
-   The system should notify students when completed orders remain
    uncollected.
-   The system should prevent conflicting bookings for unavailable time
    slots.

### FR-06: Issue and Dispute Handling

-   Students must be able to report missing or damaged clothing items
    against an order.
-   Reports must be linked to the relevant order and its original item
    record.
-   The system should make available any relevant item photos and
    drop-off confirmations.
-   Students and authorised staff should be able to view the status of a
    report.
-   Dispute statuses should include Open and Resolved.

### FR-07: Laundry Attendant Functions

-   Attendants must be able to view incoming and assigned orders.
-   Attendants must be able to confirm received clothing items and
    quantities.
-   Attendants must be able to update order statuses.
-   Attendants must be able to search for orders by order ID, student
    name, or date.
-   Attendants must be able to mark orders as collected after handover
    confirmation.

### FR-08: Administration and Business Management

-   Administrators must be able to manage user accounts and access.
-   Authorised business owners or administrators must be able to manage
    laundry service types and prices.
-   The system should provide reports such as daily orders, pending
    orders, completed orders, and open disputes.
-   The system must allow authorised users to review and manage orders.

### FR-09: Payments

-   The system must calculate an order's cost based on selected
    services, quantities, and configured prices.
-   The system must record whether an order is paid or unpaid.
-   If in-app payment is enabled, the system must integrate with a
    payment provider.
-   The system must record payment references and payment outcomes.
-   The system must not mark a payment as successful until confirmation
    is received from the payment provider.

## 10. Non-Functional Requirements

Non-functional requirements describe how well the system should operate
and the standards it must meet.

### NFR-01: Performance

The system should load its main pages and display ordinary order
information within 3 seconds under normal network conditions.

### NFR-02: Security

The system must protect user accounts and information through secure
authentication, appropriate access controls, and safe handling of
sensitive data.

### NFR-03: Reliability

The system must save valid bookings and order updates correctly. It
should prevent accidental duplicate submissions where possible and
provide clear feedback when an operation fails.

### NFR-04: Usability

The platform must have a simple, clear, and consistent interface that
students and laundry staff can use without extensive training.

### NFR-05: Availability

The platform should be available whenever users need to access it, apart
from planned maintenance or unexpected service interruptions.

### NFR-06: Privacy

The system must restrict access to personal information and ensure that
users can only view information they are authorised to access.

### NFR-07: Scalability

The system should be designed to support an increasing number of
students, laundry providers, orders, and transactions without major
performance problems.

### NFR-08: Compatibility

The application should work on commonly used mobile phones, tablets, and
desktop computers through supported browsers or supported mobile
platforms.

### NFR-09: Maintainability

The system should be organised and documented in a way that allows
developers to identify faults, maintain the codebase, and introduce
updates efficiently.

### NFR-10: Data Integrity

The system must maintain accurate and consistent user, clothing, order,
and payment records. Updates must not unintentionally overwrite or
corrupt existing records.

## 11. Key User Stories

-   **As a student,** I want to create a list of clothes before
    submitting them so that I have a record of everything I gave out.
-   **As a student,** I want to receive a digital receipt so that I can
    confirm the details of my laundry order.
-   **As a student,** I want to track my order status so that I know
    when my clothes are ready.
-   **As a student,** I want to view my previous orders so that I can
    check my laundry history.
-   **As a student,** I want to report missing or damaged clothes so
    that the laundry provider can investigate the issue.
-   **As a laundry attendant,** I want to confirm the items received so
    that the recorded list matches the clothes handed over.
-   **As a laundry attendant,** I want to update order statuses so that
    students can follow the progress of their laundry.
-   **As a laundry business owner,** I want to manage services and
    prices so that customers see the correct offerings.
-   **As an administrator,** I want to manage users and review system
    activity so that the platform operates properly.

## 12. Core User Workflow

1.  A student creates an account or logs in.
2.  The student selects a laundry provider or available laundry service.
3.  The student creates an order and records each clothing item.
4.  The system generates an order ID and digital receipt.
5.  The laundry attendant checks the clothes and confirms the received
    items.
6.  The laundry attendant processes the order and updates its status.
7.  The student receives updates and checks the order through the
    application.
8.  When the order is ready, the student is notified.
9.  The student collects the clothes and the attendant confirms the
    handover.
10. The completed order is saved in the student's order history.

## 13. Assumptions and Dependencies

-   Students and laundry providers have access to a supported device and
    an internet connection.
-   Laundry providers participating in the platform will have access to
    the attendant or business interface.
-   Each laundry provider is responsible for accurately confirming the
    clothes received.
-   Service availability, prices, and operating hours must be configured
    by authorised business users.
-   Push notifications depend on device and platform notification
    permissions.
-   Online payments depend on integration with a supported payment
    provider.
-   QR-code functionality depends on suitable device camera access and a
    working order-verification process.

## 14. Success Measures

The first version of LaundryMadeEasy should be evaluated using
measurable indicators such as:

-   Number of students who successfully register.
-   Number of laundry orders created and completed.
-   Percentage of orders with confirmed clothing-item records.
-   Percentage of orders updated through the full status workflow.
-   Number of missing-item or damaged-item reports.
-   Time taken to process and complete orders.
-   Student satisfaction ratings and feedback.
-   Percentage of students who use the platform again.

Specific numerical targets should be agreed upon after initial testing
and feedback from students and laundry providers.

## 15. Out of Scope for the Initial Release

Unless the development team decides otherwise, the following are not
required for the first release:

-   Automated laundry machines or hardware integration.
-   AI-based clothing recognition.
-   Nationwide delivery logistics.
-   Complex loyalty and reward programmes.
-   Advanced business intelligence and financial forecasting.

## 16. General Conclusion

LaundryMadeEasy is a proposed laundry service platform designed to
address common laundry challenges experienced by university students.
These challenges include limited time, difficulty accessing reliable
laundry services, delayed orders, misplaced clothing, and poor
communication between students and laundry providers.

The proposed system will provide a convenient and organised platform
where students can access laundry services, create bookings, document
the clothes they submit, view prices, and monitor the progress of their
orders.

Through stakeholder identification, student surveys, user stories, and
the definition of functional and non-functional requirements, this
document establishes an initial understanding of user needs and the
expected behaviour of the system.

The first version of LaundryMadeEasy will focus on essential features
that provide value to students and laundry providers while leaving room
for future improvements.

In conclusion, LaundryMadeEasy aims to make laundry management easier,
more convenient, and more reliable for university students through a
simple and accessible digital solution.

------------------------------------------------------------------------

## 17. Document Notes

This PRD is an initial product definition. Requirements may be refined
after discussions with students, laundry attendants, business owners,
and the development team. Any change to the agreed scope or requirements
should be documented and reviewed before implementation.
