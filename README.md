# Contact app project
*This is a really simple project to manage a contact list*


User would first land at the **login** page.

## login page
User should see a **login** box and **create an account** page.
In **login box** the user would enter its credential and click login button.
If authentication succeeds user would be redirected to its **dashboard** otherwise to **login error** page.

## create an account page
User would choose a login/password and save it so its account is created. Then it would be redirected to **dashboard** page.

## login error page
The user would see an authentication error message and a link to go back to **login** page.

## dashboard
The user would see all its contacts with a link to **contact update** page and a link to **contact delete** for each of them.
There should be a link to **contact create**
There should be a link to **logout**

## contact create
The user should be able to enter a name a surname and a phone number for its contact. He should click a save button wich would save its contact. Then it would be redirected to **dashboard**

## contact update
The user should see the information of the contact he choosed and be able to update any of it.
When clicking save button the contact would be update and the user redirected to **dashboard**

## contact delete
When clicking on a contact's delete link, the contact should be deleted and the **dashboard** should be refreshed.

## logout
User would be logged out and redirected to **landing** page

## Objects

### ContactApp object
ContactApp object would be responsible for
* user creation
* user update
* user login
* read from the storage
* write to the storage

### User object
User object must have the following methods:
* create a contact
* update a contact
* delete a contact
* list all of the its contacts
User object would have a list property to store its contact

### Contact object
Contact object need to have:
* name property
* surname property
* phonenumber property
