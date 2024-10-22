To start your mongo shell type the following command  :

mongosh



To create or switch to Database type  :

use Codetribe



To create a collection or collections  :

db.createCollection("Facilitators"),
db.createCollection("Trainees"),
db.createCollection("Projects")



To insert data into collection type the following  :

db.Facilitators.insertOne({name: "KB", location: "Kimberley", course: "Fullstack Development"}),

db.Trainees.insertOne({name: "Lebogang Mylas", location: "Kimberley", facilitator: "KB"}),

db.Projects.insertOne({name: "First MongoDB Project", course: "Fullstack Development", lesson: "MongoDB"}),