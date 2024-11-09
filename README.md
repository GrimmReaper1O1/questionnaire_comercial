currently there are bugs in the system but a brief overview in video form is available on the link below...
https://youtu.be/Df8XZyq_r_I
Introduction:
The site is still incomplete in a mannor of ways but is functional enough to train people at this stage. No release will be 
made until it is up to scratch but with less work on your part you should be able to get it operational to your specifications.

Please be aware. There is no point in choosing previous versions as these versions are the stepping stones to get to the latest 
version. The latest version is the version with the highest level of functionality and is most bug free. Hopefully, when I release
the first release it will have no bugs at all.

This site utilizes jQuery for its Javascript and PHP. Be sure to download the questionnaire.sql file to fill your database with tables
although at this point foreign keys have not been established.

Questionnaire is an e-learning site which is under development. A release will be made at some stage but this repository
does not currently include a finished product. Questionnaire is meant to be but a framework to be completed by individuals 
who know the propper way to accomplish the development of a site in order to make it safe and fesible for others to work on.
The site was not developed with others working on it in mind. There are no comments and the code is not properly indented as
I do not require indented code. That said the first release will function properly and have as styling sytem that can alter
the style of the pages, but that is all. My only aim is to make the development of a site cheaper for those who could afford 
less than others, thus as a developer or development team you must keep this in mind.

Disclaimer:
Until the first release the site is not fully tested. Currently there are no releases for this site and the version numbers are 
simply so I can keep track of my work. There shouldn't be but may be vulnerabilities that I myself am unaware of;
however, I do my best to ensure the site is safe to utilize and is functioning properly, but I cannot state it will function 
adequately until a release is made.
Please be aware that the code is given freely as is based on the license agreement. Until the first release I will not accept any
payment for private schools usage, nor organizations, nor government institutions as the work is incomplete, but public schools and
not for profits e.g. charities and religious institutions may start work if they deem it required based on this current work.
As a developer, you take responsibility for that of which you promise and you take responsibility for that of which you create with 
this work. I will accept none in that regard as the code is handed over as is. Again it is meant to be a framework not a finished 
product, although the release should be good enough to use in a pinch on a local area network without much alteration when the time
comes. 
Be aware software comes with bugs that may be within this package and I myself may not be aware of them. In time I will create a means 
of contact whereby I can recieve information from others but now is not that time as I am busy trying to complete the project.
Please know, this is but a learning experience for me. I am not a trained developer other than text books and I must find ways and make
ways to achieve the results within. The code may not be the standard way of doing things. I expect the developer who chooses to use the
framework to read through it and decide as to whether he or she will benefit from using this framework. The results of your actions
are indeed your responsibility.




Warning!!!
This website is meant to be easy to configure in relation to users who may not know sql. There is a scheme document which
has text that needs to be copied into microsoft management studio or dbeaver and will set up the database.
The file will be better made upon completion of this project. The website configures itself with the username
administrator@questionnaire.com as the root administrator. This administrator has all access privilages and cannot be
deleted by the website itself; however, if deleted in the database any person who signs up can utilize this user 
as a way to get root access, hence forbiding the website to delete it.
Let it be known you should not delete the root administrator or super user administrator@quesitonnaire.com in the sql
editor; however, the username should be changed to a desired email, although, there are countermeasures to brute force
attack. A warning function on the first accessed page will however inform you of the need to create this user as soon 
as possible if it has been deleted in the sql database.
There should be no other means of accessing an administrative account.
I chose Microsoft SQL because Microsoft SQL server 2017 is cheap at the cost of around 300 for two cals. We want to do
things in a legal fashion.

The project is meant for schools and to be run on a local area network.

Now has loading bars for file uploads other than document uploads.

A counter measure for bruteforce attack has been added to the login system.

As I've realized in this day and age there may be no way to prevent data breaches I've decided the best way to prevent
the loss of any personal information is simply not to collect it. Other than the first middle and last name as well as
test scores, all identifying contact information has been removed from the system. There is no phone number collected nor
email, but administrators can still upload their phonenumber and utilize their email address so that they can be contacted.

Sadly this prevents the use of transactional email systems in order recover peoples passwords but functionallity has been 
added to the search for students page that allows the viewer administrators to automatically reset the passwords of the 
students via automatically generated passwords of a length of 8 characters. Administrators passwords may only be reset by 
the super user administrators. Viewers and the lesser administrators may not alter any other admin password.

There is now an sql file to install the database and get the system up and running rather easily. I apologize about the 
previous method. It was a means to an end but was an erronious way of doing things due to a lack of funding nor understanding
of opensource database management tools. Please be aware although the system is functional it still needs foreighn keys to delete 
things but placeholders are mostly functional.

The questionnaire is built to utilize a theory of memory, which allows for the cementation of memory via 
its usage to answer questions. Knowledge learnt from the subject page is thus utilized to answer a series of
quesitons based on such knowledge. 
The subject page is meant to consist of lengthy text and ment to overwhelm
the individual with information. Hints can be used to jog the memory of the student but should only be used to
initially mislead in order for the student to get the question wrong. Each individual quesiton set revolves. This 
is meant to be done on the first question. There should be at least four questions in each question set
based on information needed to solve each question. At the end of the quesiton set, information as a hint could 
be given which jogs the students memory in the right direction. 
There is an answer to every choice of quesiton and a reply to every choice of answer. These can be utilized to
remind the individual of both how they got something right and how they got something wrong. Information can be 
given to help them to get the answer correct but overall replys should not consist of all the information required 
to answer all the questions. Piece by piece you are meant to accumulate the information needed to answer the questions
correctly. This allows the student to read more informaiton and utilizes repetition in reading useful information in
order to learn and to learn the pitfalls of where people tend to get things wrong as well as cement the right information.
The question sets are to be answered correctly a number of times before the questions are labeled complete and you are
to move on to the next page, although you may choose to have as many questions on each page as the administrator likes. this
number of quesitons should be short enough to be motivational and allow you to move on, yet long enough for you to have 
trouble remembering the correct answer to previously asked questions on the next questionnaire pass.
The theory is that cementation allows you to draw your memory more quickly if it is utilized enough times to fully cement 
said memory; thus, you more quickly access memory in order to utilize it in any skill in formation including things 
like grammar, etc.

