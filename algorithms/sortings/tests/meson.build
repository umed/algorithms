sources = ['test_sortings.cpp']
test_sortings_exe = executable('test_sortings',
                               sources,
                               include_directories: sortings_headers_dir,
                               dependencies: [
                                   gtest_dep,
                                   gmock_dep
                               ],
                               link_with: sortings_lib)

test('sortings test', test_sortings_exe)
