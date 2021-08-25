# Linear-Probing-

## Linear Probing: 
In linear probing, we linearly probe for next slot. For example, the typical gap between two probes is 1 as seen in the example below. 
Let hash(x) be the slot index computed using a hash function and S be the table size 

If slot hash(x) % S is full, then we try (hash(x) + 1) % S
If (hash(x) + 1) % S is also full, then we try (hash(x) + 2) % S
If (hash(x) + 2) % S is also full, then we try (hash(x) + 3) % S 

![image](https://user-images.githubusercontent.com/69696459/130780319-124dabab-c346-4aa5-a052-8cb95277df19.png)
