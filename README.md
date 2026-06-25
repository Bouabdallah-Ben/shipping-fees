# Shipping Fees

Shipping Fees is a simple static website for quickly checking delivery prices by Algerian wilaya.

The page lets a user search for a wilaya, select it from a dropdown, and instantly generate a ready-to-copy Arabic message with the delivery price to the desk and to the customer's door.

## What The Website Does

- Searches Algerian wilayas by name or wilaya code.
- Shows a dropdown of matching wilayas while typing.
- Displays two delivery prices for the selected wilaya:
  - delivery to desk
  - delivery to door
- Supports an optional discount value that is subtracted from both prices.
- Saves the discount in the browser so it stays available after refreshing.
- Automatically copies the generated shipping message after selecting a wilaya.
- Provides a manual copy button for copying the message again.

## Main Files

- `shipping.html` - the main page with the searchable wilaya dropdown and shipping fee generator.
- `fees.html` - an alternate/static version of the same shipping fee page.

## How To Use

1. Open `shipping.html` in a browser.
2. Type a wilaya name or code in the search field.
3. Choose the correct wilaya from the dropdown.
4. Optionally enter a discount amount.
5. Copy or use the generated Arabic delivery message.

## Example

If the user selects Oran, the website generates a message showing the delivery price to the desk and the delivery price to the door.

## Technologies

- HTML
- CSS
- Vanilla JavaScript
- Browser local storage

No build step or backend server is required. The website can run directly from the HTML file.
