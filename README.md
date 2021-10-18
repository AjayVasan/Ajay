# Ajay
#Python  turtle BG color flasher


import turtle

import time

def bgcolor():
    
    c=["#9e0000","#63a9ff","#ff0000","#2b2b2b","#12d0de","#85299e","#ff0095","#FF7F50","#8f138f","#aeb36d","#4db094","#e05d2e","#c7b365","#00ffe5","#c800ff","#ff0090","#3e7800","#ff0048","#cf6700"]
    
    speed=turtle.speed(0.1)

    while 1:
        i=0
        for z in range(len(c)):
            time.sleep(0.1)
            w=turtle.Screen()
            w.bgcolor(c[i])
            i+=1
            
bgcolor()
