# Wedding Venue Scraper

This project is a web scraping tool that extracts details of wedding venues from "The Knot" wedding venue marketplace for London, OH. The scraped data includes venue names, ratings, and descriptions, providing valuable insights for users planning weddings or researching venue options.

## Project Features

1. **Web Scraping**:
   - Scrapes venue name, rating, and description from the targeted webpage.

2. **Data Storage**:
   - Saves scraped data in a structured format (CSV or JSON) for analysis or further use.

## Technologies Used

- **Python Libraries**:
  - `BeautifulSoup` and `requests` for web scraping.
  - `Pandas` for data manipulation.
  - `Jupyter Notebook` for further data exploration.
 
## Sample Data

The scraped data contains the following columns:
- **Venue Name**: The name of the wedding venue.
- **Rating**: The average user rating for the venue.
- **Description**: A brief description of the venue.

| Venue Name         | Rating | Description                                   |
|--------------------|--------|-----------------------------------------------|
| The Grand Venue    | 4.5    | A luxurious wedding venue with classic decor. |
| Rustic Charm Barn  | 4.7    | A rustic-style venue perfect for countryside weddings. |
| Downtown Elegance  | 4.3    | Modern venue located in the heart of London.  |
