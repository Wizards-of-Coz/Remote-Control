## Project Description

In the experience, Cozmo is a pizza delivery boy in a city made with cardboard props. The city has fun things for Cozmo like an arcade, merry-go-round and an ice-cream parlor, but unfortunately all of that cost money. He earns money by delivering pizza around the city and receiving tips. There are a lot of game elements in the experience, like risk vs reward — Cozmo can deliver pizzas as soon as they are ready or he can wait a little bit more to get one more pizza in order to optimize for time. Although, waiting might lead to the first pizza becoming too cold when delivered, which has an effect on the amount of tip he gets. Cozmo is able to do all of this on his own (0-player), but he is quite slow and inefficient and would often try to catch your attention by throwing a tantrum. You can control Cozmo using a tablet-based remote control (1-player) and make him more efficient and take him to fun places around the city. This can also be played as a competitive multiplayer game where the player to collect most tips wins the game.

## Photos and Video

[https://www.youtube.com/watch?v=aUC0FIL7xog](https://www.youtube.com/watch?v=aUC0FIL7xog)

## Implementation Details

The Cozmo world experience incorporates a lot of the features that the SDK has to offer. The whole experience is built on Cozmo's Computer vision capabilities, we have used custom markers for the same. The vast number of animations that the SDK provides helped us a lot in building a character for Cozmo and highlighting a lot of his personality. We used ``drive_wheels`` instead of ``drive_straight`` as it provides us with more flexibility in terms of changing the speed of the wheels and performing multiple actions while driving. 

## Instructions

There are a few dependencies on other Python libraries for this experience:
Flask is used to create a local web browser for remote control
numpy is used to calculate how far the marker is from Cozmo
PIL is used for adding filters to the images
pygame is used to play background music
Wizards of Coz Common folder found [here](https://github.com/Wizards-of-Coz/Common)

The experience starts once Cozmo sees one cube in front of him. The experience starts in a remote control mode and the browser will open the remote once the experience starts.

## Thoughts for the Future
The Cozmo World experience was a great proof of concept for other developers working with Cozmo. It opens up a lot of possibilities like customizable props and accessories, making other such games which bring out Cozmo’s character in unique ways, and also expanding on Computer Vision to make the robot aware of his surroundings at all times. 
