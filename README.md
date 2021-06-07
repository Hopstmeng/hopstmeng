import multiprocessing as mp
import amino

def pl1():
#code

def pl2():
#code

if name == "__main__":
p1 = mp.Process(target=pl1)
p2 = mp.Process(target=pl2)

p1.start()
p2.start()
