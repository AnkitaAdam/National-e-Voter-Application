NATIONAL e-VOTER SERVICE SYSTEM

Problem Statement :

The present voting  system applicable  in the electoral system has   proved inefficient as   the voters’ registration process is slow, the manual collation of results takes time and gives room for result manipulation, also the inaccessible nature of election venues  which includes the long distances to be covered by voters’ to their registered location increases voters’ apathy towards the election processes, and  finally  the   issues   of   ballot  box   snatching  and   damage   and   other  election  violence   and  issues associated with the traditional ballot paper Voting all defiles the purpose of voting in election process as a formal process of expressing individual opinions for or against some motion.
In democratic countries, voting is a vital tool to collect and re-act people’s views. In the elections, the election of member of the assembly, the head of local/state government election, and others, a voter can cast vote after going to the designated polling place and checking his identity. Conventionally, voting booth is used for casting votes in both centralized and distributed places. Voting is done under the supervision of authorized parties. Counting of votes is done manually once the election is over. But with the rapid growth of electronic voting system, computer technology and cryptographic methods can be used that substitute the occurrence and most significantly error-prone human Component. To increase the productivity and accuracy of voting processes, electronic voting systems were developed to help accumulating and counting the votes.
We also propose a process that guarantees the confidentiality of voter and the secrecy of vote content. By our electronic voting system, a voter can cast his vote more easily and conveniently than the existing electronic voting using internet, within the planned time period anywhere even when a voter is not able to access internet on a voting day. Our suggestion can be used in all kinds of elections national as well as state/local elections. 




How online system overcomes drawbacks of offline voting’s :

-	Reduced costs: 
Instead of having thousands of polling stations scattered all over the country which will involve enormous logistics to is deployed deploy, the only 'polling stations' will be one counting center per service provider where the election polling software system, this makes it easier to monitor. 
-	Increased participation and voting options: 
People can vote from home or offices so no need of public holiday to enable people vote. Participation will be higher because people do not have to leave their home and stand on long endless queues. Participation will generally be higher than ever before. Many people do not vote just because of the stress involved. 
-	Reduced Risk: 
The risks associated with road travel such as road traffic accidents and late arrival of electoral resources due to unforeseen delays during deployment of polling stations will be avoided. 
-	Reduced time Consumption: 
Due to its electronic nature, the results of the Poling will be available immediately after voting with the GSM SMS voting. 
-	Greater speed and accuracy placing and tallying votes: 
Have a grate speed as compared to offline voting while publishing the results as well as while casting the votes
-	Provide Equal Opportunity: 
Best of all, this process will guarantee that a new generation of political leaders will emerge at last. Since, it will provide an equal opportunity for all the political parties.







Functionalities Provided : 

Following are the Functionalities that are to be provided are :
-	Eligibility : 
Only persons who meet certain pre-determined criteria are allowed to cast permitted number of votes. To achieve this, authority needs to verify the eligibility of voters and record their casted votes. 


-	Privacy : 
No one except users can know their votes. To achieve this, any traceability between voters and their votes must be removed during the whole election. 

-	Accuracy : 
In elections, voters expect that their votes are correctly captured and that all eligible votes are correctly tallied. Accuracy is degree of satisfactions of voters’ this expectation, and can be maintained by the verifiability 
mentioned below. 

-	Verifiability : 
Verifiability is the ability to determine whether only and all valid votes are counted in final tally or not. Accuracy of the election can be verified in two ways, one is the individual verifiability where only voters can verify their own votes in the tally. Therefore accuracy of the election consists of n voters is ensured when there are less than or equal to n votes and all and voters verify their votes. The other is universal verifiability which enables any third party to verify the accuracy of the election. 

-	Fairness : 
In order to conduct the impartial election, anyone should not be able to compute the partial tally before the end of the election which may influence the remaining voters and may affect the voting result. 

-	Receipt-freeness : 
Receipt-freeness disables anyone including voters themselves to link voters to their votes, in order to protect voters from being coerced to follow intentions.








Function-01: Home page 
-	Hyperlink to Login separation page
-	Hyperlink to registration separation page

Function-02: Login Separation page
-	Display three options as – Voter, party & admin login
-	Hyperlink to the Voter login form
-	Hyperlink to the Political party’s login form
-	Hyperlink to the Admin login form

Function – 03: Registration separation page
-	Display two options as – Voter, party registration
-	Hyperlink to the Voter Registration form
-	Hyperlink to the Political party’s Registration form

Function – 04: Voter Registration form
-	Input all the details from voter such as full name, phone no, aadhar no, address, age, dob, email, password etc. 
-	Validate all the details filled by voter
-	Store the details into database
-	Generate voter card and send to voter’s mail which contains the voter id

