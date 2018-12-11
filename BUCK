load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'replxx',
  header_namespace = '', 
  exported_headers = subdir_glob([
    ('include', '**/*.h'), 
    ('include', '**/*.hxx'), 
  ]), 
  headers = subdir_glob([
    ('src', '**/*.h'), 
    ('src', '**/*.hxx'), 
  ]), 
  srcs = glob([
    'src/**/*.cpp', 
    'src/**/*.cxx', 
  ]), 
  visibility = [
    'PUBLIC', 
  ],  
)
