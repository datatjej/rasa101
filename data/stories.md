## time path
* greet
  - utter_greet
  - utter_wh_person

## inform
* inform_person{"person":"Vlad Maraev"}
  - utter_wh_date

## book whole day
* inform_day{"date":"13/03/2020"}
  - utter_whole_day
* affirm
  - utter_yn_person_date

## book specific time
* inform_day{"date":"13/03/2020"}
  - utter_whole_day
* deny
  - utter_wh_time
* inform_time{"time":"3 pm"}
  - utter_yn_person_date_time
  
## affirm time-specific appointment
  - utter_yn_person_date_time
* affirm
  - utter_appointment_created

## deny time-specific appointment
  - utter_yn_person_date_time
* deny
  - utter_wh_person

## affirm whole-day appointment
  - utter_yn_person_date
* affirm
  - utter_appointment_created

## deny whole_day appointment
  - utter_yn_person_date
* deny 
  - utter_wh_person
 
