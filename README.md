# LinShare

## Description

Specially designed to secure paperless file sharings within companies that put
privacy and traceability in the heart of their problems of exchange, LinShare
provides a simple solution completely intuitive.

* Linshare allows employees to upload files into their space
* Linshare can share files with internal or external collaborators
* Linshare offers several features to securely exchange

More information on http://www.linshare.org/

## Live demo:

A Live demo of LinShare is available at https://demo.linshare.org/.
This demo reflects the latest developments done on LinShare, it will be
reseted and updated on regulary basis.

This instance of LinShare is set up with some test users, from user1 to user7 :
 * user1@linshare.org : password1
 * user2@linshare.org : password2
 * user3@linshare.org : password3
 * user4@linshare.org : password4
 * user5@linshare.org : password5
 * user6@linshare.org : password6
 * user7@linshare.org : password7

If you want to share with some external users, use these two email addresses *external1@linshare.org* and *external2@linshare.org*.
External users are just an email address without an account. You can also use these two emails to create guests.

NB: You won't able to send or receive emails if your email address is not @linshare.org.

In order to see emails sent by LinShare, we also put at your disposal a webmail
available at *https://demo-webmail.linshare.org*.

Webmail passwords :
 * user1@linshare.org : password1
 * ...
 * external1@linshare.org : password1
 * external2@linshare.org : password2


## All repositories

LinShare is now splitted into multiple repositories.
You can clone the whole project using the following commands :

### Main repository:

* git clone https://github.com/rasata/linshare.git

NB: You can download all components using Maven:

$ mvn dependency:copy-dependencies -DoutputDirectory='linshare'

### LinShare server components:

* git clone https://github.com/rasata/linshare-core.git
* git clone https://github.com/rasata/linshare-ui-admin.git
* git clone https://github.com/rasata/linshare-ui-user.git
* git clone https://github.com/rasata/linshare-ui-upload-request.git
* git clone https://github.com/rasata/linshare-ui-upload-proposition.git
* git clone https://github.com/rasata/linshare-upload-proposition.git

### LinShare client components:

* git clone https://github.com/rasata/linshare-plugin-thunderbird

### For tests and demonstration:

* git clone https://github.com/rasata/linshare-docker

