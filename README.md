# Notion-Bookshelf 

This project lets you create a digital bookshelf of books you've finished reading, are reading or even the ones you are interested in reading.  
It is written in Python and is built using [Notion API](https://developers.notion.com/) and [Google Books API](https://developers.google.com/books).

## Set up instructions

I have used Jupyter Notebook for organizing, running the Python code.

1. Create an account on notion.so
2. Import Notion's [reading list template](https://www.notion.so/templates/notion-reading-list) and add a few books to the reading list so we have data to pull and update.
3. Create a new integration on https://www.notion.so/my-integrations. This would give you a secret key that you will need for your notebook.
4. Go to the reading list you created using the Notion template and grant access to your integration using share option on the page.
5. Get the URL to the Reading list page, the 32 character alphanumeric id in your page URL is your database ID that you will need for using the provided Jupyter Notebook.
6. Plug in the secret key and database ID in the parameters section of the Notebook.
7. Google Books API used in this Notebook is the public search endpoint which don't need authentication.
