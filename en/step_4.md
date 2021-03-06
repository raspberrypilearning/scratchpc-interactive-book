## Code and test

Now it's time to make the digital part of your book. Start small, and add more to your project if you have time.

**Tip:** Remember to test your project each time you add something. It's much easier to find and fix bugs before you make more changes.

--- task ---
First, open a new project in Scratch on your Raspberry Pi and add the `Simple Electronics`{:class="block3extensions"} extension to your project.
--- /task ---

--- task ---
You will need to decide what order to build your book. To get started, you could:
- Create all the pages as backdrops, or
- Get one page working first
--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
You may not have time to add everything you want to your book. That's okay, you can always come back to it later. 
</p>

--- task ---
If you have completed the Scratch 1 pathway, you will have collected some very useful skills. If you haven't yet completed that pathway, you should do it next! 

Here's a reminder to help you make your electronic book: 

Code:

[[[scratch3-changing-backdrops-pages-levels]]]

[[[scratch3-change-costumes-to-show-mood]]]

[[[scratch3-animate-movement-costumes]]]

[[[scratch3-graphic-effects]]]

[[[scratch3-show-hide-sprites-backdrops]]]

[[[scratch3-positioning-with-layers]]]

[[[scratch3-jiggle-a-sprite]]]

Paint editor – backdrops and costumes:

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

Sound: 

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

Editor:

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]


--- /task ---

--- task ---

**Test:** Show someone else your project and get their feedback. Do you want make any changes to your book? 

--- /task ---

--- task ---

**Debug:**

You might find some bugs in your code that you need to fix. Here are some common bugs:

--- collapse ---

---
title: My sprite is showing or hiding on the wrong pages
---

Check that the sprite has `when backdrop switches to`{:class="block3events"} scripts with `show`{:class="block3looks"} or `hide`{:class="block3looks"} as needed. Check that you have chosen the correct backdrop name in the `when backdrop switches to`{:class="block3events"} scripts. It helps to give backdrops good names to help spot problems like this.

--- /collapse ---

--- collapse ---

---
title: My sprite is going upside down
---

Add a `set rotation style left-right`{:class="block3motion"} or `set rotation style don't rotate`{:class="block3motion"} block.

--- /collapse ---

--- collapse ---

---
title: My sprite 'jumps' when it changes costume or bounces
---

Make sure that the costume is centred in the Paint editor (line up the blue cross with the cross hairs in the centre of the Paint editor).

--- /collapse ---

--- collapse ---

---
title: My sound does not play
---

Have you added a block to `play sound`{:class="block3sound"} when the sprite is clicked? If you have copied code from another sprite, you will need to add the sound to this sprite from the **Sounds** tab. Check the volume on your computer and make sure that you have not lowered the volume with code — try `set volume to`{:class="block3sound"} `100`.

--- /collapse ---

--- collapse ---

---
title: More than one thing is happening at a time
---

You may have a short circuit between two contacts. Somewhere in the faulty page, your foil or wires are touching and activating at the same time.

Alternatively, you may not have selected the right number for your pins in the code. Go back and check that all your `When button [ ] pressed`{:class="block3extensions"} blocks have the right values for the pins you are connected to.

--- /collapse ---

--- collapse ---

---
title: Nothing happens when I touch the tool to a contact
---

You may not have a good connection to the foil inside the page or your tool. Check the connection from the wire to the foil is clear in both cases — sometimes too much glue can insulate your wire!

Alternatively, you may not have selected the right number for your pins in the code. Go back and check that all your `When button [ ] pressed`{:class="block3extensions"} blocks have the right values for the pins you are connected to.

--- /collapse ---


--- /task ---

Once you have created the code and interactions for your book and know it is working the way you want, you can upgrade your project and share it with friends and family!

--- save ---
