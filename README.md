Dual Mesh
=====================

This Blender plugin generates the "dual" of a given mesh. Tested with Blender 2.74.

Dual meshes replace each vertex with a face and visa vera.

Installation
------------
Install Blender, then put `add_dual_mesh.py` in your plugins directory location is listed here. Restart Blender, then go to `File > User Preferences > Addons`, and search for the Dual Mesh plugin, enabling it.

Uninstalling
------------

Delete the files added in installation.

Usage
-----

Select any mesh, then press space to list all operators. Run the "Add Dual Mesh" operator from the operator list.

Enabling "Preserve Boundary" will add extra vertices so that edges with a single face remain unchanged.

Enabling "Use Blending" creates a mesh that smoothly blends between the original mesh and the dual, so have one face for every vertex, face and edge in the original mesh. Blending can be done either by the operator, or using shape keys, allowing Blender to directly control the transition.

Additionally, blended meshes use 3 different material groups to mark if the face was originally from a vertex, face or edge.

Further reading can be found at <http://mathworld.wolfram.com/DualPolyhedron.html>

License
-------
This code is licensed under the MIT License copyright Adam Newgas 2015.

