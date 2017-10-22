# Dive into Defold - 2D FOV Field of View

This project shows a way of handling 2D top down Field of View along with distance with many objects. It also shows a way to handle object behavior based on a group type it belongs to. Group objects register with a manager on init, and their data is used by the player object to tell the group objects to change color if they are in the player's FOV.

This could be used for a top down game where you have to avoid guards or cameras. It can also be adapted to platformers if you want enemies to have a cone like field of view for detecting the player.

Online HTML5 Demo: https://www.pkeod.com/defold/2D-FOV-Field-of-View