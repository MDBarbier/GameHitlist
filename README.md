# GameHitlist

Application for tracking games including features like price alerts and multiple custom lists.

The user will be able to create and name multiple lists (e.g. PC, PC-DLC, PS4, Switch). For PC games the app will check Steam for possible matches and prompt for selection if ambiguous. Once a link to steam app is established it will track price etc. Later will also add similar functionalit for other online stores (Origin, Uplay, Gog, Amazon etc).

The app will be written in Python (3.7) and will use PyQt5 for the GUI. The data will be stored in a sqlite database.

Possibly add backup to google drive or similar later, and export to csv.
