# UMLDiagrams
# UMLDiagrams
A Computer Aided Software Engineering Tools  Lab Project Report on
GMAIL APPLICATION

![Alt text](image-1.png)
Submitted by
S.NITEESH BHARADWAJ    
P.VARSHITH 		       
A.SHIVA RAMA KRISHNA   
Y.M.KHASIM 		       
P.SAI KRISHNA           

Under the Guidance of
Dr. TALAKOTI MAMATHA, Associate Professor


Department of Computer Science & Engineering
SREENIDHI INSTITUTE OF SCIENCE AND TECHNOLOGY
(AUTONOMOUS)
Yamnampet(V), Ghatkesar(M), Hyderabad–501301,Telangana.
2021-2025




CONTENTS
CHAPTER.NO	
1	Introduction	
1.1	Purpose	
1.2	Scope	
2	Software Requirement Specification Document	
2.1	Functional Requirements	
2.2	Non-Functional Requirements	
2.3	Logical Database Requirements	
3	Model/Design	
3.1	Use case Diagram	
3.2	Class and Object Diagram	
3.3	Sequence and Collaboration 	
3.4	Activity Diagram	
3.5	State Chart Diagram	
3.6	Component Diagram	
3.7	Deployment Diagram
4	Conclusion	
5	References	

1.Introduction
1.1	Purpose
Signing in to your account When you first create your account, you will be automatically signed in. Most of the time, however, you’ll need to sign in to your account and sign out when you’re done with it. Signing out is especially important if you’re using a shared computer (for example, at a library or office) because it prevents others from viewing your emails. To sign in: 1. Go to www.gmail.com. 2. Type your user name (your email address) and password, then click Next. To sign out: In the top-right corner of the page, locate the circle that has your first initial (if you’ve already selected an avatar image, it will show the image instead). To sign out, click the circle and select Sign out.
 
Signing in to your account When you first create your account, you will be automatically signed in. Most of the time, however, you’ll need to sign in to your account and sign out when you’re done with it. Signing out is especially important if you’re using a shared computer (for example, at a library or office) because it prevents others from viewing your emails. To sign in: 1. Go to www.gmail.com. 2. Type your user name (your email address) and password, then click Next. To sign out: In the top-right corner of the page, locate the circle that has your first initial (if you’ve already selected an avatar image, it will show the image instead). To sign out, click the circle and select Sign out.
Importing mail and contacts You may already have a contact list from another email address, and it would be a lot of work to re-enter all of this information manually. Gmail allows you to import your contacts from another email account, and you can even import all of your email messages from that account. Several email providers are supported, including Yahoo!, Hotmail, and AOL. To add other accounts: 1. Click the gear icon in the top-right corner of the page, then select Settings. 2. Go to Accounts and click Add a mail.
 
1.2	Scope
This document lists the OAuth 2.0 scopes that you might need to request to access Google APIs, depending on the level of access you need. Sensitive scopes require review by Google and have a sensitive indicator on the Google Cloud Platform (GCP) Console’s Oauth consent screen configuration page. Many scopes overlap, so it’s best to use a scope that isn’t sensitive. 
The G’ogle OAuth 2.0 endpoint suppor’s web server applications that use languages and frameworks such as PHP, Java, Python, Ruby, and ASP.NET.
The authorization sequence begins when your application redirects a browser to a Google URL; the URL includes query parameters that indicate the type of access being requested. Google handles the user authentication, session selection, and user consent. The result is an authorization code, which the application can exchange for an access token and a refresh token.
The application should store the refresh token for future use and use the access token to access a Google API. Once the access token expires, the application uses the refresh token to obtain a new one.
 













