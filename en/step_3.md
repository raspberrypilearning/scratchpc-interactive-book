## Make your pages

Once you have the ideas for the story and interactions for your book, you'll need to make the pages.

--- task ---
Decide how many pages you will need for your electronic book. You might have one per backdrop, or just a cover and a single inside page with multiple buttons.

Decide upon what your interaction tool will look like. This is the thing your reader will touch to the pages to activate the book. It might be a magic wand, a star or anything you like!
--- /task ---

Each page needs to have a back and a front made of cardboard, with internal contacts made from aluminium foil - like a sandwich.

--- task ---
Gather or cut the needed amount of cardboard for your book's pages.

![multiple pieces of cardboard in a pile](images/1-get-card.jpg)

If you are using cardboard, you will need to get a back and a front piece cut out for each page you need. If you are using manila folders (or similar items) you can use one per page by simply gluing the foil inside.
--- /task ---

Each page needs to have a simple  design on the front side which relates to what is happening in your book. These designs will be cut out of each page, re-covered with foil and connected to he Raspberry Pi's GP pins to create buttons for your reader to interact with.

--- task ---
Draw the designs you want to have on each page. Keep them fairly simple, as more complex shapes may not work well. You can search online for 'stencil' images to see some good examples. 

![multiple designs drawn on sheets of cardboard](images/2-draw-designs.jpg)
--- /task ---

--- task ---
Once you have drawn all the designs you need on the front side of each page, cut them out using a craft knife or scissors. Make sure you get permission from an adult to use sharp tools.
![cutting out holes using a craft knife](images/3-cut-holes.jpg)
--- /task --- 

--- task ---
Take your F-F jumper cables and remove one of the ends by pulling it using a little force. We want to try and expose the internal core of the wire.
--- /task ---

--- task ---
Turn your cut out image over so you are looking at the back (or the inside of your manila folder). Coat the back side of your picture cut-out with glue, and press the exposed end of the wire to the cardboard, with the F end hanging out toward where the spine of your book will be.

![glue around the edges of the cut hole with a wire pressed into the glue and hanging off the end of the cardboard](images/4-glue-wire.jpg)

--- collapse ---
---
title: I'm making more than one button per page! 
---
If you are making multiple buttons on each page, you must **make sure that your foil pieces are not touching** or you will get a short circuit.

You will also need to add a new wire for each button. Keeping them as close together as you can will make it easier to connect later. 
--- /collapse ---

--- /task ---

--- task ---
Tear off a sheet of foil and place it over the cut out, pressing down firmly to make sure it is stuck all over. 
![cut out hole covered with foil and loose wire taped down to cardboard](images/5-tape-wire.jpg)
Tape down the free end of the wire as close to the spine as you can to keep it from pulling loose.
--- /task ---

--- task ---
Coat the other side of the cardboard page with glue and press it down firmly, to finish the back of the page. 

If you like, you can also tape the edges of your page closed for extra durability.
--- /task ---

--- task ---
Repeat these steps for each of your pages, then bind them together along the spine using strong tape to make a book.
![multiple finished pages of a book with shiny inserts](images/6-repeat-pages.jpg)
![multiple pages of a book bound together on one edge with strong tape to make a book](images/7-bind-spine.jpg)
--- /task ---

Once you have your book completed, you will need to create your interaction tool; which acts as a **common ground** that will close the circuit and 'press the button'. 

In this example I am making a magic wand, but you can cut any shape you like from cardboard to wrap in foil or simply wrap something suitable you find in the recycling.

--- task ---
Cut your desired shape for your interaction tool from cardboard (or recycle some junk!) 
![a pencil and a jumper cable with one end stripped laying on a sheet of aluminium foil](images/8-pencil-foil.jpg)
In the example, I am just going to wrap a pencil in foil.
--- /task ---

--- task ---
Pull the end off an F-F wire and glue or tape it down firmly to your base item, with the free end hanging off toward the user's grip. Wrap the base item in aluminium foil and glue or tape it down.
![a stripped wire taped down to the pencil, being wrapped in aluminium foil with the wire hanging out of one end](images/9-interaction-tool.jpg)
--- /task ---

--- task ---
Connect your pages and interaction tool to your Raspberry Pi's GPIO pins, taking note of which pins you connect to. You could also use some M-F jumper cables to extend your wires and make it easier to use the book.
![a completed electronic book and interaction tool connected to a raspberry pi by many jumper cables](images/10-connect-book.jpg)
In the example, the pages are connected to pins 2,3,4,14 and 15 while the magic wand interaction tool is connected to GND pin 6.
--- /task ---

Once you have your book and interaction tool wired up, it's time to write the code!