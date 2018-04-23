^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pr2
^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.2 (2018-04-22)
------------------
* fixed spelling of hokuyo
* Contributors: David Feil-Seifer

1.1.1 (2018-04-22)
------------------
* updated changelogs
* updated maintainer, updated changelog
* pr2: changed dependencies on driver metapackages (which no longer exist) to instead depend on particular driver packages (which do)
* updated to remove deprecated package pr2_object_manipulation and replace with moveit_pr2 and laser_drivers and replace with hokoyo_node
* pr2_metapackages: removed dependencies on deprecated packages:
  pr2_gui, camera_drivers, mobile, object_manipulation

1.1.0 (2018-03-17)
------------------
* 1.0.1
* updated maintainers
* Added pr2_apps to dependencies
* Enabled metapackages; removed CATKIN_IGNORE
* Added pr2, pr2_base, and pr2_desktop metapackages
* Contributors: David Feil-Seifer, TheDash
