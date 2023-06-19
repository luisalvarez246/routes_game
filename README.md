# routes_game

## What is a path?

According to Wikipedia

> "A path is a string of characters used to uniquely identify a location in a directory structure"

So basically a path could be something like this `"./Desktop/folder_1/image.png"`

The path above would retrieve _image.png_ thas is within a directory named _folder_1_ that is located at _Desktop_.

### Parts of a Path

Now, for the sake of understanding, let's think of paths as rooms. When we access a path, we are basically accessing a room.

In the example above we have 3 rooms:

".", "Desktop", "folder_1"

Where "." is the room where we are currently at i.e. The room from where we are calling our path, we will see more of this later on.

#### How do we enter a room?

:door: this is a door. And basically each forward slash "/" in a path represents a door.

In the path from the example above, we would have something like this:

.:door:Desktop:door:folder_1:door:image.png

This makes it clearer that we are going from our current room (".") to a room called folder_1, and we look for a file called image.png.

Okay, but wait a minute...<br />

We are going from where we are at now, to folder_1, so why do we have to go through Desktop? Let us think about this, with a real world example.
---
##### Example
Imagine you live in the fifth floor of an apartment block 🏢 and you need to go fetch your phone. 
How would you reach your apartment?

Unless you are a Mandalorian with a fancy jetpack, you would have 2 options:
  1. Staircase.
  2. Elevator.

Let us break down our 2 options:

  1. Assuming we are outside the building we would have to enter through the front door. Then find the staircase and go up each floor
  until we reach the fifth floor, then open the door to our home, and pick up the phone.
  
  This path would look something like this:
  
  Street:door:Aparment_Block:door:Floor1:door:Floor2:door:Floor3:door:Floor4:door:Floor5:door:Home:door:get_phone
  
  In this first example:
  
  - Street is where we are currently at, "."
  - As we have mentioned each door is a forward slash.
  - A path in ./Aparment_Block/Floor1/Floor2/Floor3/Floor4/Floor5/Home/get_phone


### Where do we apply these paths nomenclature

Everywhere!

Each time we need to access a file when we are writing code (on any language C, HTML, Javascript, etc.) we use a path to indicate where to look for the file(s)
that are required.

Let's suppose we have the following structure in our repository:









