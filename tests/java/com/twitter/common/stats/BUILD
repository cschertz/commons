# ==================================================================================================
# Copyright 2011 Twitter, Inc.
# --------------------------------------------------------------------------------------------------
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this work except in compliance with the License.
# You may obtain a copy of the License in the LICENSE file, or at:
#
#  http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ==================================================================================================

from glob import glob


java_tests(name = 'stats',
  dependencies = [
    pants('3rdparty:easymock'),
    pants('3rdparty:guava'),
    pants('3rdparty:junit'),
    pants('src/java/com/twitter/common/quantity'),
    pants('src/java/com/twitter/common/stats'),
    pants('src/java/com/twitter/common/stats:time-series'),
    pants('src/java/com/twitter/common/stats:util'),
    pants('src/java/com/twitter/common/testing'),
    pants('src/java/com/twitter/common/util:system-mocks'),
    pants('src/java/com/twitter/common/util:testing'),
  ],
  sources = glob('*.java')
)
