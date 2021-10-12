# No-ShowAppointments
i will view some analysis for No-show appointments data

<a id='intro'></a>
## Introduction

### Dataset Description 

> i will go through the No-show appointments dataset , this data has information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. it has columns like :
>   - PatientId
>   - AppointmentID
>   - Gender
>   - ScheduledDay  : tells us on what day the patient set up their appointment.
>   - AppointmentDay :The day someone called or registered the appointment, this is before appointment of course.
>   - Age
>   - Neighbourhood  :  indicates the location of the hospital.
>   - Scholarship    :  indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
>   - Hipertension
>   - Diabetes
>   - Alcoholism
>   - Handcap
>   - SMS_received
>   - No-show        : the output
       - note : Be careful about the the output: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.
### Questions for Analysis
>  - What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
>   - which gender is more to  show
>   - what age is more to  attend
>   - is there a relation between the AppointmentDay and to  show
>   - is there a relation between ScheduledDay, AppointmentDay and not to show , may be the ScheduledDay is too far or too early?
>   - if sending a SMS has a relation with no to show

<a id='conclusions'></a>
## Conclusions

>- gender don't affect showing up because all the ratio are the same
>- from age 1 to 50 there is more chance to not attend the oppointment
>- but from 50 to 100 there is more chance to attend the oppointment
>- the average age for attend is 39 and for not attend is 35
>- there is no appointment at sunday
>- wednesday is the day with the most appointment
>- saturday is the day with the least appointment
>- 70 % of people who show  don't receive a msg and from people who not show 56 % did not recieve a msg so we can't tell if receiving a msg affect 
>- pepole with no scholarship tend to show for they appointment more than the people with scholarship
>- people with hipertension tend to show for they appointment
>- people with diabetes has more chance to attend they appointment


> ### Limitations
>- Age column has alot of wrong data like large number of 0 values and it doesn't make sense according to the project ,and  impute all these number of wrong data may lead to bais  
>- The data just has three months ( April, May, June)
>- The msg column was missleading as it says that the people how receive a msg were most to not show which does not make sense
>- Most of the variables are categorical, which doesn't allow for a high level of statistical method.
