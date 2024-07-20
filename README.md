1.	We are going to have a random list of passengers that has to be transport from their homes and has to be transport to their workplace or vice versa. 
List fields:
-	Passenger name.
-	Origin address.
-	Destination Address.
-	Arrival time (users to be transport from home to work).
-	Departure time (users to be transport from work to home).
2.	For users that has to be transport from home to work, we are going to have a specific hour in which this users has to be at the work location. The app has to warranty no more than +5 minutes between this hour and the real hour when the users arrive to the company. Ideally the users has to arrive to destination 10 minutes before the hour given. 
3.	For users that need to be transport from the work to home, we are going to have a specific hour to start the route. 
4.	We are going to have a limit number of cars and buses with a max number of passengers that can be transport in this vehicles. 

a.	For the users that has to be transport from home to work: 
i.	The app has to generate an efficient route in order to warranty that the first user to be picked up, hast the latest hour possible.
ii.	The app has to manage in an efficient way the kilometers that a bus or multiple buses are going to travel, less kilometers better. 
iii.	The app has to generate an hour of pickup for the users and send this through WhatsApp.
iv.	The app also has to generate a complete list of the corresponding route, bus identification and the hours named in last point, in order to send to administrative person.
v.	Assume cars has GPS, design a front end view so users can see where their bus is. (Like Uber), If there is going to be a delay of 5 minutes  between the pick-up time that was assigned to the user and the real time, the app has to generate a WhatsApp message in order to inform the user and if applicable to next users about this. 
vi.	If there is going to be a delay between the Arrival time and the real time of 5, the app has to generate a mail for send to supervisor. 
vii.	After the travel concluded the app has to generate a pdf file and send for email, where you can find the real hour and date that passengers were picked-up, where they were picked-up, and the arrival time in final destination.
b.	For the users that has to be transport from home to work
i.	If the bus it is not going to be on time, the app should generate a WhatsApp message to inform users about the delay and give a new pick-up time.
ii.	After the travel concluded the app has to generate a pdf file where you can find the hour and date that passengers were dropped off at their respective homes, where they were dropped off.
The app has to manage 3 types of users: 
1.	Operators users that can: 
•	Add a new bus with the next information: 
o	TBD
•	Add new passengers with the next information: 
o	TBD
•	Change the pick-up time of a passenger or cancel it.
•	Cancel a bus travel. 
•	Change arrival time or departure time. 
2.	Passengers
•	See their pickup time. 
3.	Administrative users that can:
•	Change bus information.
•	Change passenger information.
•	Delete a bus.
•	Delete a passenger. 
4.	Super User that can: 
•	Add operator or administrative user and delete them.

*TBD=To Be Define

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
