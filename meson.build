project('libmicrohttpd', 'c')

fs = import('fs')

src_dir = meson.current_source_dir()

fileserver_example_dirs = fs.copyfile(src_dir / 'src' / 'examples' / 'fileserver_example_dirs.c', 'fileserver_example_dirs.c')

fp_translation_map = files('function_pointer_translation_map.json')[0]
