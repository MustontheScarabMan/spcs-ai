Sonancia
Sonancia is an Artificial Intelligence created for the purpose of procedural content
generation and sonification within the levels generated. First off the program uses
algorithms to generate levels, assignning a value to the level based on factors of
how many rooms can not be accessed and how many rooms the player must traverse through
to reach the end. Then using two other algorithms, the program proceeds to assign
sound to each of the rooms. With a large bank of instruments at varying intensities,
the instrument-based sonification algorithm selects an sound file in a roulette
fashion, giving a higher probabilty of being selected to instruments that have not
been used in the level yet. Once the selection is made, that specific file is removed
from the roulette to minimize redundancy and the probability of the same instrument
being selected is reduced by 50%, the newly opened distribution is then evenly
distributed between all the other potential files on the roulette. Afterwards, the
intensity-based sonification algorithm takes the intensity of the sounds to order them
such that the intensity is lower near the start and higher as the player approaches
the end of the level. By doing this the program generates a level for a horror game
so that the player will have a tense, but new experience every time they play the
game. Not only that, but sound, which is vital in horror games to set the mood, will
not grow redundant and keep the experience of the game fresh for the player most of
the time. Written by Phil Lopes, Antonio Liapis, and Georios N. Yannakakis, the design
of this program aligns nicely with a large proportion of the audience as it adds
replayability to the game and maintains the high tension and anxiety that most horror
game players look for. Also, if they do implement the ability for players to add sounds
to the database, it will allow for customization and an ever evolving game which will
present a new experience every time one were to play it. For now the system of
sonification seems to be knowledge based as it uses a static set of values to determine
a generalized output that will suit the situation. The procedural content generation also
seems to be knowledge based as it creates a map within a set of rules. If the developers
decide to implement the idea of user inputted sound files as well, then a statistical
approach would be necessary to determine the intensity of the sound and the instrument
used to generate the sound. For now though, the system works with a bank of data where
the intensity and instruments are inputted with predetermined values evaluated by people.
The system assumes the player will not dawdle as they go through the level as the sound
file loops in the background while a player is idle, but in the future there seems to be
potential plans to set up a time rule to create a new mix after a set time of inactivity.
Also, the system assumes that the player will have the desired reaction from listening to
mix that the system generates. If they implemented the system that allowed users to input
their own sounds, there is potential for harrassment if these sound files are used
publicly. If someone were to upload an inappropriate sound file, such as a happy tune,
if this sound came up in someone else's game, it may disrupt the experience and break the
imerssion. Overall Sonancia seems like an interesting program and I look forward to seeing
how it develops in the future.



Bibliography
http://www.ccgworkshop.org/wp-content/uploads/2015/06/CCGW2015_submission_4.pdf
http://www.creativeai.net/posts/u5tGaxYdk8pBz4hRr/sonancia