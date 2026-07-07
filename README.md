# Commands for Command_Block.
## likely Key System for door command.  
### if hold (Item) and on (pos) will replace (Blocks) by (fill,pos1-pos2).
```js
execute if entity @a[x=34.48,y=-60.00,z=24.47,r=1,hasitem={item=blaze_rod,location=slot.weapon.mainhand}] run fill 34.53 -60.00 24.47 34.53 -59 24.47 air
```
### if not hold (Item) and not on (pos) will replace (Blocks) by (fill,pos1-pos2).
```js
execute unless entity @a[x=34.48,y=-60.00,z=24.47,r=1,hasitem={item=blaze_rod,location=slot.weapon.mainhand}] run fill 34.53 -60.00 24.47 34.53 -59 24.47 air
```
