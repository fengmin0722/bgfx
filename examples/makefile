#
# Copyright 2011-2015 Branimir Karadzic. All rights reserved.
# License: http://www.opensource.org/licenses/BSD-2-Clause
#

rebuild:
	@make -s --no-print-directory rebuild -C 01-cubes
	@make -s --no-print-directory rebuild -C 02-metaballs
	@make -s --no-print-directory rebuild -C 03-raymarch
	@make -s --no-print-directory rebuild -C 04-mesh
	@make -s --no-print-directory rebuild -C 05-instancing
	@make -s --no-print-directory rebuild -C 06-bump
	@make -s --no-print-directory rebuild -C 07-callback
	@make -s --no-print-directory rebuild -C 08-update
	@make -s --no-print-directory rebuild -C 09-hdr
#	@make -s --no-print-directory rebuild -C 10-font
#	@make -s --no-print-directory rebuild -C 11-fontsdf
	@make -s --no-print-directory rebuild -C 12-lod
	@make -s --no-print-directory rebuild -C 13-stencil
	@make -s --no-print-directory rebuild -C 14-shadowvolumes
	@make -s --no-print-directory rebuild -C 15-shadowmaps-simple
	@make -s --no-print-directory rebuild -C 16-shadowmaps
	@make -s --no-print-directory rebuild -C 17-drawstress
	@make -s --no-print-directory rebuild -C 18-ibl
	@make -s --no-print-directory rebuild -C 19-oit
#	@make -s --no-print-directory rebuild -C 20-nanovg
	@make -s --no-print-directory rebuild -C 21-deferred
	@make -s --no-print-directory rebuild -C 23-vectordisplay
	@make -s --no-print-directory rebuild -C 24-nbody
#	@make -s --no-print-directory rebuild -C 25-c99
#	@make -s --no-print-directory rebuild -C 26-occlusion
	@make -s --no-print-directory rebuild -C common/font
	@make -s --no-print-directory rebuild -C common/imgui
	@make -s --no-print-directory rebuild -C common/nanovg

metal:
	@make -s --no-print-directory TARGET=5 -C 01-cubes
	@make -s --no-print-directory TARGET=5 -C 03-raymarch
	@make -s --no-print-directory TARGET=5 -C 04-mesh
	@make -s --no-print-directory TARGET=5 -C 05-instancing
	@make -s --no-print-directory TARGET=5 -C 06-bump
	@make -s --no-print-directory TARGET=5 -C 07-callback
	@make -s --no-print-directory TARGET=5 -C 08-update
	@make -s --no-print-directory TARGET=5 -C 09-hdr
	@make -s --no-print-directory TARGET=5 -C 12-lod
	@make -s --no-print-directory TARGET=5 -C 13-stencil
	@make -s --no-print-directory TARGET=5 -C 14-shadowvolumes
	@make -s --no-print-directory TARGET=5 -C 15-shadowmaps-simple
	@make -s --no-print-directory TARGET=5 -C 16-shadowmaps
	@make -s --no-print-directory TARGET=5 -C 18-ibl
	@make -s --no-print-directory TARGET=5 -C 19-oit
	@make -s --no-print-directory TARGET=5 -C 21-deferred
	@make -s --no-print-directory TARGET=5 -C 23-vectordisplay
	@make -s --no-print-directory TARGET=5 -C 24-nbody
