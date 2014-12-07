cheese-classification
=====================

An Expert System designed to classify a variety of cheeses. Implemented in CLIPS

======================================================
  University of the West Indies St Augustine

  COMP 3850 Assignment 2
  812003287 – Jherez Taylor
  812002149 – Dillon Bhola
  811003468 – Aaron Yuk Low

  Cheese Selection

  wichCheese: The Cheese Expert system.
  This system returns the name and details of a cheese to drink with a meal.
======================================================

Implementation Details
======================================================

The system tries to classify cheese based on the criteria that we (the Experts in this scenario) selected in
order to guide the user towards idenitifying a particular cheese.

The classification types that we have choosen are as follows:

Cheese Type
Texture
Colour
Flavour
Aroma
Common food pairings

We choose these areas because cheese classification is not a field that has fixed agreement and so we found that these characteristics would
yield the best results for identifcation. In addition to these charateristics, we included the country and the milk source which we used to provide more information to the user. There are 30 varities of cheese included in the system. They are as follows:

Gouda
Cheddar
Brie
Parmesan
Mozzarella
Feta
Asiago
Mascarpone
Muenster
Montery Jack
Ricotta
Cottage Cheese
Gorgonzola
Cream Cheese
Danish Blue
Jarlsberg
Provolone
Cantal
Roquefort
Fromage Blanc
Stilton
Explorateur
Reblochon
Castigliano
Caciotta al Tartufo
Innes Button
Brunost
Sapsago
Calcagno
Manchego

The system uses forward chainging to derive the results. The user is prompted with a series of questions for each characteritic to determine
the cheese in question. On system start the facts are loaded into the system, this becomes our Knowledge Base. As the questions supplied by
the system are answered, facts that do not meet the characteristic are removed from the Knowledge Base. This is repeated until a solution is found.
Upon identification of a solution the user is given the full details of the cheese in question (the fact of the cheese). If no solution is found
the user is notified of this and the process is terminated.

Useage
======================================================

To use the Expert System, you will need at least CLIPS version 6.3. Use the navigation window to load the file "wichCheese.clp"
Upon loading the file type the command " (reset) " with the brackes or hit "ctrl + E" followed by " (run) " or "ctrl + R".
Answer the questions while keeping the accepted responses in mind. These accepted responses are displayed alongside each question.
In order to reuse the system simply reset and run once again.


Sources
======================================================

Data on the cheese varieties in the system was pulled from www.cheese.com and http://chefsblade.monster.com/training/articles/980-how-to-classify-cheese?page=1.
