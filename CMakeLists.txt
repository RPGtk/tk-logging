################################################################################
## The configuration files for the tk-logging project. This requires CMake 
## version 3.10 or higher.
##
## Copyright (c) 2025 - RPGtk Team
## This source code is under the GPLv3. For information on what that entails,
## please see <https://www.gnu.org/licenses/gpl-3.0.txt>.
################################################################################

cmake_minimum_required(VERSION 3.10 FATAL_ERROR)
project("TKLogging" LANGUAGES C VERSION 0.0.0.7)

include(Helpers)
run_checks(ON)
create_target(OFF RAW_SOURCES "TKLogging" OVERRIDE_SHARED ON)
