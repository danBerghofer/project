env = Environment()  # Initialize the environment
env.SharedLibrary(target = 'libhello.so', source = ['libhello.c'])
env.Append(LIBPATH = ['/home/dan/cpts224'])
env.Append(CPPPATH = ['/home/dan/cpts224'])
hello = env.Program(target = 'helloworld', source = ['helloworld.c', 'libhello.so'])
env.Install(dir = "/usr/lib", source = hello)
      
