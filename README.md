[![image](https://github.com/user-attachments/assets/84a91555-87d9-4565-96d2-752b7700a1e2)](https://macrisconstantine.github.io/mario-database/)
# mario-database
This project's output is a simple database that holds a small collection of tables with data on various Mario characters consisting of 5 tables:
- The `characters` table stores some basic information and `character_id` for each of of the characters in the database.
- The `more_info` table stores additional attribute information about each character (i.e. `height`, `weight`, etc.).
- The `actions` table stores all the possible actions any given character can perform (i.e. `run`, `jump`, etc.).
- The `character_actions` table links characters by `character_id` to the actions they can perform by `action_id`.
- The `sounds` table stores a collection of sounds that can be connected to any of the characters.
## webpage
After finishing the database, I wanted some way to show the database. But GitHub Pages only allows for static sites (no databases allowed). Turns out a database can be transformed into a JSON file, which can be fed to an HTML page, even in a static site. So I did this, and was quite happy with the result. Click on the image at the top of this `README.md`.
