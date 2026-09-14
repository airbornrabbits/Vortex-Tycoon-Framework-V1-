# Vortex Tycoon Framework V1

May be buggy, my bad. Still a highly work in progress and it isn't the easiest thing in the world to add items and buttons to but it sets a basis.

MADE BY: AIR_NODE  | 09/14/2026 (14th September 2026)
GUIDE:

Creating Buttons:

A button table to hold all your Buttons.

A key is then required for each Button.

Inside the Button Key you need a: Price, Id, ButtonPart, and NextButtonUnlock value.3.1. Price is the Price of the Button.3.2. Id is the ID of the Button.3.3. ButtonPart is the Button Part in the Workspace.3.4. NextButtonUnlock is the next Button to appear after you buy the Button.

Once you have all of them, give them values and proper naming, make sure you haveall of your references to the objects in workspace correct, and then you should be good to go!

Example:

local Buttons = {Button1 = {Price = 0;Id = 1;

    ButtonPart = Workspace.FloorButton1;
    NextButtonUnlock = Workspace.WallButton1;
};

}

Creating Items:

You need a table called Items

Then you need a key for your Item.

Inside the Item Key you need an: Id, and ItemPart.3.1. Id is the ID of the Item.3.2. ItemPart is the Item object in workspace.

Example:

local Items = {Item1 = {Id = 1; ItemPart = Workspace.Floor1;};

Items can be models as well.
