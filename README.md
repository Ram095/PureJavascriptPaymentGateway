# FisdomAssignment
Payment Gateway

A form where the user can enter the credit card details like Card Number,
CVV and Expiry Date as well.

The saved card list is updated as the user adds new card

User can delete the cards which also gets deleted from the local Storage

1. Master Card, Visa, Discover and American Express are included in the project
2. Auto Tab after the user has entered the data into the input field
3. Master Card, Visa, Discover - 16 digits, CVV - 3 digits
4. American Express - 15 digits, CVV - 4 digits

  a) Master Card starts with - 51 to 55.
  b) Visa starts with - 4.
  c) Discover starts with 6011, 622126-622925, 644-649, 65.
  d) American Express starts with 34 or 37.
        
5. Local Storage limit is checked and only then new cards are added
6. CVV is not displayed in the list as it is private
7. Only the last 4 digits of Card Number are displayed and rest are replaced with an 'X'
8. Success message on successfull addition of a card is displayed
9. List is displayed if present otherwise 'no saved cards available' message is displayed to the user

Only Bootstrap.min.css is used.
No other external library has been used.
