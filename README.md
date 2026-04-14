# Ticketing-System-Lab
This repository documents a ticketing system lab that I created. Using Spiceworks, I create tickets for issues that have appeared within my Active Directory homelab. These are then resolved and closed after confirming with the user. 

## Ticket One - User can't log into computer

![Locked out](images/Locked-out.png)

#### 1. Account lockout on client machine of COMPUTER03 for user Harry Potter.

![Ticket for locked out](images/Ticket-Locked-Out.png)

#### 2. User 'Harry Potter' creates a ticket detailing the issue 
 - Describes device affected, details of the screen, where he can be found
 - Priority is HIgh because he cannot complete any tasks
 - Category 'Other' because 'account issues' not listed

    
![Event viewer](images/Confirm-Event-Viewer.png)


#### 3. Confirmed on Windows Server in Event Viewer that there is an account lockout on COMPUTER03 by ‘harrypotter’.
- Event viewer > windows logs > security
- Selected ‘Filter Current Log’ for code 4740

![Unlock account](images/Unlock-account.png)

#### 4. Unlocked account in 'Active Directory Users and Computers' and provided temporary password of ‘TestPassword#’

![Closing ticket](images/Closing-ticket.png)

#### 5. Closed ticket after confirming with Harry Potter that everything is working well.
 - Later conducted a post-resolution follow-up.


       
      

