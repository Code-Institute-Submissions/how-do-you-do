<a href="https://marcelkolarcik.github.io/how-do-you-do/">
<img src="https://raw.githubusercontent.com/marcelkolarcik/how-do-you-do/master/assets/screenshots/heroimage.gif" title="https://marcelkolarcik.github.io/how-do-you-do/" alt="https://marcelkolarcik.github.io/how-do-you-do/"></a>



# how-do-you-do 
 A website that will help you to find more job opportunities, become better educated, easily travel anywhere in the world,
 know the global language, improve confidence and date more people ... :wink: ...
 by  teaching you  English online.
 


## Table of Contents

- [Inspiration](#inspiration)
- [Technologies](#technologies)
- [User Experience](#user-experience)
- [User story](#user-story)
	- [Potential Student](#potential-student)
	- [Student](#student)
	- [Potential Teacher](#potential-teacher)
	- [Teacher](#teacher)
- [Testing](#testing)
- [Deployment](#deployment)
- [Acknowledgements](#acknowledgements)
- [Future Features](#future-features)


## Inspiration 

I was inspired to create this project after conversation with my wife, when she said,
that she would like to become teacher of English online. So I thought, that it would be nice,
if she had online presence, where she could fulfill her dream.

As well as fulfilling dreams of others to learn or teach English online.

## Technologies

* HTML
* CSS
* Twitter's Bootstrap
* Font Awesome
* Adobe Illustrator ( hero image, avatars and screenshots editing )
	

## User Experience

> #### Wireframes 

I used pencil and paper to wireframe design ...
They can be found at 
[Wireframes](WIREFRAMES.md)

</a>

>   #### Colors

![Teacher Dashboard](https://raw.githubusercontent.com/marcelkolarcik/how-do-you-do/master/assets/screenshots/color_scheme.png)



I extracted colors for the website from the hero image, and created few classes to easily
apply color styles as needed. I chose these colors as they are not intrusive and are easy to look at.
And they are associated with trust, reliability, security ( blue ). Fun ( orange ). New beginnings and growth ( green ).
These are the emotions I would like my users to feel when they arrive at landing page.

```css
.white {
	color: #fdf1ed;
	}

.bg_green {
	background-color: #0fbeba;
	}

.border_green {
	border: 1px solid #0fbeba;
	}

.bg_blue {
	background-color: #0076ba;
	}

.blue {
	color: #0076ba;
	}

.border_blue {
	border: 1px solid #0076ba;
	}

.bg_orange {
	background-color: #fc8b09;
	}
```

>  #### Translations

##### Translated pages

As students that are looking for online school of English probably don't speak
English yet, I have translated  landing.html, login.html and student_signup.html and some of the testimonials into 2 different languages ( more to come ), together
with the page titles, so that search engines can index those pages in different languages, so that if Spanish or Chinese   ( more to come )
future student is looking for online English school in his native language, our website would come up in search results in his particular language
 as well . 
 
 
##### Not translated
 
 I have not translated signup.html ( teacher sign up), teacher_signup_succesful.html, teacher_dashboard.html,student_dashboard.html
 as I felt that teachers would speak English already. As well as student dashboard, as students
 are learning English and it would be first opportunity to to discover meanings of the words they don't know yet.
 
## User story


 ### Potential Student 


As potential student who wants to study English online, 
I want to see pricing and structure of the courses, so that I can choose one that is right for me.
I want to find easily on any device.

As I land on landing page of how-do-you-do.com I have option of viewing the website in other languages, by clicking on the language name 
in the right top corner.If I was visiting on mobile device, I would see country flags instead.

Right on the top of the page I see hero image with animated text saying : "There are many reasons for learning English. Only you know yours." 
which is changing it's translation to different languages, which I find cool and interesting.

Right under hero image I see Start Learning Now! button, which could be clicked.

I would scroll down to read about the benefits of learning English
and then under benefits section I would see button Start Learning Now! again. 

And as I would scroll down even more I would see testimonials from 
previous students, which convinced me that it's good place to learn English online.
And I would click on the Start Learning Now!, which is situated under testimonials section as well.
 
As I would click on the button I would see form with prices and structure.
I would choose study plan that is right for me, fill in my details and pay the course fee to become student.

&ensp;

 ###  Student 

 
 As a student I want to be able to :
  
 -  log in into my dashboard to book study session with teacher.
 -  see my teacher's Skype user name, so I can connect with him.
 -  download study material to my device, so that I can practice what I've learnt.
 -  write and save notes about session.
 -  see all my previous notes and be able to read, edit, delete them.
 -  access to support, when I need it.
 -  rate / review my teacher(s).
 -  logout of my dashboard.
 
 &ensp;
 

 ### Potential Teacher
 

As potential teacher who wants to teach English online, 
I want to know terms and conditions of the company I would teach in.
I want to find this information easily on any device.

As I land on landing page of how-do-you-do.com I have option of viewing the website in other languages, by clicking on the language name 
in the right top corner.If I was visiting on mobile device, I would see country flags instead.

Right on the top of the page I see hero image with animated text saying : "There are many reasons for learning English. Only you know yours." 
which is changing it's translation to different languages, which I find cool and interesting.

On the navigation bar, in the right hand corner, I would see word Teacher? or translated version of it, If I was visiting
on mobile device, I would see graduation cap icon with question mark next to it. That makes me click it.

As I would hover over this word, a title of the element would appear asking me 
"Would you like to become one of our teachers?"

As I would like that very much, I would click on it.
Then I would see sign up form. 
I would fill in my details.

As I click on Sign up! button,
I see acknowledgement of my request.

I would be asked to check my email for further instructions.

&ensp;
  ### Teacher


As teacher I want to be able to:
 
-   log in into my dashboard to check my bookings.
-   check on progress of my students.
 -  see my student's Skype user name, so I can recognize them.
-   write and save notes about session.
-   see all my previous notes and be able to read, edit, delete them.
-   access to support, when I need it.
-   block some of the days, when I am not available for teaching.
-   logout of my dashboard.

 &ensp;
## Testing

 I recommend using one of these modern browsers : Google Chrome, Mozilla Firefox or Opera.

 Internet Explorer is not displaying animation of the hero image. ( i am currently investigating this behavior )
 
 Apple Safari responds with Error:  Can't Establish a Secure Connection to the Server github.com .
 
I tested my website on 5in and 6in phones, 10in tablet 18in laptop and 22in desktop with good response from
all of the devices.

Please see step by step testing on desktop and mobile devices here :

[Testing](TESTING.md)

## Deployment 

I deployed how-do-you-do site by going to my github repository and then clicking on setting button,
scrolling down until I reached Github Pages section and then selecting master branch as source.

As the website is deployed in Github, it allows me to test it on more devices.
And as it is versioned, it allows me to see latest updates straight away.






## Acknowledgements

[Acknowledgements](ACKNOWLEDGEMENTS.md)





## Future Features

[Future Features](FUTURE_FEATURES.md)
