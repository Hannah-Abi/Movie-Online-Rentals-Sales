## Business Overview 
- MovieNow: an online movie rental company
- Platform to stream movies
- Additional information for each movie: genre, main actors, etc.
- Customer informationCustomers can give a rating after watching a movie

## Objectives of Data-driven decision making
Objectives of data driven decision making
- Information for operational decisions
  - Popularity of actors to decide which movies to invest in.
  - Revenue of the last months to estimate budget for short term investments.
- Information for strategic decisions
  - Success across countries to decide on market extensions.
  - Longterm development of revenue for long term investments.

## MovieNow data structure
These tables capture information about customers, movies, movie rentals, actors, and actor-movie relationships in the MovieNow database. The MovieNow database structure includes:
- **Customers Table:**
  - Columns: `customer_id`, `name`, `country`, `gender`, `date_of_birth`, `account_creation_date`.
- **Movies Table:**
  - Columns: `movie_id`, `title`, `genre`, `runtime`, `release_year`, `rental_cost`.
- **Renting Table:**
  - Columns: `renting_id`, `customer_id`, `movie_id`, `rating` (1 to 10), `rental_date`.
- **Actors Table:**
  - Columns: `actor_id`, `name`, `year_of_birth`, `nationality`, `gender`.
- **Actsin Table:**
  - Columns: `actsin_id`, `movie_id`, `actor_id`.
