# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2018 Marvell International Ltd.
# Copyright(c) 2018 Semihalf.
# All rights reserved.
#

dep = dependency('libmusdk', required: false, method: 'pkg-config')
if not dep.found()
	build = false
	reason = 'missing dependency, "libmusdk"'
	subdir_done()
endif

ext_deps += dep

sources = files('mvep_common.c')
