# Raffle Draw Project

- sell lottery ticket
- update lottery ticket
- delete lottery ticket
- get all ticket
- get ticket by id
- bulk buy (user can buy multiple ticket at a time)
- raffle draw

# Ticket

- Number (Must be unique)
- username
- price
- timestamp

# Routes

- /tickets/t/:ticketId GET find single ticket
- /tickets/t/:ticketId PATCH update ticket by id
- /tickets/t/:ticketId DELETE delete ticket by id
- /tickets/u/:username GET find ticket for a given number
- /tickets/u/:username PATCH update ticket for a given number
- /tickets/u/:username DELETE delete ticket for a given number
- /tickets/sell = create ticket
- /tickets/bulk = bulk sell ticket
- /tickets/draw
- /tickets/ - find all tickets
