## Homework for Control Statements (for/while/if/if...else...)

#### EvenlySpreadBeeperRow
- Initial Condition
    - Row length can be any size.
    - Beepers are randomly on the corners
    - There can be at most 2 beepers at a corner
- To Do:
    - Write a program in which Karel spread beepers evenly on the row.
- Restriction:
    - You can use only one **while** loop.
    - Nested loops are **not** allowed.
    - To make sure there is exactly one beeper on each corner, try to use **if** or **if else** statements
- Tests Worlds:
    - EvenlySpreadBeeperRow.W, EvenlySpreadBeeperRow1.W

#### BeeperFinder
- Initial Condition
    - World size can be of any width and height.
    - Karel is on the north-west corner facing south.
    - A beeper will be anywhere on either western wall or southern wall.
- To Do:
    - Write a program in which Karel goes along the walls until it reaches the beeper.
- Test Worlds:
    - BeeperFinder.W, BeeperFinder1.W, BeeperFinder2.w


 #### OneSafeBeeper
 - Initial Condition
     - World size is fixed.
     - Four possible state of the world, see left side of below pic
     - https://github.com/pyiso80/EoBP_02HW/blob/master/OneSafeBeeper.png
 - To Do:
     - For each world on the left side the pic above, Kare must put beepers as shown in the corresponding final state of the world on the right.
 - Test Worlds:
     - OneSafeBeeper.w, OneSafeBeeper1.w, OneSafeBeeper2.w and OneSafeBeeper3.w

#### CarpetingRoom
- Initial Condition
    - Karel **may** be is in front of a room as shown in CarpetingRoom.w (default world).
    - A room is blocked by walls on all sides except on the **south**. A room is only one unit wide on each side. CarpetingRoom.w is a room.
    - If any side/sides other than the south is open, it's not a room. CarpetingRoom1.w, CarpetingRoom2.w and CarpetingRoom3.w are not rooms.
- To Do:
    - Karel must put a beeper if he is in front of a room.
    - Karel must not put a beeper if it is not a room.

- Test Worlds:
     - CarpetingRoom.w, CarpetingRoom1.w, CarpetingRoom2.w and CarpetingRoom3.w

