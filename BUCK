include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'wykobi', 
  header_namespace = 'wykobi',
  exported_headers = subdir_glob([
    ('', '*.hpp'),
    ('', '*.inl'),
  ]),
  srcs = glob([
    '*.cpp'
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
