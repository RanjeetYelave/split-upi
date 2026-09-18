# Split UPI

A simple, lightweight, open-source web app for splitting a large UPI payment into multiple smaller QR payments.

## How to Use

1. Open `split_upi_standalone.html` in your browser.
2. Enter your **UPI ID (VPA)** and click **Save**.

   * Your UPI ID is saved locally in the browser.
3. Enter the **total amount** you want to collect.

   * Example: `₹8000`
4. Click **Generate QR**.
5. The app automatically splits the amount into payments of up to **₹1,999**.

   * ₹8,000 → ₹1,999 + ₹1,999 + ₹1,999 + ₹1,999 + ₹4
6. Show the generated QR code to the payer.
7. After receiving the payment, click **Mark Received / Next**.
8. Continue until the **Remaining** amount reaches ₹0.
9. The app displays a completion message when the full amount has been collected.

## Features

* Split payments automatically up to ₹1,999 per transaction
* UPI QR code generation
* Copy UPI payment details
* Open payment directly in a supported UPI app
* Payment progress tracking
* Local VPA storage
* Simple Settings page
* No backend or account required
* Works as a single HTML file
* Open source and free to use

## Important

This app **does not verify UPI payments automatically**. The **Mark Received** action is a manual confirmation by the user.

The QR generation uses an online QR library/service, so an internet connection may be required for QR generation.

## Credits

Created by **Ranjeet Yelave**.

Free to use • Open Source

GitHub: https://github.com/RanjeetYelave/split-upi
