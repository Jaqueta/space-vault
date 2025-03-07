### Shock
Deals 1 [[True Damage]] per second to the target per Stack, then reduces the amount of Shock Stacks by 10. After the stacks are reduced, creates an lightning arc between itself and the closest unit that also has shock, up to a distance of 3 unit radius, this arc will damage and apply Shock to Spaceships that are hit by this arc, equal to 40% of the sum of the Shock Stacks of both units that created the arc (Rounded Up). 

![[Shock Status Effect Behavior.png]]

> In this example, the Spaceship **A** connected with the **B**, creating a damage Arc in-between them that has hit **E** that has 40 Shock Stacks. This happened in this order:
> 
> > Spaceship A received 10 True Damage and is now at 0 Stacks.
> 
> > Spaceship B received 40 True Damage, and is now at 30 Stacks.
> 
> > Spaceship A and B are within range of each other, so they created an Arc in-between them that of `(0+30) / 2 DMG = 15 DMG`
> 
> > Spaceship E was hit by this Arc, so it received 15 True Damage, and is has also received 15 Shock Stacks. This Damage was dealt by the Arc itself, and not the Shock Stacks applied, on the next Shock Tick, it will receive another 15 Damage due to having 15 Stacks (Which can also create Arcs by itself).

