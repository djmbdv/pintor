project('com.github.djmbdv.pintor', ['c', 'vala'],        version: '0.0.1',
  meson_version: '>= 0.40.0',
)

i18n = import('i18n')
# define GETTEXT_PACKAGE
add_project_arguments('-DGETTEXT_PACKAGE="intltest"', language:'c')
subdir('data')
subdir('src')
subdir('po')

meson.add_install_script('build-aux/meson/postinstall.py')
