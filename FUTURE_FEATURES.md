
# how-do-you-do


## Future features I would add.


- [General](#general)
- [Payments for the teachers](#payments-for-the-teachers)
- [Student](#student)
- [Teacher](#teacher)
- [Admin](#admin)


## General

- Translate website to more languages

    -   Using PHP or Python store translations in language file ( Json ) on server side
    -   Keep strings in views in variables
    -   Every time browser requests page, we will serve same
        page with different translation only, instead of hardcoding every language into
        HTML page, and rewriting same page over and over for every translation
    -   Saves us lots of time and headaches.... with any future updates   
 
-   Start accepting payments using Stripe

-   Create partial views for navigation, headers, footers....

-   Create components for form elements, buttons, avatars, testimonials ...

-   Using Javascript ( jQuery )

## Payments for the teachers

### Figure out the payments for the teachers

#### IDEA :

1.  Once student has completed session, he will have to confirm it as completed before he can book another
    session, by clicking on completed button.

2.  Same goes for the teacher, once he completed session with the student, he will have to 
    confirm it by clicking on completed button.

3.  Once the session is confirmed as completed by both parties, we will consider session as 
    completed.

4.  Once a week or once a month, a cron job would run and collect all data about teachers and
    their completed sessions, and would transfer the funds to their accounts using Stripe.

5. Or something better... 
    
## Student


####  Using jQuery to make AJAX calls to server with necessary data and load response into div that will hold the info requested.
 

-   Ability to click on any module to preview sessions in that module

-   Ability to book future session with current teacher and add option of booking session
    with  :
    
    -   different teacher from same country / timezone
    -   different teacher from different country / timezone

    so that student can experience different styles of conversations , accents...

    Time difference will have to be taken into consideration, so we'll have to check 
    currently logged in user's timezone and check it against selected teacher's timezone
    and recalculate availability.

-   Ability to mark study session as completed.

-   Ability to save notes about the study session to database.

-   Ability to view, edit, delete notes.

-   Ability to contact support when needed

## Teacher 

####  Using jQuery to make AJAX calls to server with necessary data and load response into div that will hold the info requested.
        

-   Ability to click on any student that he is currently teaching
    and check current progress of that student, and maybe previous teachers as well...  
    
-   Ability to mark study session as completed.
    
-   Ability to see booking calendar.

-   Ability to block off some days in calendar.

-   Ability to save notes about the study session to database.

-   Ability to view, edit, delete notes.

-   Ability to check payment for sessions tought.

-   Ability to contact support when needed

## Admin 

-   Create Admin user :
    -   To deal with any issues that will occur.
    -   To provide support for students and teachers.
    -   To manage payments for teachers.    