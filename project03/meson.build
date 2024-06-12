project('project03', 'c')
libs=meson.get_compiler('c').find_library('thirdinfo', dirs : join_paths(meson.source_root(), 'src/third'))
executable('project03', 'src/main.c', dependencies : libs, include_directories : 'src/include')

