Dependecies

- Scrapy            # For web scraping
- PyGithub          # For GitHub API interactions
- python-dotenv     # For loading environment variables
- PyYAML            # For YAML file handling
- beautifulsoup4    # For HTML parsing
- validators        # For URL validation
- cloc              # For counting lines of code
- requests          # For testing URLs

Ensure you create a .env and within the file, assign the variable GITHUB_TOKEN a Github authentication token, instructions to create one can be found here: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens

Q1: Gets statistics for all Github repositories associated with a specific account. Account is specified by command line argument.

Q2: Gets information about a specific Jira issue. Issue is specified via a url by command line argument.
