# Port-Container-

This program simulates how a shipping port handles containers and ships. Containers unloaded from trucks are stored temporarily in a stack (last in, first out). Ships waiting at the dock are kept in a queue (first in, first out).

Process Overview

1. Store Container – Enter container details (ID, description, weight) and it is added on top of the stack.


2. View Containers – Displays all containers from the top of the stack down to the bottom.


3. Register Ship – Enter ship information (name and captain) and it is placed at the end of the queue.


4. View Ships – Shows all ships in order, from the front of the queue to the rear.


5. Load Next Ship – The top container is removed from the stack and loaded onto the first ship in the queue. Both are then taken out of the system.



This setup reflects how ports operate: containers are handled in the order they arrive (stack behavior), while ships are served in the order they dock (queue behavior).

