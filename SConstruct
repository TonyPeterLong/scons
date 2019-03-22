## Construction environment.
env = DefaultEnvironment(tools=['m4'])
env['PLATFORM'] = 'cygwin'
env['ENV']['PATH'] = ['C:/cygwin/bin']

## Construction rules..
SConscript('sources/SConscript', exports = 'env', variant_dir='build', duplicate=0,) # do not copy src files to build 