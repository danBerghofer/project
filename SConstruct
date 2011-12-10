env = Environment()  # Initialize the environment
env.SharedLibrary(target = 'libhello.os', source = ['libhello.c', 'hello.h'])
env.Append(LIBPATH = ['/home/dan/cpts224'])
env.Append(CPPPATH = ['/home/dan/cpts224'])
env.Program(target = 'helloworld', source = ['hello.h'])