2.Software Requirement Specification Document
2.1 Functional Requirements
Functional Requirements provide details of how a product should behave and specify what is needed for development. Quality-of-Service Requirements detail what characteristics a product must maintain in order to maintain its effectiveness and any constraints.
Functional Requirement 1:
After entering URL user will directed to homepage
Input:  Url using keyboard.
Output: Shown to user.
Functional Requirement 2:
If server is busy or Maintainance period
Input: Url using keyboard.
Processing: Check network traffic on web.
Output: Display an error message.
Functional Requirement 3:
Ask user to login or signup in his/her account.
Input: Email id, Name, phone number and password.
Processing: Store all the information in database and send a confirmation code on contact number.
Output: Display a message that signed in successfully and redirect user to homepage.
Functional Requirement 4:
Creating a message
Input: Compose message.
Processing: System opens a prompt window to write a message.
Output: Display the command message send successfully.
Functional Requirement 5:
View all received messages.
Input: Click on Inbox.
Output: All categories of messages are displayed to the user.
Functional Requirement 6:
Important messages to view later
Input: Click on starred.
Processing: System will check in database for all the starred message.
Output: All the starred messages are displayed to user.
Functional Requirement 7:
History of send mails.
Input: Click on sent mail
Processing: System check in database about all the send messages.
Output: Displays list of all send messages.
Functional Requirement 8:
List of messages that were failed to send.
Input: click on drafts button.
Processing: System checks in database for all the message that were failed to send.
Output: Display list of unsent messages.
Functional Requirement 9:
Default “Reply All”.
Input: Default reply behaviour.
Process: Default behaviour added to database.
Output: Two behaviour added successfully.
Functional Requirement 10:
Change Id name.
Input: Click to change username.
Process: Search username in database.
Ouput: Display “change username”.
Functional Requirement 11:
Acknowledgement of Send mail.
Input: After clicking on send button.
Processing: System checks in database, they accept delivery report.
Output: Display receipt notification to the user.
Sending a Message
To send a message, click "Compose Mail" at the top left. Then type the receiver's address after "To." If you've added addresses to your contact list, you can type the first letter or two of the name for auto-complete, which lets you pick the name you want.
Click on "Add Cc" to add addresses for people whose responses are welcome but not required. Click on "Bcc" to add recipients whose names and addresses will be hidden.
Next, enter your topic after "Subject," and type your message in the large box. Using the symbols above the box, you can change the formatting, font and color of the text. You can also check spelling, add links and attach files. (You'll learn more about attachments later on this page.)
Gmail automatically saves your message in draft every few minutes while you're writing. When your message is complete, click "Send." A confirmation above the window will show your message was sent. If you don't want to save the draft message, delete it from the Draft folder.
Receiving a Message and Responding
Check the tally number next to your Inbox to see if you have new messages. Gmail checks for new messages every two minutes and updates the tally.
Gmail saves a "conversation" of each original message and all replies. When you open a message, the newest in the conversation is on top with the rest stacked below. To read all the messages in the conversation, click "Expand All."
To print a message, click the down arrow next to "Reply" and select "Print." To print the whole conversation, click "Print all."
To forward an individual message, open it and click "Forward" from below the message area. Enter recipients' addresses and add any notes to the message. Click "Send."
Using Attachments
With Gmail, attachments like documents, photos or video are easy to add and read. To attach a file to a message, click "Attach a file" under the Subject field. Find the file you want to attach, and click "Open." "Attach another file" lets you repeat the process. To remove an attached file, click "Remove."
To view an attachment, open the message, click "Download" at the message's bottom and then "Open" or "Save." To view an attachment without downloading, click "View as HTML" after you open the message. You also can open Microsoft Excel files as Google spreadsheets and Microsoft Word files as Google docs.
Message Archives
Archiving lets you move messages from the inbox to All Mail for storage. You can find information in these e-mails later by using the search tool. To archive a message, check the box next to the sender's name and click "Archive." If someone responds to a message you've archived, the whole conversation reappears in your inbox.
Gmail has plenty of features beyond the basics. Next, let's look at some of them, such as security filters, Gmail Notifier to announce new mail, and "retrieve and respond" to access messages from other e-mail services.
Gmail Features
Gmail features make e-mail easier and more convenient. Let's take a closer look at some like Gmail Notifier, which can alert you when you have a new message, and Mail Fetcher, which allows you to retrieve e-mail from other services, like Yahoo Mail or AOL.
Gmail Notifier
This downloadable application lets you know when you have new Gmail messages -- without opening your browser. The Notifier automatically checks for new messages every two minutes. With it, you can see a brief section of text from up to 30 messages and select a sound to indicate you have new mail.
Running Gmail Notifier requires Windows 2000, Windows XP or a newer version of Windows. Mac users need OS X 10.3.8 or later to run the Notifier, which can also alert them of upcoming events recorded on Google Calendar.
Mail Fetcher
This feature lets you fetch and download messages from up to five other e-mail accounts. Mail Fetcher will check all of the accounts regularly so that mail from them appears automatically in Gmail. Accounts that you want to access must be POP (Post Office Protocol) access enabled. POP allows users to download messages from Gmail's servers so e-mail can be accessed without an Internet connection.
Contact Groups
By creating a contact group, you can quickly send e-mails to everyone in the group. To create a group, click "Contacts" at the left and then "New Group" in the top left corner. Enter the name of the group and click "OK."
To fill the group with contacts, select the contacts you want in the Contacts list. Then open the Groups menu, and under "Add to . . .," select the group you want.
For later additions, enter the contact's name or e-mail address in the "Add this to group" box below the contact list.
To send a message to the group, go to the Compose window. After "To:" enter the first few letters of the contact group's name. Choose from the list that auto-complete suggests and write and send your message.
Security and Spam
Gmail is security conscious, starting with virus scans of every attachment you send. Every attachment you receive is scanned twice, when it's delivered and when you open the message. Questionable e-mails go directly into the spam folder. To remove spam from your inbox, select the unwanted message and click "Report Spam."
You also can send unwanted mail from specific addresses or domains directly to the trash by setting up a filter. Click "Create a filter" under the search box. Fill in fields with your criteria for the filter, and click "Next Step." Choose how you want the e-mails handled by checking a box such as "Delete it." Then click "Create Filter."
Parental Controls
Children under age 13 need parental permission to create a Gmail account. Parents also can use mail filters to block unwanted mail from reaching their children.
Gmail also recommends that parents:
•	Keep their child's computer in a public area of the house so they can monitor online activity.
•	Download parental control software or use browser settings that can block unwanted visits to inappropriate sites.
•	Discuss appropriate e-mail communication and behavior.
•	Advise children not to download attachments from unknown senders -- and to check with an adult if they're unsure.
•	Tell children not to give identifiable photos or information over e-mail or in chats, particularly to strangers.
Gmail continues to look at new ways to send and receive e-mail. Keep reading to learn how you can use Gmail for chat, instant messaging with AIM users, e-mailing from mobile devices and mail with voice.
Mail with Voice
If you're also signed into downloadable Google Talk while using Gmail's chat features, you can make and receive voice calls. A "Call" button will appear next to your contacts' profiles. Unless that button appears gray, the person is available to talk.
Your contacts also can leave you voice messages using Google Talk's voicemail. These will appear as special messages in your inbox. They have the subject "Voicemail from ContactName (x seconds)" and appear with a telephone icon. To hear voicemail, click "Play" in the conversation view.
Gmail Chat
Like Google Talk, Gmail allows you to chat with just one person or with a group. You can chat with anyone on your chat list who has a colored ball next to his or her name. Go to "Chat" and find and click on the name of the person you want. That will open a chat window, so enter your message and press "Enter."
You also can search for a contact by entering the name you want in the box at the top of Chat. Or you can search for the person you want from your Contacts list and then click the Chat link. When you're finished chatting, click the x in the top right corner of the chat window. Chat works with Internet Explorer 6.0+ or Firefox 1.0+ but not with Safari or other browsers. Chats are saved and can be searched.
Group chat lets you talk with an unlimited number of contacts at once. Here's how to set it up:
1.	Start a chat with one person in your Contacts list.
2.	Click "Options" at the bottom left of the chat window, and select "Group Chat."
3.	Enter the names of contacts you want to add in "Add a person to this chat."
4.	To end the chat, click the x in the corner of the chat window. The group chat continues until everyone has left.
Chat/IM with AIM Users
With Gmail chat, you can sign into your AIM account from Gmail to chat with AIM buddies. They're listed among your contacts, and you can search for them. To chat, you just click on a name on your chat list and type a message.
Gmail for Mobile
Gmail for mobile can be accessed through a smartphone's Web browser or from an application downloaded to the phone. To access by browser, point your phone's browser to Gmail. The interface makes it appear as if you're using Gmail on your computer.
Downloadable Gmail for mobile also keeps your actions in sync with your Gmail account, but it's faster and uses less data than the browser version. To try downloadable Gmail for mobile, point the phone's browser to Gmail applications.
Either version provides Gmail functions like search and conversation view. And both have automatic synching so anything you do in Gmail from your phone is also shown in your regular Gmail account.
•	Conversation View: Gmail allows you to see all incoming and outgoing emails, which you can verify by rechecking your previous emails for information. In the case that you cannot visualize this view you must enter:
•	General configuration.
•	Conversation View.
•	You enable or disable the option.
•	Undo send: You sent an email that you no longer want to do, so that you can undo the sending you have to act quickly, and you go to the left screen and click on undo.
•	Importance markers: Gmail allows you to select which emails you want to mark important and which ones are not. To do this function you must activate and enter:
•	Configuration.
•	
•	Importance markers.
•	Tags: They facilitate the management of large amounts of mail. You can do it in the following way:
•	Go to general settings.
•	Go to the Tags option.
•	Select the option you want.
•	Categories: Emails are organized automatically and can be added with notifications, forums, social or promotions. The way to access you have to enter "Tags" at the bottom.
•	Snooze: This option makes an email hide until the desired time, that is, it disappears in the inbox and we can reappear at the desired time.
•	Schedule shipping: If you need to send the mail that arrives when you need it, you can program it by simply pressing the arrow next to the send button.
•	Confidentiality.: Gmail gives you this option that makes your emails private, with just:
•	Check the expiration date option.
•	Dial access code.
•	Check the option that cannot be forwarded, copied or other.
•	Multiple Input Trays: Gmail with this function you can add up to five inbox panels directed to the main one. You can do them this way:
•	Go to advanced settings
•	The Multiple Inbox window will be mirrored.
•	You configure the ones you are going to add.
•	Replies predefined: You can create long emails and you can mark a answer if you have to always write the same answer. You can do it this way:
•	Go to advanced settings.
•	Click on Preset Answers.
•	Unread emails: enter the text label: unread in the search window.
•	Paste images: With this option you can drag images and other files to Gmail emails using Chrome.
•	Integrate Google Maps: with this you can include a map in the body of the message.
•	Google translator: Excellent opportunity that Gmail offers you to translate email messages.
•	Use Google Docs: Allows you to create documents with any email. Attached documents can also be converted into compatible documents.
•	Use Google Calendar: You can send "SMS" messages whose function is a reminder alarm.
•	Priority mail: You will be able to order your inbox and history of your emails, classify them and move them in the different trays, according to the need you have. You can also modify through the Gmail email settings.



2.2 Non-Functional Requirements
Availability:
The web server should be available for 24 hours
The web server should support every platform and could be opened on mobile phones, tablets, and PC
Reliability
The system should update and show the booking seats real-time
The system should be a one-way data flow that can be understood by just one look
Performance: 
The web application should be fast and respond to users within 1 second
The web application should have Hot Module Replacement (HMR) feature
Scalability:
The application should be easily implemented by other IT professionals for further uses no matter what platform it is
The database of the application should be able to deal with an enormous and increasing amount of data
Usability:
The web application should be a responsive web application
The web application must provide various languages to every user
Modifiability:
The web server should provide admin page for the administrator to modify and manage data
Convenience:
The web application should provide various ways of making a payment for the customers such as using PayPal or Mastercard
Security:
The web application should be https protocol

2.3 Logical Database Requirements
Website must able to store every kind of data means every format of data.Website should be frequently connectable to database or it must be database sensitive.











3.Model/Design
3.1 Use case Diagram
![Alt text](image.png)
 







3.2 Class and Object Diagram

 
 















3.3 Sequence and Collaboration 

  






 




 


3.4 Activity Diagram

 












3.5 State Chart Diagram


 






3.6 Component Diagram

 







3.7 Deployment Diagram

 


















4.Conclusion
With Gmail, your email is stored safely in the cloud. You can get to messages from any computer or device with a web browser. If your administrator allows, you can join or start a video meeting in Google Meet right from Gmail. Add Google Chat to your Gmail inbox and get all the features of Chat directly in Gmail. You can also quickly organize and find important email, as well as read and draft email without an internet connection.




















5.References
https://support.google.com/a/users/answer/9297685?hl=en
https://support.google.com/a/users?sjid=4216441372484093358-AP#topic=11499463
https://www.informit.com/articles/article.aspx?p=1312652&seqNum=7
https://github.com/alexandrakmet/UML-diagrams-Gmail/blob/master/Diagrams/State%20Machine/Sign%20in.jpg


## A Computer Aided Software Engineering Tools  Lab Project Report on GMAIL APPLICATION


### Submitted by                                                            
S.NITEESH BHARADWAJ    
P.VARSHITH 		       
A.SHIVA RAMA KRISHNA   
Y.M.KHASIM 		       
P.SAI KRISHNA           

### Under the Guidance of                                             
Dr. TALAKOTI MAMATHA, Associate Professor
Department of Computer Science & Engineering
### SREENIDHI INSTITUTE OF SCIENCE AND TECHNOLOGY (AUTONOMOUS)              
Yamnampet(V), Ghatkesar(M), Hyderabad–501301,Telangana.
2021-2025




### CONTENTS                                      
1	Introduction	                                                                                     
1.1	Purpose	                               
1.2	Scope	                                      
2	Software Requirement Specification Document	                                  
2.1	Functional Requirements	                               
2.2	Non-Functional Requirements	                             
2.3	Logical Database Requirements	                                 
3	Model/Design	                                
3.1	Use case Diagram	                             
3.2	Class and Object Diagram	                                   
3.3	Sequence and Collaboration 	                       
3.4	Activity Diagram	                               
3.5	State Chart Diagram	                                   
3.6	Component Diagram	                                      
3.7	Deployment Diagram                                           
4	Conclusion	                            
5	References	                                     
