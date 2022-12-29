# search-engine
a simple Flask application that allows users to search for documents by entering a query in the URL. The search route handles the search functionality by looping through the list of documents and checking if the query appears in the title or content of each document. If the query is found, the document is added to the list of results. The search results are then rendered in a template along with the search query.