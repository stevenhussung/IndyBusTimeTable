# To Do List
## Immediate next step:
- Need to find a datatype to store times in. This enables finding the routes, since we have to be able to look for < > in the times.
- After that, we'll want to search each var table = bus_stop_times(0)(i).reverse looking through each stop location to see when the time jumps in the wrong direction.

## Vision:
- Need to create an honest bus route object for whatever the final form of the bus route data will be. 
    - This is essential to refactoring! Otherwise we can't write functions with explicit object types to return the bus route data.
      I think. 
- THEN you can refactor

- Need to figure out the multi-route issue. Currently buses that start mid-route screw up our table.
- Need to transpose the table so that stops appear at the top, each bus-drive appears on one row.
- Will need to figure out the odd/even row shading at some point. (Done!)
- Tiny detail: Is it possible to pull the bay letter out to the stop header, instead of it being in-line? (It changes by day, but never *within* a given day.)