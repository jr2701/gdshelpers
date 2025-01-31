Changelog
=========

1.2.0
----------
* Added meep integration
* GDSII-export: Added support for LineStrings

1.1.4
-----
* Waveguide: added add_left_bend and add_right_bend to make code easier readable
* added alphanumeric_to_id as an inverse of id_to_alphanumeric
* allow to limit the numbers of workers for parallel export
* fixed oasis export

1.1.3
-----
* Grating coupler: make_traditional_coupler now allows to apodize the period of the grating
* Port: added with_width function to generate a copy of the Port with a certain width
* Increased precision in add_straight_segment by evaluating derivative
* Added add_route_straight_to_port to Waveguide
* Fixed evaluation of width-parameter in add_parametrized_path
* Stopped testing with Python 3.5, as it reached it's end-of-life and added a warning
* Deprecated gdsCAD, as it isn't compatible with Python 3
* Fixed cell.show

1.1.2
-----
* Added scale-parameter to save_image
* fixed .dxf-export in Cell
* Waveguide.add_parameterized_path now also supports an array as path_derivative
* fixed add_dlw_marker, origin can now also be a list

1.1.1
-----
* Removed \_\_future\_\_ imports and (object) in class definitions for Python 2
* create_holes_for_under_etching now allows ovals and rectangles
* add_route_single_circle_to_port now tapers the waveguide to match the width of the port
* Bugfixes

1.1.0
-----
* Added support for slot waveguides and coplanar waveguides
* Direct GDSII-export is now the standard GDSII-writer
* Added function for generating vortex traps
* Improved shape generation performance of waveguide
* Strip to slot mode converter added
* Bugfixes

1.0.4
-----
* Added part for GDSII-import
* Added direct GDSII-export
* Added DXF-export
* bugfixes

1.0.3
-----
* Structures in Cell are now converted individually for pattern export
* annotate_write_fields now works with Cells instead of gdscad.Cells
* fixed some bugs

1.0.2
-----
* Dependencies are now installed automatically

1.0.1
-----
* Project description now visible on PyPI

1.0.0
-----
* Public release
