# Egypt Airport Transfers

[Explore the live booking flow](https://egyptairporttransfers.com/)

Travelers use this service to arrange airport pickups and drop-offs in Egypt. My work covered the booking interface, route maps, pricing, vouchers, and reservation management.

## From route to reservation

1. The traveler enters the trip details, including pickup time, passenger count, luggage, and an optional return trip.
2. The booking interface shows the route on a map and presents vehicle options alongside a trip summary.
3. Staff can review the reservation and its details in the booking dashboard.

## Frontend implementation

The React booking form uses separate components for trip inputs, route display, vehicle results, and the summary. Pricing calculations live in a dedicated module, so display components can use the calculated price without duplicating the pricing rules.

The live booking flow can be explored up to vehicle selection without submitting a reservation.
