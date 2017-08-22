project('vulkan-meson-cpp', 'cpp')
vkdep = dependency('vulkan')
vkhpp = include_directories('vulkan')
executable('sample', 'main.cxx', include_directories : vkhpp, dependencies : vkdep)
