# SWGoH Data Scraper

SWGoH Data Scraper is a Python script designed to scrape data from the Star Wars Galaxy of Heroes (SWGoH) website (swgoh.gg) for guilds and their members. It retrieves data such as Territory War (TW) history, Territory Battle (TB) history, Raid history, account details, unit data, and ship data.

## Features

- **Scraping Guild Data**: Retrieve TW, TB, and Raid history for a guild.
- **Scraping Account Data**: Get detailed information about each member of a guild, including their Galactic Power (GP), roles, arena ranks, fleet arena ranks, player rating skill, and more.
- **Scraping Unit and Ship Data**: Collect data on the units and ships owned by each guild member, including their names, sides, stars, levels, gear levels, relic tiers, zetas, omicrons, GP, and images.
- **Generating Reports**: Generate CSV and Excel reports for guild data, account data, unit data, ship data, TW history, TB history, and Raid history.

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/swgoh-data-scraper.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Modify the `main()` function in `swgoh_data_scraper.py` to customize the behavior of the script if necessary.
2. Run the script:

    ```bash
    python swgoh_data_scraper.py
    ```

3. The script will generate CSV and Excel reports in the current directory containing the scraped data.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for any bugs, feature requests, or improvements you may have.
