# Copyright 2019 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# [START cloudrun_system_package_dockerfile]
# Use the Official eclipse-temurin image for a lean production stage of our multi-stage build.
# https://hub.docker.com/_/eclipse-temurin/
FROM eclipse-temurin:17.0.14_7-jre

RUN apt-get update -y && apt-get install -y \
  graphviz \
  && apt-get clean
# [END cloudrun_system_package_dockerfile]
