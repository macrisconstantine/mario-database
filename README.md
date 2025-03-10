[![image](https://github.com/user-attachments/assets/84a91555-87d9-4565-96d2-752b7700a1e2)](https://macrisconstantine.github.io/mario-database/)
# mario-database
This project's output is a simple database of 5 tables that holds a small collection of data on various Mario characters:
- The `characters` table stores some basic information and `character_id` for each of of the characters in the database.
- The `more_info` table stores additional attribute information about each character (i.e. `height`, `weight`, etc.).
- The `actions` table stores all the possible actions any given character can perform (i.e. `run`, `jump`, etc.).
- The `character_actions` table links characters by `character_id` to the actions they can perform by `action_id`.
- The `sounds` table stores a collection of sounds that can be connected to any of the characters.
## webpage
To visit the webpage, click on the image at the top of this `README.md`.
<br><br>After making the database, I wanted some way to show the data. But GitHub Pages only allows for static sites (no databases allowed). It out that a database can be transformed into a JSON file, which can be fed to an HTML page, even in a static site. So I did this, and was quite happy with the result. 
