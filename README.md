This is a demo app written in PHP to demonstrate how to read and
respond to USSD requests. This demo app requires PHP 5.2.0 or later.
Here is the expected workflow of the app:

Begin at STEP 1.

STEP 1:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Welcome to Afrinet Services.  
&nbsp;&nbsp;&nbsp;&nbsp;1. Vote 
&nbsp;&nbsp;&nbsp;&nbsp;2. Music  
&nbsp;&nbsp;&nbsp;&nbsp;3. Ticket pass 
&nbsp;&nbsp;&nbsp;&nbsp;4. Project 
If the user selects option 1, goto [STEP 2](#step-2)  
If the user selects option 2, goto [STEP 12](#step-12)  
If the user selects option 3, goto [STEP 19](#step-19)
If the user selects option 4, goto [STEP 26](#step-26) 
If the selection is none of the above, goto [STEP 11](#step-11)  



STEP 2:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Select to Vote a Player at NGN 100
&nbsp;&nbsp;&nbsp;&nbsp;1. Player1
&nbsp;&nbsp;&nbsp;&nbsp;2. Player2
&nbsp;&nbsp;&nbsp;&nbsp;3. Player3
&nbsp;&nbsp;&nbsp;&nbsp;4. Player4 
&nbsp;&nbsp;&nbsp;&nbsp;5. Player5
&nbsp;&nbsp;&nbsp;&nbsp;6. Player6
If the user selects option 1, goto [STEP 3](#step-3)  
If the user selects option 2, goto [STEP 4](#step-5)  
If the user selects option 3, goto [STEP 5](#step-5)
If the user selects option 4, goto [STEP 6](#step-6)
If the user selects option 5, goto [STEP 7](#step-7)
If the user selects option 6, goto [STEP 8](#step-8)
If the selection is none of the above, goto [STEP 11](#step-11)

STEP 3:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Player 1 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 4:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select player2  ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 5:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select player3 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 6:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select player4 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 7:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select player5 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)


STEP 8:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select player6 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 9:
-------
Display the following message and release the session:  
&nbsp;&nbsp;&nbsp;&nbsp;Thank you. Selection successful


STEP 10:
-------
Display the following message and release the session:  
&nbsp;&nbsp;&nbsp;&nbsp;Order cancelled.


STEP 11:
-------
Display the following message and release the session:  
&nbsp;&nbsp;&nbsp;&nbsp;Invalid selection.


STEP 12:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Select an Artist download at NGN100
&nbsp;&nbsp;&nbsp;&nbsp;1. Artist1
&nbsp;&nbsp;&nbsp;&nbsp;2. Artist2
&nbsp;&nbsp;&nbsp;&nbsp;3. Artist3
&nbsp;&nbsp;&nbsp;&nbsp;4. Artist4 
&nbsp;&nbsp;&nbsp;&nbsp;5. Artist5
&nbsp;&nbsp;&nbsp;&nbsp;6. Artist6
If the user selects option 1, goto [STEP 13](#step-13)  
If the user selects option 2, goto [STEP 14](#step-14)  
If the user selects option 3, goto [STEP 15](#step-15)
If the user selects option 4, goto [STEP 16](#step-16)
If the user selects option 5, goto [STEP 17](#step-17)
If the user selects option 6, goto [STEP 18](#step-18)
If the selection is none of the above, goto [STEP 11](#step-11)


STEP 13:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist1 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 14:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist2 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 15:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist3?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 16:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist4?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 17:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist5 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)


STEP 18:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Artist6 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No

If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 19:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Select an Event Ticket for NGN500
&nbsp;&nbsp;&nbsp;&nbsp;1. Event1
&nbsp;&nbsp;&nbsp;&nbsp;2. Event2
&nbsp;&nbsp;&nbsp;&nbsp;3. Event3
&nbsp;&nbsp;&nbsp;&nbsp;4. Event4 
&nbsp;&nbsp;&nbsp;&nbsp;5. Event5
&nbsp;&nbsp;&nbsp;&nbsp;6. Event6
If the user selects option 1, goto [STEP 20](#step-20)  
If the user selects option 2, goto [STEP 21](#step-21)  
If the user selects option 3, goto [STEP 22](#step-22)
If the user selects option 4, goto [STEP 23](#step-23)
If the user selects option 5, goto [STEP 24](#step-24)
If the user selects option 6, goto [STEP 25](#step-25)
If the selection is none of the above, goto [STEP 11](#step-11)


STEP 20:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event1 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 21:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event2 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 22:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event3 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 23:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event4 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 24:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event5 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)


STEP 25:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to select Event6 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No

If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 26:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Select a Project Contribution at NGN100
&nbsp;&nbsp;&nbsp;&nbsp;1. Project1
&nbsp;&nbsp;&nbsp;&nbsp;2. Project2
&nbsp;&nbsp;&nbsp;&nbsp;3. Project3
&nbsp;&nbsp;&nbsp;&nbsp;4. Project4 
&nbsp;&nbsp;&nbsp;&nbsp;5. Project5
&nbsp;&nbsp;&nbsp;&nbsp;6. Project6
If the user selects option 1, goto [STEP 27](#step-27)  
If the user selects option 2, goto [STEP 28](#step-28)  
If the user selects option 3, goto [STEP 29](#step-29)
If the user selects option 4, goto [STEP 30](#step-30)
If the user selects option 5, goto [STEP 31](#step-31)
If the user selects option 6, goto [STEP 32](#step-32)
If the selection is none of the above, goto [STEP 11](#step-11)


STEP 27:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to support Project1 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 28:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to Support Project2 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 29:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to Support Poject3 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 30:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to Support Project4 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  


STEP 31:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to Support Project5 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No
If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)


STEP 32:
-------
Display the following menu and wait for a response:  
&nbsp;&nbsp;&nbsp;&nbsp;Are you sure to Support Project6 ?
&nbsp;&nbsp;&nbsp;&nbsp;1. Yes
&nbsp;&nbsp;&nbsp;&nbsp;2. No

If the user selects option 1, goto [STEP 10](#step-10)  
If the user selects option 2, goto [STEP 13](#step-13)  

