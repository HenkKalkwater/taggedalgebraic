project('taggedalgebraic', 'd',
	meson_version: '>=0.50',
	version: '0.11.15'
)

project_soversion      = '0'
project_version_suffix = ''
project_version        = meson.project_version()
project_version_full   = project_version + project_version_suffix

source_root = meson.source_root()
build_root = meson.build_root()
subdir('source/taggedalgebraic')

taggedalgebraic_dep = declare_dependency(
	include_directories: include_directories('source'),
	link_with: taggedalgebraic_lib
)
