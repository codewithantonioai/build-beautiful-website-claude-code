MARIGOLD BAKERY WEBSITE
=======================

HOW TO VIEW IT
Double-click index.html. It opens in your web browser. Use the menu at the
top to visit the other pages. Keep all the files together in the same folder.

THE FILES
  index.html    Home page
  menu.html     Menu and prices
  cakes.html    Custom Cakes: three cake styles, starting prices, order buttons
  about.html    Our story
  contact.html  Opening hours, address, phone, email
  style.css     Colors and layout for every page

HOW TO EDIT
1. Right-click a .html file and open it with a plain text editor
   (Notepad, TextEdit in plain-text mode, or any code editor).
2. Find the text you want to change and type over it. Only change the words,
   not the parts inside < > brackets.
3. Save, then refresh the page in your browser to see the change.
Lines starting with <!-- EDIT ... --> are notes to guide you.

PLACEHOLDERS TO REPLACE
Anything in [square brackets] is a placeholder. Search each file for "[".

  index.html    tagline, welcome text, hours summary, address (also in footer)
  menu.html     ALL items and prices are samples. To add an item, copy one
                <div class="menu-item"> ... </div> block and edit it.
  cakes.html    the three sample cakes (name, price, description, servings), the
                "How to order" lead times, and the email address in each
                "Order this cake" button (hello@example.com: replace it in all three)
  about.html    the three story paragraphs and the "what we believe" list
  contact.html  opening hours, address, phone, email, and the Google Maps link
                (replace YOUR+ADDRESS+HERE with your address, using + for spaces)
  footer        every page ends with your address; change it on all five pages

CHANGING COLORS
At the top of style.css, the lines under ":root" hold the colors.
Change a code like #F7B21A to another color code to restyle the whole site.

FONTS
The headings and text use two free Google fonts (Young Serif and Hanken
Grotesk). They load from the internet. If someone views the site offline,
the browser quietly uses a similar font already on the computer.

THE MARIGOLD
The big flower on the home page and the small one in the logo are drawn
in the page itself, so there are no image files to manage. The petals open
once when the home page loads (not for visitors who have turned animations
off in their device settings).

PUTTING IT ONLINE
When you're ready, upload all of these files to any simple web host
(for example Netlify Drop, GitHub Pages, or your domain provider's hosting).
