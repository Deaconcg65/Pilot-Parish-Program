IMAGES FOLDER
=============
Drop parish photos here. Recommended filenames:

hero-parish.jpg        — Main hero image (homepage, right column)
parish-exterior.jpg    — Church exterior (photo strip, slot 1)
parish-mass.jpg        — Mass / liturgy scene (photo strip, slot 2)
parish-community.jpg   — Community / people (photo strip, slot 3 + mission section)
chris-greer.jpg        — Chris Greer headshot (team card)
roger-rybkowski.jpg    — Roger Rybkowski headshot (team card)
raffaele-scotti.jpg    — Raffaele Scotti headshot (team card)

DIMENSIONS
----------
- Hero photos: 800×600px minimum, landscape
- Team headshots: 400×400px minimum, square or portrait
- Strip photos: 800×500px minimum, landscape

COMPRESSION
-----------
Run through Squoosh.app before uploading.
Target: under 200KB per image.

TO ADD PHOTOS TO PAGES
----------------------
Find placeholder divs in the HTML like:
  <div class="photo-placeholder">...</div>

Replace with:
  <img src="../images/parish-exterior.jpg" alt="Description">

The <!-- comment --> lines in the HTML show exactly where each image goes.