Function – 05: Voter  Login form
-	Input all the required fields from voter (Voter id and password)
-	Match the username password entered with records available in database
-	Redirect to voter’s module if login successful
-	Otherwise show error message
Function – 06: Political party’s registration form
-	Input all the required fields from party such as party name, party symbols (only one if existing party or 3 if registering as a new party)
-	Validate if the fields are filled 
-	Store the data into database
-	Send the party creation request to admin module for authentication
-	Do not give access to any dashboard feature unless admin accepts the request.
Function – 07: Political Party’s login form
-	Input party name and password
-	Validate the details entered
-	Check if the details match with records in database
-	If matched then show political party’s dashboard
-	Otherwise give error message

Function – 08: admin Login
-	Input the admin username and password
-	Validate the fields
-	Match the username and password of admin from database
-	If data matches then allow to enter into the admin dashboard

Function – 09: Voter’s dashboard
-	Show below features to voters:
1.	My Profile
2.	Steps to vote
3.	What’s on the ballot
4.	Voter area
5.	View voter card
-	Hyperlink to all the above listed features

Function – 10: My Profile page
-	Fetch all the voter’s details from database records
-	Show them in a proper format to voter

Function – 11: Steps to vote
-	Show the steps to vote using e-voter application 
-	Include some information about Indian democracy and constitution
Function – 12: What’s on the ballot
-	The page should display all the nominated candidates for elections 
-	Only the authenticate candidates should be visible to voter
-	The page should dynamically change the content according to candidate nominations approval.
Function – 13: Voter area
-	This feature should be accessible only if the current election phase selected by admin is ‘Start voting’
-	The page should first authenticate user by asking him to enter the correct otp sent to the phone number
-	If OTP entered is correct and that too within given time limit, then do face detection of the voter
-	If both process are successful then Allow voter to enter into the actual voting booth where all the nominated candidates, their party names, party symbols would be shown to user with a cast vote button
-	Once user clicks the cast vote button, his vote will be granted and added into the node of blockchain
-	Don’t allow user to recast the vote 
-	Expire the session automatically by giving a message as ‘ Vote casted successfully’ and shown the dashboard to voter

Function – 14: View voter card
-	Here as well, first do verification by OTP  and face detection
-	If successful then allow to view and download the voter card 
-	Otherwise show error and redirect to dashboard

Function – 15: Political Party’s dashboard
-	Show below features to political party
1.	My Party
2.	Nominate a candidate
3.	View election results
-	Allow parties to access the above listed features only if their party creation request is approved by admin
-	Hyperlink all above pages with dashboard

Function – 16: My Party page
-	Fetch all the party’s details from database records
-	Show them in a proper format to voter



Function – 17: Nominate a candidate page
-	This feature should accessible only when the phase selected by admin is ‘Candidate Nominations’
-	The parties should be notified when it’s time to nominate their candidates
-	Input all the required candidate nomination details from party
-	Validate all the fields are entered
-	Store them into database
-	Send the nomination request to admin 
-	Notify parties when admin approves the request or rejects the request of nomination

Function – 18: View election results
-	This feature should be accessible only when the phase of election is selected to ‘Publish election results’ 
-	This page should display the results in graphical format 
-	In the form of graphs dynamically changing results should be shown
-	Parties should be notified when results are out

Function – 19: Admin dashboard
-	Show below features to political party
1.	Set election title
2.	Set election phase
3.	Party creation requests
4.	Candidate nomination requests
5.	Approved candidates for election
6.	Publish election results
-	Hyperlink all above pages with dashboard

Function – 20: Set election title:
-	This feature should allow election commissioner to set a title for the upcoming elections
-	After setting the title, the voter and party modules will get notified as the elections are going to be held for the respective title when election phase is selected to ‘start election’


Function – 21: set election phase
-	Here, admin can actually select or handle all the election duties systematically
-	Admin will have following list of choices:
1.	Start election
2.	Nominate candidates
3.	Start voting
4.	End voting
5.	Close elections
-	The above phases can be selected in sequential order only
-	Admin can’t select any random phase
-	And the respective module will be notified when related phase is currently running, for example – party module and voter module will be notified after selecting the ‘Start election’ phase
-	When election phase is set to ‘Close elections’ then all the current election related data will be flushed out from respective pages unless next election is started.
-	But the previous election data will always be available in the database records

Function – 22: Party creation requests
-	Here, admin can view all the party creation requests sent while creating their account on the website
-	Admin can accept or reject their requests by viewing all their filled details

Function – 23: Candidate nomination requests
-	In this feature, all the nominated candidates requests will be shown
-	By seeing which, admin can accept or reject their requests
-	The parties will be notified if their candidate is eligible or not depending on accept or reject of admin

Function – 24: Approved candidates for elections
-	In this page, the approved candidates list will be shown to admin
-	The same list will be shown to voters in the ‘What’s on the ballot’ page 
Function – 25: Publish election results
-	when election phase is set to ‘Publish results’, the results will be shown here first, and then when admin clicks on the publish button results will get displayed on remaining other modules


