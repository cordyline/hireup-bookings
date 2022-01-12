# hireup-bookings

## test stubs
### describe validation
* it should fail bookings less than 1 hour
* it should fail bookings more than 24 hours
* it should fail bookings not in 15 minute increments
* it should fail bookings with an end date later than the start date

### describe rates
* it should charge in-week wholly daytime bookings at the day rate
* it should charge in-week partially night time bookings at the night rate
* it should charge saturday hours at the saturday rate
* it should charge sunday hours at the sunday rate
* it should differentiate between friday and saturday hours of the same booking
* it should differentiate between saturday and sunday hours of the same booking
* it should differentiate between sunday and monday hours of the same booking

### describe sad paths
* it should throw an error if inputs are incorrectly formatted
