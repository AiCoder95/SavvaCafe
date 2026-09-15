# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary users are guests in Madinah who are deciding where to go for coffee, dessert, a light breakfast, or a calm evening visit. They may be local residents, visitors, or tourists near Bir Uthman who need to quickly understand what SAVVA is, where it is, why it is worth visiting, and what action to take next.

## Product Purpose

The site exists to bring more people to SAVVA Specialty Coffee in Madinah. Success means visitors quickly understand the place, trust it, view the menu if needed, and choose a next action: build a route, call to reserve, or check the menu before visiting.

## Positioning

SAVVA is presented as a real specialty coffee place in Bir Uthman with visible street presence, indoor and outdoor seating, coffee, matcha, desserts, and light breakfast. The site should sell the decision to visit through real cafe evidence: actual photos, Google Maps facts, menu prices, address, phone, and multilingual access.

## Operating Context

Visitors are likely using the site on a phone, often while choosing a cafe nearby or planning a visit in Madinah. The main flows are opening Google Maps directions, checking the menu and prices, calling the cafe, and confirming practical visit information such as address and hours.

The site is currently a static multilingual web page with Arabic as the default page language and English/Russian language switching. It is hosted with Sites and published at `https://savva-cafe-madinah.jhnnscjhnngmlcm.chatgpt.site/`.

## Capabilities and Constraints

The site must keep the primary actions clear: “Build route”, “View menu”, and “Reserve table” / call. It must remain responsive across phones, tablets, and desktop screens, with no horizontal scrolling, hidden buttons, overlapping header content, or menu text collisions.

The site uses real business information and should not invent reviews, fake dishes, fake interior scenes, or generated food photos presented as real. Hours are treated as usually 7:00 AM to 2:00 AM, with a note that visitors should verify on Google Maps before visiting.

Current implementation is static HTML, CSS, and JavaScript inside `dist/`. The known hosting configuration is a static Sites project with `dist` as the public directory.

## Brand Commitments

The business name is SAVVA / سافا, described as Specialty Coffee. The site must preserve the cafe identity, real address, real phone number, real menu data, and multilingual presentation in Arabic, English, and Russian.

The tone should feel clear, premium, calm, and practical for a cafe/restaurant site. Future copy should avoid generic AI-sounding advertising phrases and should favor concrete reasons to visit.

## Evidence on Hand

Confirmed or previously gathered materials include:

- Cafe name: SAVVA / سافا / SAVVA Specialty Coffee.
- Address: Zubairah Al Roumiah, Bir Uthman, Madinah 42331, Saudi Arabia.
- Phone: +966 56 437 0303.
- Google Maps facts previously visible: rating 4.7, 729 reviews, 636+ guest photos.
- Instagram profile: `https://www.instagram.com/savva_cafe/`.
- User-provided real exterior photo: `dist/assets/exterior.jpg`.
- User-provided real interior photo: `dist/assets/interior.jpg`.
- Menu items and prices extracted from the provided SAVVA menu PDF.
- User-confirmed primary goal: bring the person to the cafe.
- User-confirmed likely audience: guests in Madinah.
- User-stated usual hours: 7 AM to 2 AM.

Google Maps photos may inform design and content strategy, but they should not be copied into the site as owned assets unless usage rights are confirmed.

## Product Principles

1. Make the visit decision obvious within a few seconds: what the place is, where it is, why to come, and what to press next.
2. Prefer real evidence over decoration: photos, menu prices, address, phone, reviews, and concrete visit reasons.
3. Keep route-building and menu access faster than reading long promotional copy.
4. Preserve multilingual usability, including Arabic RTL behavior and readable English/Russian translations.
5. Treat mobile as the primary decision environment and prevent overlap, hidden controls, or cramped touch targets.

## Accessibility & Inclusion

The site should support Arabic, English, and Russian users. Interactive controls need readable labels, sufficient contrast, and touch-friendly sizing on mobile. Text should remain readable and layout should remain usable when viewport width changes.
