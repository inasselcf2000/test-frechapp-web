# test-frechapp&web
# Description:

The tutorial offers a set of missions for new players in the multiplayer mode. The goal is simple: reach the finish line of the race using the provided data. The tutorial has multiple levels, ranging from the Wood League to the Silver League. Each level introduces new parameters to manage.

# Code proposed:

The proposed code is a game loop that uses the input data to calculate the target position and the power to apply to the ship to reach the next checkpoint.

The game starts with an infinite loop that reads the input data at each iteration. The provided data is the current position of the ship (x and y), the position of the next checkpoint (nextCheckpointX and nextCheckpointY).

The distance between the ship and the next checkpoint is calculated using the Euclidean distance formula. The angle between the ship and the next checkpoint is also calculated.

The power to apply to the ship is calculated based on the distance to the next checkpoint. The farther the distance, the greater the power. The power is limited to a maximum of 100 and a minimum of 0.

The target position is defined as the position of the next checkpoint.
