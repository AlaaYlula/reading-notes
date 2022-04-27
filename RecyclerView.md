# RecyclerView
* Use it to create dynamic list.  
* RecyclerView reuses the view for new items that have scrolled onscreen which improves performance, improving your app's responsiveness and reducing power consumption.  
  
### Key classes  
To build the dynamic list need:
* RecyclerView holds multiple elements, each element is defined by a view holder object.  
  
### Steps for implementing your RecyclerView
* What the list or grid is going to look like.  
* Design how each element in the list is going to look and behave.  
* Define the Adapter that associates your data with the ViewHolder views.
  
### Plan your layout
* The items in the list arranged by LayoutManager.
* The common layout:  
1. LinearLayoutManager arranges the items in a one-dimensional list.   
2. GridLayoutManager arranges all items in a two-dimensional grid.   
3. StaggeredGridLayoutManager is similar to GridLayoutManager, but it does not require that items in a row have the same height (for vertical grids) or items in the same column have the same width (for horizontal grids). The result is that the items in a row or column can end up offset from each other.  
  
### Implementing your adapter and view holder
The **ViewHolder** is a wrapper around a View that contains the layout for an individual item in the list. The **Adapter** creates ViewHolder objects as needed, and also sets the data for those views. The process of associating views to their data is called binding. 

Resources: [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview#java)   