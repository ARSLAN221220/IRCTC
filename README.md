ASSIGNMENT

IntercityExpress Database

Group members
Set A: Aditya Kotasthane (23112018)
Set B: Avnee Jain (23112002)
Set C: Arslan Shaikh (23112034)

By observing the given information we've established that entities and their attributes will be as follows:

1. TRAIN
   train_id
   train_name
   type
   mileage
   driver_id

2. COACH
   coach_id
   train_id
   capacity
   mileage
   last_maintenance_date
   due_for_maintenance_date
   driver_id
   co_driver_id

3. DRIVERS
   driver_id
   driver_name
   contact
   rest_day
   accommodation_required

4. ROUTES
   route_id
   source_station
   deination_station

5. SCHEDULE
   schedule_id
   train_id
   route_id
   departure_time
   arrival_time
   driver_name
   co_driver_name
   yearly_delay

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


