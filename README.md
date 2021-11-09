# HW03 Ebay Web Scraping

[Homework Instructions](https://github.com/mikeizbicki/cmc-csci040/tree/2021fall/hw_03)

### What does the Ebay.dl file do?

This file generates a url with the `search_term` argument, and then it uses the url and downloads the first ten pages of`search_term`. It then creates a list of dictionaries that contain information on each item, like its cost, its shipping, the free returns status, etc.

### How do you Run the ebay.dl File?
You can type in the `search_term` the specific item you want information on, and then enter the number of pages of that item you want analyzed by replacing x with that number.

    python3 ebay.dl 'search_term' --num_pages=x
    
**The command lines to receive my specific json files look like this:**

For hammer.json:

    python3 ebay.dl 'hammer'
    
For screw.json:

    python3 ebay.dl 'screw'
    
For smart watch.json:

    python3 ebay.dl 'smart watch'
    