An example of question sets are as follows...

For childern
Which of these is a noun?
Talk.
reply
Incorrect.

Throw.
Reply
Incorrect.

Timothy.
Reply
Correct.

“”””””””
Time
Reply 
correct

Want
Reply
Not correct.

Obviously
Reply
Not correct

For childern
“””””
Universe.
Reply
Correct
Hint
Every thing is called and within…

Reply
Reply
Not correct

And
Reply
Not correct. And is a co-ordinating conjunction.

For teenagers and adults
Which of these is an adjective?

An
reply
Not correct. An is an article as is a and the. When utilizing articles you must consider whether the first letter of the object of the word is a vowel. If it is a vowel then an or the is used, otherwise a or the is used.

for 
Reply
Not correct. For is a co-ordinating conjunction. It requires a comma before it if there are two of them and they are not essential information. Note that the co-ordinating conjunctions are often omitted in the form of a list. I bought coffee, ice cream, cake, and pork.

Which
Reply 
Not correct. Which is a relative pronoun meaning it is a word that describes a noun or concept or points to something. Otherwise it is used in replacement of a noun in relation to something as are who, whom, whoever, whomever, and that.

Throw
Reply not correct. Throw is a verb it shows the action of an object or a state at any given moment. To throw the ball.

Strong 
Reply Correct. An adjective is a describing word. In such a case as the strong white male. Strong and white are both adjectives.
“””””””””””””””””””



For teenagers and adults
Which of these is correct in their usage of a semi column?

I went down to the shop, however, there was a unclean woman picking her nose at the delli; so, I didn’t bother going in.
Reply
Not correct

I was going to have a shower but didn’t; consequently, I stank for the duration of the trip.
Reply 
Correct! A semi-column is utilized to end a sentence with words like consequently which then start another complete sentence with a comma after the word in question.

I was going off the rails; so, I punched him in the face about a thousand times.
Reply
Not correct. So is not one of those words it is a co-ordinating conjunctions.

The taste of honey was in the drink; it was a bitter sweet remembrance of long days past when times were better and the world was full of milk and honey like a sweet memory of the past, all but forgotten to the rigours of time.
Reply
Not correct. Although a semi-column can be used between two short sentences in relation to each other, the second sentence was far too long. Try to keep the sentences short and about the same length.


“””””

Our history was all but forgotten to the rigours of war. All but a bitter sweet memory of time long past within our sphere of recollection and that of which we most focus on in this day and age. It is; however, a simple time. We do what we are told for advancement or we are shot as traitors. The spoils of war fall upon us due to our advancement.
Reply
Not correct. Although however is one of these words it is not in the correct placement and is not considered essential information. A comma should have been used.
Hint
However is one of the words to use with the semi-column.

I need you to buy; milk, poultry, sour dough bread, coffee, a banjo, beef jerky, chocolate, glasses, wine, outdoor furniture, a jukebox or another kind of stereo, music to play or a spotify subscription, a mobile phone, honey, cake, and about fifty other things. We need them for the party; it's is your sons by the way.
Reply
Correct! You utilize the semi-column at the start of a long list and in between two short sentences in relation to each other.
Hint 
A semi-colun is used after a complete sentence with a conjunctive adverb.

There are administrative functions and a library, which if within a class will limit the shown books to the class.
You can alter or fill out the questionnaire in the administrative functions, but a subject must be taken down.
There is also a way to quickly learn multiplication or at least utilize the times tables for cementation.
There are three levels of administrative users to primarily protect students confidential information.
One is like the administrative assistant who can fill out quesitonnaires only. Another can view the recorded test results and search for students given they know their email or name. The last is all access. There is also an area where books can be uploaded and a style system to update the style of the page.

As of version 6.7 the site is completely functional but is still incomplete and will take some time to refactor although the styling of the quesitonnaire isn't in place.
The quesitonnaire is however completely functional as is the functionallity to fill them. There are php prototypes which are completely functional as well.
The style system has been updated to Javascript and there is now a drop down menu in the most current version.
Learning Javascript is tedious at best at the moment but then I've been doing it for less than two weeks. The questionnaire needs refactoring at which stage 
it will have different styling based on the style config page. Thinking of separating the php pages to accomplish different aspects or incorporating some into themselves via javascript.


My apollogies, you will have to use the scheme document to fill the database and at this stage it may be erronious;
however, any web developer with sql skills can get it working quite easily. For the most part it's good to go in version 6.7.

The introduction to subjects page is configured for video, audio, and image or qpendix entries via the use of the administrative pages.

Please be aware the php interperater will need the php.ini file altered to accomodate for video files of your choice of size. I'm 
sticking to the size of 250 megabytes.

The style system isn't set up for the questionnaire as it requires refactoring and there is an error in the style configuration 
page which prevents the correct change in width for the introduction to subject page in relation to the bottom text box. Otherwise
there is much to be done to release a final version.

I hope this contribution makes an impact to the disadvantaged via helping in thier education as the license agreement stipulates any not for profit or public school,
or tertary education system may utilize this website for free, or at least at the cost of the software required as well as the computers to run it.
