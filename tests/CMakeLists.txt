# Copyright 2012, 2013, 2014 CNRS-LAAS
#
# Author: Mathieu Geisert
#
# This file is part of hpp-core hpp-model-urdf is free software: you can
# redistribute it and/or modify it under the terms of the GNU Lesser General
# Public License as published by the Free Software Foundation, either version 3
# of the License, or (at your option) any later version.
#
# hpp-core is distributed in the hope that it will be useful, but WITHOUT ANY
# WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR
# A PARTICULAR PURPOSE.  See the GNU General Lesser Public License for more
# details. You should have received a copy of the GNU Lesser General Public
# License along with hpp-core  If not, see <http://www.gnu.org/licenses/>.

# ADD_TESTCASE(NAME)
# ------------------------
#
# Define a test named `NAME'.
#
# This macro will create a binary from `NAME.cc', link it against Boost and add
# it to the test suite.
#
macro(ADD_TESTCASE NAME)
  add_unit_test(${NAME} ${NAME}.cc)
  target_link_libraries(${NAME} ${PROJECT_NAME})
endmacro(ADD_TESTCASE)

add_testcase(test-successstatistics)
add_testcase(test-distribution)
add_testcase(test-statistics)
