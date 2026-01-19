# Copper Dimension  
This is a dimension with just copper. Here's how it works:  
4 copper blocks on top
1 layer of bedrock on the bottom.

Entering (and you can replace 0 5 0 with the coordinates you want to go to):  
```mcfunction
/execute in copper_dim:copper_dim run tp @s 0 5 0
```

Exiting (and replace -109 72 -92 with where you want to be in the overworld):  
```mcfunction
/execute in minecraft:overworld run tp @s -109 72 -92
```
