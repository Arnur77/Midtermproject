# Game Hub

## Midterm Project

Game Hub is a responsive website for finding and booking computer gaming clubs.

The idea of the project is to make it easier for users to find a gaming club, compare prices and ratings, choose a computer and book a gaming session.

The project was created by:

- Sultan Nurlybek
- Amur Kudaibergen

## Project Pages

The website contains the following pages:

1. Home
2. Clubs & Map
3. Club Details
4. Payment
5. My Bookings
6. Profile
7. Gallery
8. Sitemap

## Main Features

### Home Page

The home page contains:

- Website introduction
- Search for gaming clubs
- Popular gaming clubs
- Club cards
- Navigation to other pages
- Information about how the website works

### Clubs & Map

This page allows users to:

- Search for gaming clubs
- Filter clubs by price
- Filter clubs by rating
- View gaming clubs on a map
- Open club details
- Check club information

Leaflet.js is used for the interactive map.

### Club Details

The club details page contains:

- Club name
- Club rating
- Club location
- Club description
- Club features
- Gaming PC selection
- Date selection
- Start and end time
- Booking duration
- Total price

The available PCs change depending on existing bookings.

### Payment

The payment page contains:

- Booking information
- Total price
- Deposit amount
- Payment method selection
- Card payment form
- Cash option
- Other payment option

After confirmation, the booking is saved.

### My Bookings

The bookings page allows users to:

- View all bookings
- See the selected club
- See the selected PC
- See date and time
- See booking duration
- See total price
- See deposit
- Cancel a booking

Multiple bookings can be stored at the same time.

### Profile

The profile page contains basic user information and a link to the bookings page.

### Gallery

The gallery page shows images related to gaming clubs and gaming setups.

### Sitemap

The sitemap page shows the structure and main pages of the website.

## Technologies

The project uses:

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Leaflet.js
- LocalStorage

## HTML

HTML5 is used to create the structure of the website.

The project uses:

- Headings
- Paragraphs
- Lists
- Links
- Images
- Tables
- Forms
- Buttons
- Div elements
- Span elements
- Semantic elements such as `header`, `main`, `section`, `article` and `footer`

## CSS

CSS is used for the visual design of the website.

The project includes:

- CSS selectors
- Classes
- IDs
- Colors
- Fonts
- Margins
- Padding
- Borders
- Alignment
- Hover effects
- Flexbox
- CSS Grid
- Positioning

Different positioning methods are used, including:

- `relative`
- `absolute`
- `fixed`
- `sticky`

## Flexbox

Flexbox is used for:

- Navigation
- Buttons
- Card layouts
- Feature tags
- Booking information
- Alignment of elements

## CSS Grid

CSS Grid is used for:

- Gaming club cards
- Gallery
- Booking information
- PC selection
- Profile information

## Bootstrap

Bootstrap 5 is used in the project for responsive layout and interface components.

Bootstrap Grid is used with:

- `container`
- `row`
- `col-md-*`
- `col-lg-*`

Bootstrap utility classes are also used, for example:

- `mt-*`
- `mb-*`
- `py-*`
- `g-*`
- `w-100`
- `text-center`
- `ms-auto`

Bootstrap is also used for buttons, forms and responsive navigation.

## Responsive Design

The website is responsive and works on different screen sizes.

The project includes breakpoints for:

- Desktop
- Tablet
- Mobile

CSS media queries are used to change the layout for smaller screens.

For example, club cards change from multiple columns to one column on mobile devices.

## JavaScript

JavaScript is used to make the website interactive.

JavaScript features include:

- Club search
- Club filtering
- Map markers
- PC selection
- Booking calculations
- Time validation
- Booking conflict checking
- Payment method selection
- Booking creation
- Booking cancellation

## LocalStorage

The browser `localStorage` is used to save bookings.

The website stores:

- Club
- PC
- Date
- Start time
- End time
- Duration
- Total price
- Deposit
- Payment method

This allows bookings to remain available after changing pages or refreshing the website.

## Project Structure

```text
Game Hub/
│
├── index.html
├── clubs.html
├── details.html
├── payment.html
├── bookings.html
├── profile.html
├── gallery.html
├── sitemap.html
├── README.md
│
└── css/
    └── styles.css
How to Run
1. Download or clone the project.
2. Open the project folder.
3. Open index.html in a web browser.
4. Use the navigation menu to visit other pages.
For the best experience, the project can also be opened using a local development server.
Map
The map is implemented using Leaflet.js and OpenStreetMap tiles.
The club locations shown on the map are demonstration locations used for the student project.
Booking Flow
The main booking flow is:
Home
   ↓
Clubs & Map
   ↓
Club Details
   ↓
Choose PC
   ↓
Choose Date and Time
   ↓
Payment
   ↓
My Bookings

Authors
Sultan Nurlybek & Amur Kudaibergen
Project Type
Midterm Project
