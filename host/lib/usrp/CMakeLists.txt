#
# Copyright 2010-2011 Ettus Research LLC
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
#

########################################################################
# This file included, use CMake directory variables
########################################################################
LIBUHD_APPEND_SOURCES(
    ${CMAKE_CURRENT_SOURCE_DIR}/dboard_base.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/dboard_eeprom.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/dboard_id.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/dboard_iface.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/dboard_manager.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/dsp_utils.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/gps_ctrl.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/mboard_eeprom.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/misc_utils.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/multi_usrp.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/subdev_spec.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/tune_helper.cpp
)

INCLUDE_SUBDIRECTORY(dboard)
INCLUDE_SUBDIRECTORY(usrp2)
INCLUDE_SUBDIRECTORY(usrp_e100)
