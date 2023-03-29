# Paramaterized_Centrifugal_Filter
Parameterized GMSH code of a vertical centrifugal filter

## What is it?
- Here the Hermle Sieva-3 centrfiuge is divided into multiple pieces to be drawn with GMSH in a simplified form.

  ### Assumptions
    - The basket has no thickness (it is drawn as a shell)
    - The outer basket is not drawn
    - The inner basket walls are not drawn, instead the filter mesh is drawn as the wall
    - The filter mesh pores are assumed to be repeating square pores (to check how the pore sizes are adjusted please check the article: and check the source code)
    - Inlet pipe height is modified to fit the application
  
  ### Parts
    - Inlet pipe (in_cyl.geo)
    - The filter mesh (dem_walls_30X_14micronpore_mod_mesh.geo)
    - Top nut that connects the inner basket to the rotating shaft (top_cyl.geo)
    - Conical shape within the centrifuge (cone.geo)
    - The cylindirical part under the cone,the part that is the connection to the bottom of the inner basket (bot_cyl.geo)
    - Top lid of the inner basket (top_disk.geo)
    - The bottom of the inner basket (bottom_disk.geo)
    
