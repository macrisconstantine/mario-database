# mario-database
This project's output is a simple database that holds a small collection of tables with data on various Mario characters consisting of 5 tables:
- The `characters` table stores some basic information and `character_id` for each of of the characters in the database.
- The `more_info` table stores additional attribute information about each character (i.e. `height`, `weight`, etc.).
- The `actions` table stores all the possible actions any given character can perform (i.e. `run`, `jump`, etc.).
- The `character_actions` table links characters by `character_id` to the actions they can perform by `action_id`.
- The `sounds` table stores a collection of sounds that can be connected to any of the characters.
