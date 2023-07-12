^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pybind11_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.1.1 (2023-07-11)
------------------
* Switch to ament_cmake_vendor_package (`#24 <https://github.com/ros2/pybind11_vendor/issues/24>`_)
* Contributors: Scott K Logan

3.1.0 (2023-04-27)
------------------

3.0.3 (2023-04-11)
------------------
* Add a modified patch from upstream to support Python 3.11 (`#22 <https://github.com/ros2/pybind11_vendor/issues/22>`_)
* Contributors: Scott K Logan

3.0.2 (2022-12-06)
------------------
* Add missing buildtool dependency on git (`#19 <https://github.com/ros2/pybind11_vendor/issues/19>`_)
* Update maintainers (`#17 <https://github.com/ros2/pybind11_vendor/issues/17>`_)
* Contributors: Audrow Nash, Scott K Logan

3.0.1 (2022-11-02)
------------------
* Force pybind11 to find Python 3. (`#15 <https://github.com/ros2/pybind11_vendor/issues/15>`_)
* Contributors: Chris Lalancette

3.0.0 (2022-09-13)
------------------
* Mirror rolling to master
* Update maintainers (`#14 <https://github.com/ros2/pybind11_vendor/issues/14>`_)
* Update to pybind11 2.9.1.
* Rename patch file for history continuity.
* Contributors: Audrow Nash, Steven! Ragnarök, methylDragon

2.4.0 (2022-03-28)
------------------
* Use sha256 hash instead of tag (`#12 <https://github.com/ros2/pybind11_vendor/issues/12>`_)
* Install headers to include/${PROJECT_NAME} (`#11 <https://github.com/ros2/pybind11_vendor/issues/11>`_)
* Contributors: Shane Loretz

2.3.0 (2022-01-14)
------------------
* Update pybind11 to 2.7.1. (`#10 <https://github.com/ros2/pybind11_vendor/issues/10>`_)
  This is the version that is shipped in Ubuntu 22.04.
* Contributors: Chris Lalancette

2.2.6 (2020-12-10)
------------------
* Update maintainers (`#7 <https://github.com/ros2/pybind11_vendor/issues/7>`_)
* Contributors: Shane Loretz

2.2.5 (2020-08-17)
------------------
* Merge pull request `#3 <https://github.com/ros2/pybind11_vendor/issues/3>`_ from ros2/fix_windows_warning
* remove passing in CMAKE_BUILD_TYPE
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* cleanup
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* do not define CMAKE_BUILD_TYPE on windows
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* suppress all developer warnings
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* suppress warning on windows
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* attempt to fix windows warning
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* Disable building pybind11 tests (`#1 <https://github.com/ros2/pybind11_vendor/issues/1>`_)
  Signed-off-by: Karsten Knese <karsten@openrobotics.org>
* Update to pybind 2.5.0 (`#2 <https://github.com/ros2/pybind11_vendor/issues/2>`_)
  Signed-off-by: Mabel Zhang <mabel@openrobotics.org>
* Create pybind11 vendor package.
  Signed-off-by: Michael Carroll <michael@openrobotics.org>
* Contributors: Karsten Knese, Mabel Zhang, Michael Carroll
