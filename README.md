# Google Search

Google search from Python.

A fork of MarioVilas' [googlesearch](https://github.com/MarioVilas/googlesearch) that adds result title and description
in addition to result url.

## Usage example

    # Get the first 20 hits for: "Breaking Code" WordPress blog
    from googlesearch import search
    for result in search('"Breaking Code" WordPress blog', stop=1):
        print(result)

    # {'title': 'Breaking Code - WordPress.com  breakingcode.wordpress.com', 'url': 'https://breakingcode.wordpress.com/', 'description': 'Blog at WordPress.com.Do Not Sell or Share My Personal Information. Follow Following. Breaking Code. Join 37 other followers. Sign me up.'}

## Installing

    pip install git+https://github.com/sabitm/google-search-py
