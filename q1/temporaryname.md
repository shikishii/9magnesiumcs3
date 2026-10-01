## Design Revision
Changes from my previous design:
-
No major changes were needed from my original design.

| Attribute | Data Type | Visibility | Why Public/Private? |
|---|---|---|---|
| display | string | **Public** | Other parts of the game need to display the item. |
| amount | int | **Private** | The amount should only change when items are collected or removed. |
| description | string | **Public** | The player needs to be able to view the item's description. |
| capacity | int | **Private** | The inventory should control how many items it can hold. |
