# Trace Circle — Digital Product Passport

Mobile-first HTML/CSS/JavaScript implementation inspired by the supplied reference.

## Run
Open `index.html` in a modern browser with an internet connection. The shirt image is local in `assets/`. Leaflet, OpenStreetMap tiles, and GSAP load from CDNs.

## Interactions
- Live, draggable OpenStreetMap with five journey markers and a dashed route through the supplied example locations.
- Click a timeline stage or map marker to focus the map and show details.
- Zoom in/out, fit all locations, and expand/collapse the map.
- GSAP entrance and scroll-reveal animations, with reduced-motion preference support.
- Feedback form demo and language selection status.

## Production notes
- Map locations are illustrative sample coordinates for the product journey (Coimbatore/Tiruppur/Bengaluru), not verified supplier GPS coordinates. Replace them with coordinates from the product/DIP API.
- OpenStreetMap tiles need internet access and must retain attribution. For high-traffic production use, review the OpenStreetMap tile usage policy and consider a suitable hosted tile provider.
- Login and feedback submission are front-end demos; connect them to your authentication and feedback APIs.
- GSAP and Leaflet are loaded from public CDNs. Bundle/pin dependencies locally if required by your deployment policy.
