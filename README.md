## Introduction
Inventory system from S.T.A.L.K.E.R.: Call of Pripyat with all the basic mechanics on UE4. In addition to the basic features, a system for developing weapon mechanics has been prepared. 

## Requirement
These requirements must be met before you start: <br>
Before you start, if your version of Unreal Engine is less than 4.27, install it at this link [Unreal Engine 4.27](https://www.epicgames.com/site/en-US/news/unreal-engine-4-27-is-now-available)

## Getting Started
1. Install the required version of the engine (if required)
2. Select the folder to clone the project
3. Open GitBush and write this command
```
git clone https://github.com/akiroqw/inventory_system.git
```
or you can do it with the IDE you are working in.

## Restrictions
Inventory can be extended with new functions, logic, etc. But you should expect that when adding new items, you need to remember to have a list of items for this.
You can see the file: `Content\Inventory\Structures\S_ItemDetails`.<br>
In addition, the project has not implemented a system of weight of items for the UI. You can see the weight system in this component: `Content\Inventory\Components\InventoryComponent`.<br>
But for it to work correctly it must be implemented in the inventory UI itself: `Inventory\UI\WB_Inventory`
