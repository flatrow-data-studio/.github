## Flatrow Data Studio

We build [Apify Actors](https://apify.com/myth84) that turn hotel, holiday-rental and online-marketplace pages into clean price tables, with no personal data, and you pay only for the results you get.

Every Actor returns one flat row per hotel, listing, product or review, with the same columns across the platforms of a theme, so that prices can be compared side by side. Most of them track prices: schedule the same search and get the drops and rises since the previous run. Prices below are the lowest tier price ("from") per 1,000 results; the Apify Free plan price is on each Actor's Pricing tab.

## Hotel prices

| Actor | What you get | Price |
|---|---|---|
| [Booking.com Hotels Scraper & Price Tracker](https://apify.com/myth84/booking-hotels-scraper) | Booking.com search results for any destination and stay: total price, taxes, review score, reviews, stars, location. | from $1.69 / 1,000 properties |
| [Google Hotels Scraper & Price Tracker](https://apify.com/myth84/google-hotels-scraper) | Lowest price per hotel with taxes, and every booking site's rate with direct links (rate parity). | from $1.69 / 1,000 hotels |
| [Agoda Hotels Scraper & Price Tracker](https://apify.com/myth84/agoda-hotels-scraper) | Agoda search results: nightly and total price with and without taxes, guest rating, reviews, stars. | from $1.29 / 1,000 hotels |
| [Expedia Hotels Scraper & Price Tracker](https://apify.com/myth84/expedia-hotels-scraper) | Expedia search results: nightly and total price, guest rating, reviews, class, location. | from $1.29 / 1,000 hotels |
| [Booking.com Hotel Details Scraper: Rooms & Prices](https://apify.com/myth84/booking-hotel-details-scraper) | Hotel pages by URL: room types, facilities, photos, address, stars and the cheapest offer for your dates. | from $1.69 / 1,000 hotels |

## Short-term rentals

| Actor | What you get | Price |
|---|---|---|
| [Airbnb Listings Scraper & Price Tracker](https://apify.com/myth84/airbnb-listings-scraper) | Airbnb search results for any location and dates: nightly and total price, rating, reviews, type, coordinates. | from $0.99 / 1,000 listings |
| [Airbnb Listing Details & Availability Calendar](https://apify.com/myth84/airbnb-listing-details-scraper) | Listing pages by URL: amenities, house rules, six category ratings and a day-by-day availability calendar. | from $0.99 / 1,000 listings |

## Anonymous reviews

| Actor | What you get | Price |
|---|---|---|
| [Airbnb Reviews Scraper: Anonymous Ratings & Texts](https://apify.com/myth84/airbnb-reviews-scraper) | Rating, month, language, text and translation, stay length; no author name, photo, profile or location. | from $1.19 / 1,000 reviews |
| [Booking.com Reviews Scraper: Anonymous Scores](https://apify.com/myth84/booking-reviews-scraper) | Score, month, liked and disliked texts, trip type, room type and the hotel's sub-scores; no reviewer identity. | from $0.79 / 1,000 reviews |

## E-commerce prices

| Actor | What you get | Price |
|---|---|---|
| [Amazon Products Scraper & Price Tracker](https://apify.com/myth84/amazon-search-scraper) | Amazon search results on 9 marketplaces: price, list price, coupon, rating, reviews, bought in past month, badges. | from $0.99 / 1,000 products |
| [AliExpress Products Scraper & Price Tracker](https://apify.com/myth84/aliexpress-search-scraper) | AliExpress search results for your country and currency: price, discount, rating, units sold, ship-from, delivery. | from $1.19 / 1,000 products |
| [AliExpress Product Details Scraper & Shipping](https://apify.com/myth84/aliexpress-product-scraper) | Product pages by URL or ID: every variant with price and stock, shipping cost and delivery time to your country. | from $2.10 / 1,000 products |
| [eBay Listings Scraper & Price Tracker](https://apify.com/myth84/ebay-search-scraper) | eBay search results on 9 marketplaces: price, condition, buying format, shipping, units sold. | from $1.69 / 1,000 listings |
| [Walmart Products Scraper & Price Tracker](https://apify.com/myth84/walmart-search-scraper) | Walmart.com and Walmart.ca search and category pages: price, was-price, stock, rating, badges. | from $0.99 / 1,000 products |
| [Etsy Listings Scraper & Price Tracker](https://apify.com/myth84/etsy-search-scraper) | Etsy search results in USD, EUR or GBP: price, sale price, rating, reviews, free-shipping flag. | from $1.29 / 1,000 listings |

## Multi-marketplace price comparison

| Actor | What you get | Price |
|---|---|---|
| [Price Comparison: Amazon, AliExpress, eBay & more](https://apify.com/myth84/marketplace-price-compare-scraper) | One keyword on Amazon, AliExpress, eBay, Walmart and Etsy in one run: one table with the same columns on every marketplace, plus the lowest, median and highest price per marketplace. | from $1.29 / 1,000 products |

## Python examples

Small, MIT-licensed scripts that call the Actors with the official `apify-client` package: a search to CSV and a daily price tracker.

- [booking-scraper-python](https://github.com/flatrow-data-studio/booking-scraper-python): Booking.com hotel prices, taxes, review scores and stars.
- [google-hotels-scraper-python](https://github.com/flatrow-data-studio/google-hotels-scraper-python): Google Hotels prices and the rate of every booking site.
- [airbnb-scraper-python](https://github.com/flatrow-data-studio/airbnb-scraper-python): Airbnb listings with nightly and total prices.
- [amazon-scraper-python](https://github.com/flatrow-data-studio/amazon-scraper-python): Amazon product prices, coupons and ratings.
- [aliexpress-scraper-python](https://github.com/flatrow-data-studio/aliexpress-scraper-python): AliExpress product prices for your country and currency.
- [ebay-scraper-python](https://github.com/flatrow-data-studio/ebay-scraper-python): eBay listing prices, condition and shipping.

## MCP kits for AI agents

Ready-made Apify MCP server configurations: one URL that connects several Actors to Claude, ChatGPT, Cursor or VS Code, a system prompt that tells the agent which tool answers which question, and test prompts.

- [Hotel price agent](https://github.com/flatrow-data-studio/mcp-kits/blob/main/hotel-price-agent.md): Booking.com, Google Hotels, Agoda, Expedia and Airbnb.
- [E-commerce price agent](https://github.com/flatrow-data-studio/mcp-kits/blob/main/ecommerce-price-agent.md): Amazon, AliExpress, eBay, Walmart and Etsy, one by one or compared in one run.

## Data and support

- **No personal data**: no names of hosts, guests, reviewers or private sellers, no profile photos, no account data. Reviews are anonymous. Nothing is collected behind a login.
- **Questions, bugs and feature requests**: the Issues tab of each Actor on Apify Store.
