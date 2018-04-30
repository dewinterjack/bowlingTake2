## Requirements

* Keep track of score during a game of bowling
* Seperate score into 3 sections: roll1, roll2 & frameScore
* Handle bonuses for strikes and spares accordingly

**Game**

* Frames are stored in an array
* Starts with first frame created
* Stores the current frame in a variable
* Stores a bonus array of frames that need a bonus
* Game total is calculated after the last frame is completed **only**.
* A roll can be made, this will progress the game and take a score.
* A roll will be prevented if it doesn't fit the game rules.
* Game rules will determine if frame enforcement will be applied (must be 10 frames).
* Dev game rules will allow easy testing, so a 3 frame game can be run.

**Frame**

* Stores a value for a roll in variables roll1 and roll2 respectively.
* Bonuses are recorded in roll2 regardless of where earned (Strike will show in roll2).
* Frame score is calculated after a bonus has been applied or a frame is complete.
* Frame score is the total of a frame and every frame before it (game total so far).

*Rules*

* A game must have 10 frames
* A frame can only have 2 rolls except for frame 10 that could have 3.
* A frame cannot exceed 10 pins hit

