# football-mapper
Project to create 2-d minimap representation of football (soccer) games.

Seth Mize, Lucas Franz, Bryant Cornwell
# Project Description
Most sport broadcasts camera angles provide views from the sides of the playing field but tracking players can be difficult as the camera and views change. Having an additional real-time tracking, overhead view of the field could provide an easier way to study player performances and other game statistics. Our group is interested in using computer vision techniques to recognize football (soccer) objects and mapping the movements into an overhead 2-D space for further event recognition during gameplay. This would involve collecting still images to train an image recognition algorithm for the players, ball, and other related objects. The algorithm can then be used to track object movement in the video. This movement can then be translated to a 2-D overhead space, which can be used to track game progress and events from an overhead view.

- Identify Objects in still image

- Classify objects in still image

- Track object movement in video

- Translate tracking to 2d space*

- Recognize events in the game*
# Reading list
# Research plan and time-line

The first task for this project will be to isolate lines from a still images to identify if the image contains a pitch/field. If the image contains a field, overlay gridlines on the pitch based on dimensions that are provided as parameters of the program. Object detection algorithms for players, ball, etc. can be developed while developing the image grid space. Once the image grid space is determined, positions from object detection relative to the field can be used to mapped into the image grid space. Determine the position of the players on the field based on the provided image grid space and object detection. Using object positions, event detection such as ball possession or (other events) can be explored.    

# Plan for data and experiments
