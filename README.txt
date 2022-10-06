For this project, I utilized the transition property to make a nice resize effect while hovering over the images.
The navigation was used as a filler element and the items in the navigation do not lead anywhere, not even with a #.
The background was created using Canva by simply stacking blocks on besides others in an alternating fashion.
The border, z-index, and box-shadow attributes help to highlight the item that the mouse is over, adding to the overall component of the gallery.
The photos' original size was 512x512px and they were size to 512x512px while highlighted, however they did have grain on them. By default,
they were sized to 180x512px with an object-fit:cover.
I did not utilize blend modes because I could only find blend modes that would work on the background, not the photos, which I used an <img> tag for.
I did not use display:flex nor display:grid, leading to an unfortunate lack of responsiveness. It is barely decent on tablet, but phone is not ideal for it.
