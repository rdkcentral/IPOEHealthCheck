################################################################################
#
# If not stated otherwise in this file or this component's LICENSE file the
# following copyright and licenses apply:
#
# Copyright 2020 Sky
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
################################################################################

bin_PROGRAMS = ipoe_health_check

ipoe_health_check_CFLAGS = -DFEATURE_SUPPORT_RDKLOG $(SYSTEMD_CFLAGS)
ipoe_health_check_SOURCES = ihc_core.c ihc_main.c
ipoe_health_check_LDFLAGS = -lccsp_common -lrdkloggers -lnanomsg -lsysevent
ipoe_health_check_CFLAGS +=  -DGIT_VERSION=\"$(GIT_VERSION)\"
