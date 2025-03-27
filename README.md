# GDLET-code-refactor
The code to change Bing to GDLET and make a timeline based on the output
Here is a list of changes:
1. I changed the search engine to GDLET in the search query.
2. get_gdelt_data() function now returns the entire dataframe, not just URLs.
3. To extract data from URLs, I added a function called get_snippet_from_url (). I used Stack Overflow to extract the data, but Claude AI helped me with the headers.
4. In the gdelt_format_results(),  I changed the input type to a data frame, then converted that to a dictionary with keys as column names and values as values. The snippet is now populated using the get_snippet_from_url () function.
