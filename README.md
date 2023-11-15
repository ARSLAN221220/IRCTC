ASSIGNMENT

IntercityExpress Database

Group members
Set A: Aditya Kotasthane (23112018)
Set B: Avnee Jain (23112002)
Set C: Arslan Shaikh (23112034)

We have created the database named Intercity_Express by observing the given information. We've assumed that coaches can move independent of train. This assumption is further supported by the fact that each coach has a driver which takes it to different routes. We've also assumed  that for each scheduled journey, a specific driver and co-driver are assigned. We've established that entities and their attributes will be as follows:


1. TRAIN
   1.train_id
   2.train_name
   3.type
  4. mileage
  5. driver_id

2. COACH
   1.coach_id
   2.train_id
   3.capacity
   4.mileage
   5.last_maintenance_date
   6.due_for_maintenance_date
   7.driver_id
   8.co_driver_id

3. DRIVERS
   1.driver_id
   2.driver_name
   3.contact
   4.rest_day
   5.accommodation_required

4. ROUTES
   1.route_id
   2.source_station
   3.deination_station

5. SCHEDULE
   1.schedule_id
   2.train_id
   3.route_id
   4.departure_time
   5.arrival_time
   6.driver_name
   7.co_driver_name
   8.yearly_delay

6. STAFF
   staff_id
   staff_name
   contact
   role
   joining_date

7. STATIONS
   station_id
   station_name
   city

8. MAINTENANCE_SCHEDULE
   maintenance_id
   entity_id
   coach_id
   last_maintenance_date
   due_for_maintenance

9. BOOKINGS
   booking_id
   route_id
   booking_made_by

10. TICKETS
    ticket_id
    passenger_id
    schedule_id
    seat_number
    booking_status
    total_amount
    booking_date

11. TRAVEL_AGENT
    agent_id
    agent_name
    commission_rate

12. PASSENGER
    passenger_id
    passenger_name
    age
    total_trips
    discount_type


