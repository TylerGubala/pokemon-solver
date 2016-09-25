# pokemon-solver
The purpose of this is to generate solutions to battle scenarios in the pokemon game.

src is the directory to the source code. Source is c++, written using Qt Creator.

build are built applications. The application is a GUI interface which will allow you to create teams of pokemon, edit their stat spreads, and then calculate a winrate, in percentage form, against possible opposing team builds.

database is the location of the XML database that the application uses. The goal here is to have a format that is extensible, easy to read, and easy to change. Hopefully, through utilizing different versions of the XML database, the application can be changed by a person with little knowlege of C++ on-the-fly.
