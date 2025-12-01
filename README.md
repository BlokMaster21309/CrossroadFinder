# CrossroadFinder
Finds different crossroad formations on a set seed.
Works for 1.7-1.18.2+

# Input parameters
**Version** - the closest version smaller or equal to the one you are using  
**Seed** - the nether structure seed in numeric form, usually the same as the overall world seed  
**Fortress salt** (only for 1.16.1+) - Set the custom salt, leave empty for the vanilla value  
**Crossroad shape** - the shape you want to find crossroads in, see next section of a list  
**Max Y** - only show crossroads below this Y level  
**Search radius** - search radius in blocks  
**Search center** - block position of the search center  

# Shapes
"+" is a crossroad "O" is anything else, including empty space or orther fortress parts. 
Each also include the rotations and reflections of the shapes shown.

**Double**  
++

**TRI_LINE**  
+++

**QUAD_LINE**  
++++

**QUINT_LINE**  
+++++

**TRI_CORNER**  
++  
+

**QUAD_CORNER**  
+++  
+

**QUINT_CORNER**  
+++  
+  
+

**QUAD_SQUARE**  
++  
++

**QUINT_BLOB**  
+++  
++

**QUINT_C**  
+++  
+O+

**QUINT_Z**  
++  
O+  
O++

**QUINT_H**  
+O+  
+O+  
+


# Building
Clone the repo and run the command from `compile.txt`
