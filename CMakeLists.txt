cmake_minimum_required(VERSION 3.10)
project(pybind11_vendor CXX)

find_package(ament_cmake REQUIRED)
find_package(ament_cmake_vendor_package REQUIRED)

find_package(pybind11 QUIET)

ament_vendor(pybind11_vendor
  SATISFIED ${pybind11_FOUND}
  VCS_URL https://github.com/pybind/pybind11.git
  VCS_VERSION v2.11.1
  PATCHES patches
  GLOBAL_HOOK
)

ament_package(CONFIG_EXTRAS_POST "${PROJECT_NAME}-extras.cmake")
