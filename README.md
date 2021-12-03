# working_with_apis

# General info
These programs generate a visualization based on data that it retrieves.  We use web APIs to automatically request specific information from a website -- rather than entire pages -- and then use that information to generate a visualization.

The first project, `python_repos_visual.py` looks at the popularity of Python projects on GitHub and then makes an interactive bar chart to show the number of stars the project has acquired as well as the name of the repository.  We create this bar chart visualization using a Python library named Plotly.

The second project, `hn_submissions.py` looks at the top articles on Hacker News.  Then we build a dictionary for each article and print the title, discussion link and comments.

# Sources
https://api.github.com/search/repositories?q=language:python&sort=stars

https://developer.github.com/v3/

https://hacker-news.firebaseio.com/v0/topstories.json
