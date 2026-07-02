# zoura-website
Zoura website

## Door-to-door sales form (`index.html`)

A mobile-friendly quote request form for sales reps to fill out on a
customer's doorstep. It collects name, email, phone, property address, and
which services the customer wants, then emails it straight to the business
inbox.

**Setup:** already done — a Web3Forms Access Key tied to `admin@zoura.com.au`
is configured in `index.html`. Just open the file in any browser (or host
it) and submissions will email straight to that inbox.

If the key is ever removed or missing, the "Send Quote Request" button
falls back to opening the rep's own email app with the details pre-filled,
so the form stays usable either way.
