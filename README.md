# explorers
Apple II program simulating the lab vector graphic in the movie Explorers for Hackfest at KansasFest 2021.

## How to Run
```
LOAD LAB.BAS
RUN
```

## How to use
It will ask for a location to start the sphere in x,y,z.  Do each seperately.  So type 100 and hit enter, 50 and hit enter and 2 and hit enter.

- X has a min of 1 and max of 279
- Y has a min of 1 and max of 191
- Z has a min of 1 and a max of 6

Then it will load up the lab _vector graphic_ and you will be able to use the arrow keys to move the sphere up, down, left, and right.  the A and Z keys move the sphere on the Z plane.

# Demo Video on Youtube
https://www.youtube.com/watch?v=wptqLrLxYUE

## TODO
There is still a lot of work to do.  

- The text in the lower right, does not update.  So I need to make that update.  In the movie there is also a lot more text here.
- The sphere should be a different color than the lines in the background.  This just needs to use page 2, and erase as the sphere moves.
- Could change it so that it loads the lab's lines out of visibility from the user and then flip to that page
- Add a title screen
- Add some sounds based on sounds in movie

## Inspiration, thanks, and notes
It is written in Basic and used Beagle Brothers Apple Mechanic to create the sphere shape file and the font text.  Inspiration from Max Piantoni's remake of a scene from A View to Kill (https://www.youtube.com/watch?v=YGVfwEEjRfs) as well as help on how to display text on hires using beagle brothers.
