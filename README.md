# nodeSite_Pinar
I created ajaxTry.html file. Than I created GET, POST, DELETE, and PUT buttons. 
I add function to see JSON object array as a table.
Then I wrote methods for each button.  
GET method calls "Actor Name", "Oscar Year", "Movie Name", and "ID" from Users JSON file.
I used $.getJSON method. 
It responds like that;

{
  "celeb1": {
    "name": "Javier Bardem",
    "oscarYear": "2008",
    "oscarMovie": "No Country for Old Man",
    "id": 100
  },
  "celeb2": {
    "name": "Frances McDormand",
    "oscarYear": "2018",
    "oscarMovie": "Three Billboards Outside Ebbing Missouri",
    "id": 101
  },
  "celeb3": {
    "name": "Emma Stone",
    "oscarYear": "2017",
    "oscarMovie": "La La Land",
    "id": 102
  }
}
Actor Name	Oscar Year	Movie Name	ID
Javier Bardem	2008	No Country for Old Man	100
Frances McDormand	2018	Three Billboards Outside Ebbing Missouri	101
Emma Stone	2017	La La Land	102

POST method calls agencies from giving URL and it responds like;

{
  "agencies": [],
  "sub_agencies": [
    {
      "subtier_agency_name": "Administration"
    },
    {
      "subtier_agency_name": "Agricultural Marketing Service"
    },
    {
      "subtier_agency_name": "Agricultural Research Service"
    },
    {
      "subtier_agency_name": "Animal and Plant Health Inspection Service"
    },
    {
      "subtier_agency_name": "Assistant Secretary for Departmental Management"
    },
    {
      "subtier_agency_name": "Board of Contract Appeals"
    },
    {
      "subtier_agency_name": "Department of Agriculture"
    },
    
   DELETE method deletes by Id number. I set the Id =102.
   When I click the DELETE button console responds "Delete user 102".
   
   PUT method calls "Actor Name", "Oscar Year", "Movie Name", and "ID" from Users JSON file.
I used $.getJSON method. 
It responds like that;

{
  "celeb1": {
    "name": "Javier Bardem",
    "oscarYear": "2008",
    "oscarMovie": "No Country for Old Man",
    "id": 100
  },
  "celeb2": {
    "name": "Frances McDormand",
    "oscarYear": "2018",
    "oscarMovie": "Three Billboards Outside Ebbing Missouri",
    "id": 101
  },
  "celeb3": {
    "name": "Emma Stone",
    "oscarYear": "2017",
    "oscarMovie": "La La Land",
    "id": 102
  }
}
Actor Name	Oscar Year	Movie Name	ID
Javier Bardem	2008	No Country for Old Man	100
Frances McDormand	2018	Three Billboards Outside Ebbing Missouri	101
Emma Stone	2017	La La Land	102

QUESTION:

Actually I tried to change POST API from https://api.usaspending.gov/docs/endpoints website; however, I haven't been successful.
I used the URL into the appropriate methods, and I used giving request example, but it didn't work at all.
I don't understand why it doesn't work.
