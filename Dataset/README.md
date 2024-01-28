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
