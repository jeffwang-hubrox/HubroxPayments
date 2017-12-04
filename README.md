# HubroxPayments
Payment Application for HB-9000

Hubrox Payments is a demo application for POS device HB-9000. It demonstrates the features of HB-9000, and is also an example of a smart payment processing experience. It contains the following main pages:

1. Latest Payment
Default page on start-up, shows the recent payments made, including date and amount.

2. Items
Displays barcodes, item names, and prices. "Add" button adds a new item to database by scanning barcode, inputting description and price. Now it only works with barcodes containing only digits (e.g. UPC), and if a barcode starts with “0”, please remove the “0” before adding it to the database. You will not need to delete the “0” when you edit, remove, or scan to make a payment in the future. "Edit" edits the selected item, options are like "Add". “Delete” deletes the selected item from database.

3. Make Payments
Press the scan buttons on either side, the barcode will appear in the textbox where it says “Type or scan code”, hit “SCAN” when finished. A table will be built when items are scanned. Payment received by swiping inserting or tapping the payment card. In swipe interface, the receipt will be printed once a card is swiped. In insert interface, insert the card, hit “RESET”, then “DETECT”, the receipt will be printed once a chip card is detected. In tap interface, press “OPEN”, then “CHECK”, the receipt will be printed once the NFC reader detects a card.

4. About
Information page of the application.
