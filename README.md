# zoura-website
Zoura website

## Door-to-door sales form (`index.html`)

A mobile-friendly quote request form for sales reps to fill out on a
customer's doorstep. It collects name, email, phone, property address, and
which services the customer wants, then emails it straight to the business
inbox.

**Setup (one-time, ~1 minute):**

1. Go to [web3forms.com](https://web3forms.com) and sign up using
   `admin@zoura.com.au`.
2. Copy the free Access Key it gives you.
3. Open `index.html` and paste the key into the
   `WEB3FORMS_ACCESS_KEY` variable near the top of the `<script>` block.
4. Save the file. Open it in any browser (double-click it, or host it
   anywhere) and it's ready to use.

Until a key is set, the "Send Quote Request" button falls back to opening
the rep's own email app with the details pre-filled, so the form is usable
immediately even before setup is finished.
