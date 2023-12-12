# Job Listing Collector
This scraper will do the following:
1. Build a web framework using Flask
2. Gather data from the top job search sites using Python
3. Save data in accessible database
4. Serve as a reusable job search tool that's easy to use for the end user

Tools:
- Python
  - BeautifulSoup: Extracts data for analysis
  - Splinter: Allows script user to view page being parsed

Job Sites searched:
- Indeed

Example Output:
![image](https://user-images.githubusercontent.com/31219195/229323037-abe96e83-8d50-4385-a7f1-d24b9e4db36b.png)

What I eventually want this program to do:
- Scrape across multiple major job search & recruiting sites
- Have a user-facing interface that 
  a) asks the desired job title
  b) asks the desired location
  c) scrapes information
  d) visualizes salary statistics (range, average)
  e) provides top keywords and skills listed in the qualifications
