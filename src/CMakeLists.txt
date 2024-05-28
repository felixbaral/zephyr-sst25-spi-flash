#
# Created by Hannes Gebauer
# Copyright (c) 2023 HEAVN GmbH
#
# SPDX-License-Identifier: Apache-2.0
#

zephyr_library()

# zephyr_library_sources_ifdef(CONFIG_SST25 src.c)
zephyr_library_sources_ifdef(CONFIG_SST25, src.c)
zephyr_library_include_directories(${ZEPHYR_BASE}/drivers/flash)