^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pr2
^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* pr2: changed dependencies on driver metapackages (which no longer exist) to instead depend on particular driver packages (which do)
* updated to remove deprecated package pr2_object_manipulation and replace with moveit_pr2 and laser_drivers and replace with hokoyo_node
* pr2_metapackages: removed dependencies on deprecated packages:
  pr2_gui, camera_drivers, mobile, object_manipulation
* updated maintainers
* Added pr2_apps to dependencies
* Enabled metapackages; removed CATKIN_IGNORE
* Added pr2, pr2_base, and pr2_desktop metapackages
* Contributors: David Feil-Seifer, TheDash
