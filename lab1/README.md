# Laboratory Work #1

## Topic: Hotel Management System

## Domain Description

The system is designed for a hotel to track its financial operations. The hotel provides rooms to clients for specific periods. Each room is characterized by:
- Capacity
- Comfort level (luxury, semi-luxury, standard)
- Price

The hotel keeps track of client information including:
- Last name
- First name
- Middle name
- Additional comments

Room booking is processed based on availability and client preferences for the parameters mentioned above. The system records:
- Check-in date for each booking
- Check-out date for each occupied space

## Implementation Progress

### Commit 1: Initial ER Model

**Commit Message**: ` add initial ER diagram for hotel management system`

#### Entity-Relationship Model

The ER diagram represents the domain model in Third Normal Form (3NF) with the following main entities:

1. **Client**
   - Primary entity for the laboratory work
   - Contains personal information
   - Will be the focus of implementation in labs 1-4

2. **Room**
   - Contains room specifications
   - Linked to comfort levels and bookings

3. **Booking**
   - Represents reservations
   - Links clients with rooms
   - Tracks check-in and check-out dates

The complete ER diagram can be found at: [`./diagrams/ERdiagram.svg`](./diagrams/ERdiagram.svg)

---
> 📝 **Note**: Each commit represents a distinct implementation step.
