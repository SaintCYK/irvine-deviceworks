Irvine DeviceWorks website (Night design)

Files
  index.html   the public one-page site
  shop.html    the in-store iPad page (not linked from the site; set as the iPad's home page)
  config.js    THE ONLY FILE YOU EDIT: WhatsApp number, display number, shop address
  qrcode.js    QR code library (do not edit)

Set the WhatsApp number
  1. Open config.js in any text editor.
  2. Put the number in international format, digits only, no + or spaces:
       WHATSAPP_NUMBER: "447700900123",
     (a UK number 07700 900123 becomes 447700900123: drop the 0, add 44)
  3. Optionally set WHATSAPP_DISPLAY and SHOP_ADDRESS.
  4. Save. Every WhatsApp button, the footer and the iPad page's QR code update.

Preview on your computer: double-click index.html (shop.html for the iPad page).
