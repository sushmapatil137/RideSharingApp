This is a simple Java console application that simulates a ride-sharing system.
It allows users to choose a ride type (bike or car), enter the distance, and then calculates the fare.
It also handles invalid ride types and invalid distances with custom exceptions.
Features:
Choose between Bike Ride and Car Ride
Fare calculation:
Bike → ₹10 × distance
Car → ₹20 × distance
Exception handling:
Invalid ride type → InvalidRideTypeException
Distance ≤ 0 → IllegalArgumentException
