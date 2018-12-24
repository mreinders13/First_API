GET REQUESTS: 
 - Get All Students: http://localhost:50157/api/students/index
 - Get specific Student: http://localhost:50157/api/students/6

POST REQUESTS: 
 - Add a Student(Ekedahl): 
   POST: http://localhost:50157/api/students/create
    JSON: {"lastName": "Ekedahl", "firstName": "Michael", "GPA": "4.0", 
	   "graduationDate": "2018-12-08T13:00:00.00", "Active": "True"}

PUT REQUESTS:  
 - Change student(Ekedahl): ***Wherever you see {id}, please replace with the studentID of the student you wish to edit
   PUT: http://localhost:50157/api/students/edit/{id}
    JSON: {"studentID": {id}, "lastName": "Ekedahlzz", "firstName": "Michael", "GPA": "3.99", 
	   "graduationDate": "2018-12-07T13:00:00.00", "Active": "True"}

DELETE REQUESTS: 
 - Delete student(Ekedahl):
   DELETE: http://localhost:50157/api/students/delete/{id}