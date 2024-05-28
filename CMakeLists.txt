#
# SPDX-License-Identifier: Apache-2.0
#

add_subdirectory_ifdef(CONFIG_SST25, src)

#include(${ZEPHYR_BASE}/drivers/flash/spi_nor.h)