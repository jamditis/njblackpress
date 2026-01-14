# NJ Black Press database

A historical database documenting Black publications in New Jersey from 1880 to present day.

## Overview

This database catalogs approximately 140 Black-owned and Black-focused publications that have operated in New Jersey, including newspapers, magazines, newsletters, and digital media outlets. The data spans over 140 years of Black press history in the state.

**Project lead:** Cassandra Etienne, Associate Director of Programming and Membership
**Data curator:** Amanda Alicea
**Project owner:** [Center for Cooperative Media](https://centerforcooperativemedia.org/)

## Data structure

### Source files

The data is exported from Notion and stored in:
- `data/` - Contains individual markdown files for each publication plus CSV exports

### Schema fields

Each publication record includes:

| Field | Description |
|-------|-------------|
| ID | Unique identifier |
| Publication | Name of the publication |
| Alternate Name | Other names used |
| Location (City) | Primary city of operation |
| Owners/Publishers | Publishing entity or individuals |
| Year founded | Start year |
| Year ceased | End year (if applicable) |
| Frequency of publication | Weekly, monthly, daily, etc. |
| Format | Newspaper, periodical, digital, etc. |
| Languages published | Primary language(s) |
| Political/Social affiliation | Editorial stance or affiliations |
| Historical notes + impact | Context and significance |
| Archive/Call Number | LCCN, OCLC, or other catalog numbers |
| Website/Archive | URLs to archives or current sites |
| Target audience | Intended readership |
| Primary focus/Content areas | Subject matter coverage |
| Medium/Distribution method | Print, online, multimedia |
| Mission statement | Editorial philosophy |
| Key staff members | Notable editors, publishers |
| Challenges faced | Historical obstacles |
| Community impact | Documented influence |
| Notes | Additional context |
| Sources | Citation information |

## Notable publications in the database

### Historical (pre-1950)
- **The Sentinel** (1880, Trenton) - One of NJ's earliest Black newspapers
- **New Jersey Trumpet** (1887-1897, Newark)
- **The Echo** (1904-1943, Long Branch/Red Bank) - "Oldest colored paper in New Jersey"
- **The Camden News** (1915-1918)
- **Newark Herald** (1928-1939)
- **New Jersey Afro-American** (1941-?, Newark) - "Longest running and most widely read Black newspaper in New Jersey"

### Civil rights era (1950-1980)
- **Black Newark** (1968-1974) - Committee for Unified Newark publication
- **Unity and Struggle** (1972-?, Newark) - Connected to Congress of Afrikan People
- **Essex Forum** (1972-?, East Orange)

### Contemporary digital outlets (2010s-present)
- **Black In Jersey** (2021, Trenton) - "Our Voices, Our Perspectives"
- **NJ Urban News** (2018, Newark) - "A Voice for the Voiceless"
- **Public Square Amplified** (2021, Newark) - Grassroots nonprofit newsroom
- **Trenton Journal** (2021) - Solutions-based journalism
- **Five Wards Media** (2021, Newark)
- **Front Runner New Jersey** (2017, Atlantic City)
- **The Newark Times** (2014)

## Geographic coverage

Publications span across New Jersey including:
- **North Jersey:** Newark, Paterson, East Orange, Teaneck, Montclair
- **Central Jersey:** Trenton, Princeton, Plainfield, Somerset
- **South Jersey:** Camden, Atlantic City, Swedesboro

## Working with this data

### CSV exports
The main CSV file contains all publication records:
- `data/publications.csv`

### Individual records
Each publication has its own markdown file in `data/publications/` with structured data.

### External archives
Many publications link to:
- Library of Congress (loc.gov)
- WorldCat (search.worldcat.org)
- Internet Archive (archive.org)

## Potential uses

- Historical research on Black media in New Jersey
- Journalism studies and media history
- Community archiving projects
- Connecting contemporary outlets with historical predecessors
- Mapping the evolution of Black press from print to digital
- Understanding regional media ecosystems

## Data quality notes

- Some dates are uncertain (marked with `?`)
- Historical publications may have incomplete records
- Archive links should be verified for accessibility
- Some publications operated under multiple names over time

## Contributing

If you have information about New Jersey Black publications not included in this database, or corrections to existing records, please open an issue or submit a pull request.

## License

This dataset is made available for research and educational purposes. Please cite the Center for Cooperative Media when using this data.
