# hotel-system
Java Spring Project for Practicing Different Concepts. The Northwind of Spring Apps.

# Entities
* HotelProperty
* InteriorSpace
  * HotelRoom
  * Restaurant
  * MeetingRoom
  * PublicArea
* Person
  * Guest
  * Employee
    * Receptionist
    * Concierge
    * Maid
    * Manager
    * Chef
    * Waitress
    
***Concierge might end up being a *service* as opposed to an object. Possible opportunity for Machine Learning**
# Use Cases (more may be added later)
1. An unauthenticated website visitor needs to be able to browse **hotel room** availability.
2. An unauthenticated website visitor needs to be able to create an account.
2. An unauthenticated website visitor needs to be able to log in.
3. An authenticated website visitor (**Guest**) needs to be able to book a **hotel room**.
4. A Guest should be able to review their current **booking**.
5. A Guest should be able to update existing booking up until check-in date.  
6. The system should send a guest confirmation of new bookings, as well as updated bookings.
7. A guest should be able to request recommendations from the **concierge**.
8. A receptionist should be able to create a booking on behalf of a guest
9. A receptionist should be able to update a booking on behalf of a guest
10. A receptionist should be able to retrieve a booking given a guest's name and check-in date
11. An Employee should be able to view their work schedule

#Technologies to Be Used
* [https://developer.okta.com/ **Okta** for authentication]
* Spring Boot for Backend
* MySQL for DB (possibly Mongo in places where Objects do not have a lot of relationships to other Objects)
* [https://spring.io/guides/tutorials/react-and-spring-data-rest/ ReactJS for Website]
* React-Native for mobile app (eventually)
