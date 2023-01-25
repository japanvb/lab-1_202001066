 <h1>  IT314 Lab-1  Identifying Functional and Non-Functional Requirements </h1>
 <h2> Japan Vijay Bhatt</h2>
<h2> 202001066 </h2>

***Q.1. Identify FRs and NFRs of LIS :***

<ins>**Functional Requirements**</ins>

* The system must ensure that all the content available in the library should be available, visible and accessible remotely, to the users on the system website.
* The user must login into the system’s website using the login credentials of the institute and using the institute’s LAN network, in order to access the system.
* Only the librarian should be allowed to add a new record or remove a record from the system.
* Users can search the books on the website and check their current status.
* Users can take membership of the system.
* Membership allows issuing of the books in the system.
* A member can also reserve a particular book, if it is currently issued by someone else.
* A user can also extend his due date if there is no booking for that particular book.
* Non-members can only view the contents of the system.
* A mail is sent to the user when he issues a book,  that includes the date of issue, name of the book issued and the due date of the book.
* A notification email is sent to both the librarian and the member if he has a book which is overdue.
* The system calculates the fine for overdue books on their return. 

<ins>**Non-Functional Requirements**</ins>

* **Usability** - The UI of the website should be simple yet elegant so that every type of user can search books and perform other actions easily, without any special training. Option  for different language and voice assistant cna help in hinderless access.
* **Accuracy** - The data stored about the books and the fines calculated should be correct, consistent, and reliable.
* **Availability** - The website should be accessible within the operating hours of the library. The system should be able to respond within 3 seconds of the request.
* **Security** - The website should not transit any sensitive information such as passwords.
* **Compatibility** - The website should be easily accessible through any basic web browser that supports html5.
* **Maintainability** - Adding new features to the website or making basic changes should be as easy as possible and maintainable.



***Q.2. Identify scope, features and non-functional aspects of hearing aid software.***

<ins>**Scope**</ins>

The software is aimed to provide a smart AI-based real time helping hand to the people who require hearing aids. It can be easily linked to the user’s android device for all time access. This application helps the user by giving alerts, in order to create a real time surrounding for the user. It is supposed to be most useful in identifying immediate actions such as car horns, babies, etc. and display them on the screen and vibrate the device to notify the user.


<ins>**Functional Aspects**</ins>

* It can access the microphone of the mobile device to record the surrounding sounds.
* It detects sounds and notifies the user by displaying them on the mobile screen and also vibrates the device.
* The application runs in the background, to capture any sound that might require an immediate alert notification.
* The software uses a pre-trained AI model to identify sounds.
* Users can record and enter custom sounds for some custom notifications if they want.
* Users can choose to prioritize the notifications over other notifications and applications. By default it is turned on.


<ins>**Non-Functional Aspects**</ins>

* The application has a simple UI that can be understood and usable by any user.
* The application is active all the time in the background for emergency alerts but for normal use it must be opened.
* The software prioritizes the alert notifications over the other notifications on the mobile screen, irrespective of the user using any other application.
* The software notifies the user within 3 seconds of sound detections.
* The software can work without any internet connection for day to day sounds.
* The data stored about the sounds should be correct, consistent, and reliable.
* The application is compatible with any android or ios device with 4GB of RAM.
