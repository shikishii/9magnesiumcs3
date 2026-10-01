## Design Revision
Changes from my previous design:
-
No major changes were needed from my original design.

## Decide what is Public or Private

| Attribute | Data Type | Visibility | Why Public/Private? |
|---|---|---|---|
| display | string | **Public** | other parts of the game need to display the item |
| amount | int | **Private** | the amount should only change when items are collected or removed |
| description | string | **Public** | the player needs to be able to view the item's description |
| capacity | int | **Private** | the inventory should control how many items it can hold |
