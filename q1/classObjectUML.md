# SG4 - Understanding Classes and Objects
## Inventory
## Displays the inventory's items in-game, and allows the user to place items in the inventory and remove it in-game.
## Properties

| Property | Data Type | Description |
|---|---|---|
| display | string | displays the items |
| amount | int | amount of each items |
| description | string | displays detailed description of each individual item |
| available | boolean | indicates if the item is inside the inventory |

| Method | Description |
|---|---|
| separate | separates grouped items |
| edit  | edits the placement of the items in the inventory |
| throw | throws the items away to clear out your inventory | 
| collect  | collects the items dropped by exploration in-game |

## Class Diagram
![Class Diagram](images/classDiagram.png)
## Design Explanation
### I chose this because I love games and I wanted to show basics of inventories.
### The display is the most important because one should see the items at first glance so that the gameplay is smooth and uncomplicated.
### The method collect is the most important out of all because what is the use of an inventory when you can't store items.
