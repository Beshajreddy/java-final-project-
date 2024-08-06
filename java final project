// User.java
public class User {
    private String userId;
    private String name;
    private String email;
    private String password;
    // Getters and Setters
}

// Flight.java
public class Flight {
    private String flightId;
    private String airline;
    private String departureCity;
    private String arrivalCity;
    private Date departureTime;
    private Date arrivalTime;
    private int availableSeats;
    private String flightClass;
    // Getters and Setters
}

// Booking.java
public class Booking {
    private String bookingId;
    private User user;
    private Flight flight;
    private Date bookingDate;
    private String status;
    // Getters and Setters
}

// FlightService.java
public class FlightService {
    public List<Flight> searchFlights(String departureCity, String arrivalCity, Date date, String flightClass) {
        // Logic to search flights from the database
    }
    
    public Flight getFlightDetails(String flightId) {
        // Logic to get flight details from the database
    }
}

// BookingService.java
public class BookingService {
    public Booking bookFlight(User user, Flight flight) {
        // Logic to book a flight and save to the database
    }
    
    public Booking getBookingDetails(String bookingId) {
        // Logic to get booking details from the database
    }
}
