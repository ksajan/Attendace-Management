# Attendace-Management
This project describes the methods by which we can reduce the number of proxies if utilised with Face recognition

### Task
> *Design an Attendance System for a class by scanning their face and ensure that no
student can put anyone’s proxy?*

### Solution

##### Assumptions
> We have limited computation resources
> 
> Using multiple access points( more than 3 ) to entry the attenbance data at different place will distract the students
> 
> The person entring the proxy for his friends doesn't have more than one laptop/desktop.


There are many ways to solve this problem. I will be discussing few of them which I think are ideal and can be used with the current system of using facial signatures to mark a student presence.

First we will discuss what we can do with only face recognition

1. **Time** : We can introduce an time limit in which they should be able to provide their attendace or at any random moment between class the face data will taken for attendace system. 
2. **Presence** : Introducing taking multiple face data at random time to reduce the number of proxies.


Now, Lets introduce some other barries to entry proxies

1. **Location Based** : Introducing location based crosscheck systems with facial data this can be achieverd using IP tracing linked with each stream of student.
2. **Biometric Authentication** : Using Iris recognition which are unique for each individual and immovabiltiy. We can use data of iris scanned with facial data and match the student database. Or using mobile fingerprint sensor as authenticator system to validate the student uniqueness this can be achieved through a validator app linked with student ERP and can be opened through scanning their fingerprint. 
3. **Code** : One of the popular method is to introduce a code scanning with such as QR code which are easier to do and attach and genrate random and uniwue code for every student joined with their student ERP system to validate and register student attendance.

The application design will look something like this if some of the above mentioned methods are used together:
![Attendace System Design](/images/Attendace_System.png)

I believe these methods implemented alongside with the current face detection + recognition system can introduce a higher barrier to entry a proxy for a student.

**Note**: _The above discussed/mentioned methods are not the only ways we can reduce the number of proxies online. And no solution will work 100% all the time. Each and every solution will introduce a higher barrier to entry a proxy. For better perforfance in this regard we can actually use bunch of the above mentioned method together which can significantly reduce the proxies entered in the attendance system._ 
