Create a clean, modern, mobile-first restaurant discovery website called **“PortHarcourt Eats”** that helps users find restaurants around **Port Harcourt, Rivers State, Nigeria**, compare their ratings, locations, menus, food prices, and discover the best places to eat nearby.

Use **HTML, CSS, and vanilla JavaScript** for the frontend. Make the project beginner-friendly, interactive, responsive, and easy to expand later.

### Main Goal

The website should allow users to:

* Find restaurants in Port Harcourt
* Search restaurants by name or location
* Search for specific foods
* See restaurant ratings and review counts
* See food/menu items and their prices in Nigerian Naira
* See restaurant locations and approximate distance
* Filter restaurants by rating, price, cuisine, and location
* View detailed restaurant information
* Save favorite restaurants

### Port Harcourt Locations

Include restaurant discovery around areas such as:

* GRA Phase 1
* GRA Phase 2
* Old GRA
* Trans Amadi
* Woji
* Rumuola
* Rumuokoro
* Rumuodara
* Eliozu
* D-Line
* Peter Odili Road
* Ada George
* Choba
* Alakahia
* Rumuigbo
* Borokiri
* Town
* Stadium Road
* Artillery
* Abacha Road

### Homepage

Create a hero section with:

**“Find the best food in Port Harcourt”**

Subtitle:

**“Discover restaurants, compare menus and prices, check ratings, and find great food near you.”**

Include:

* Search bar: **“Search restaurants, food, or area...”**
* 📍 **Use My Location** button
* Search button
* Popular food categories
* Featured restaurants
* Highly rated restaurants
* Restaurants near the user

### Restaurant Cards

Each restaurant card should display:

* Restaurant image
* Restaurant name
* ⭐ Rating
* Number of reviews
* 📍 Location
* Distance
* Cuisine type
* Price range
* Open/Closed status
* Popular food item
* Starting food price
* ❤️ Favorite button
* **View Restaurant** button

Example layout:

**Restaurant Name**
⭐ 4.7 · 245 reviews
📍 GRA Phase 2, Port Harcourt
🍴 Nigerian · Continental
💰 Meals from ₦3,000
🟢 Open Now

**Popular:** Jollof Rice + Chicken — ₦4,500

[View Restaurant]

### Restaurant Details

When a user clicks **View Restaurant**, display:

* Restaurant name
* Large restaurant image/gallery
* Rating
* Number of reviews
* Full location
* Distance
* Opening hours
* Phone number
* About the restaurant
* Menu
* Food categories
* Individual food prices
* Popular dishes
* Customer reviews

Add buttons:

* 📍 Get Directions
* 📞 Call
* 💬 WhatsApp
* ❤️ Save

### Menu

Create realistic menu categories:

**Nigerian Food**

* Jollof Rice
* Fried Rice
* Coconut Rice
* Ofada Rice
* Pounded Yam
* Egusi Soup
* Okro Soup
* Vegetable Soup
* Native Rice

**Grills**

* Grilled Chicken
* Grilled Fish
* Suya
* Barbecue

**Fast Food**

* Burger
* Shawarma
* Pizza
* Chicken & Chips

**Soups & Local Meals**

* Pepper Soup
* Goat Meat Pepper Soup
* Catfish Pepper Soup
* Amala
* Eba
* Fufu

**Drinks**

* Soft Drinks
* Water
* Fresh Juice
* Smoothies

Every menu item must display a **₦ price tag**.

Example:

**Jollof Rice + Chicken** — ₦4,500
**Catfish Pepper Soup** — ₦6,000
**Shawarma** — ₦4,000
**Pounded Yam + Egusi** — ₦5,500

Clearly label all prices as **sample/demo prices** unless obtained from a verified current source.

### Search

Make the search fully interactive with JavaScript.

Searching:

**“Jollof”**

should display restaurants selling Jollof Rice.

Searching:

**“GRA”**

should display restaurants around GRA.

Searching:

**“Suya”**

should display restaurants selling Suya.

Searching:

**“Chinese”**

should display Chinese restaurants.

### Filters

Add interactive filters:

**Location**

* GRA
* Trans Amadi
* Woji
* Rumuola
* Rumuokoro
* Choba
* Eliozu
* D-Line
* Other Port Harcourt areas

**Rating**

* 4.5+
* 4.0+
* 3.5+
* Any rating

**Price**

* Under ₦3,000
* ₦3,000–₦5,000
* ₦5,000–₦10,000
* ₦10,000+

**Cuisine**

* Nigerian
* Fast Food
* Chinese
* Indian
* Italian
* Continental
* Seafood
* Local Food
* BBQ/Grills

**Availability**

* Open Now
* All Restaurants

### Sorting

Allow users to sort by:

* Recommended
* Highest Rated
* Cheapest
* Closest
* Most Reviewed

Results should update instantly without refreshing the page.

### Location

Add a **“Use My Location”** button using the browser Geolocation API.

For the beginner version:

1. Ask the user for location permission.
2. Get latitude and longitude.
3. Display “Location detected.”
4. Show nearby restaurants using the sample location data.
5. Structure the code so a real map API can be connected later.

### Map

Create a map section for Port Harcourt showing restaurant markers.

Use a placeholder map if necessary, but structure the project so it can later integrate with:

* Google Maps
* Mapbox
* OpenStreetMap

Restaurant markers should show the restaurant name, rating, and starting price when clicked.

### Ratings

Display ratings using stars:

⭐ 4.9
⭐ 4.7
⭐ 4.5
⭐ 4.2

Include review counts:

**⭐ 4.8 · 312 reviews**

Add a detailed review section on the restaurant page.

### Nigerian Design

Make the website feel appropriate for users in Port Harcourt.

Use:

* ₦ Nigerian Naira
* Nigerian food
* Port Harcourt neighborhoods
* Nigerian restaurant names
* Nigerian phone-number formatting
* WhatsApp contact buttons
* “Open Now” indicators
* Local delivery/takeaway information where available

### Important Data Requirement

The website should be designed to **search/find real restaurants in Port Harcourt and display current information where a reliable data source is available**, including:

* Restaurant name
* Current rating
* Review count
* Address/location
* Opening hours
* Menu items
* Current prices
* Cuisine
* Contact information

Do not invent real restaurant ratings, addresses, menus, or prices. If real data is unavailable, clearly mark the information as **demo/sample data**.

### Responsive Design

Mobile:

* One-column restaurant cards
* Large search bar
* Touch-friendly filters
* Bottom navigation
* Compact map

Tablet:

* Two-column restaurant grid

Desktop:

* Three/four-column restaurant grid
* Large map beside results
* Desktop navigation
* Advanced filtering sidebar

### Navigation

Use:

**Home | Explore | Map | Favorites | Profile**

### Empty State

If no restaurants match a search:

**“No restaurants found”**

“Try searching for another food, restaurant, or Port Harcourt area.”

Add:

**[Clear Filters]**

### Loading State

Create skeleton loading cards while restaurant information is loading.

### Project Structure

Provide:

```text
portharcourt-eats/
├── index.html
├── style.css
├── script.js
└── images/
```

Use only:

* HTML
* CSS
* Vanilla JavaScript

Do not use React, Vue, Bootstrap, Tailwind, or other frameworks.

Keep the code beginner-friendly with clear comments and explanations.

The finished website should look like a polished combination of a **restaurant directory, food menu browser, local discovery app, and map-based restaurant finder specifically designed for Port Harcourt, Nigeria**.
