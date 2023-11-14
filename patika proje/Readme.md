## Phyton proje anlatımı 
``` def flat(x):
     flatten=[]
    for i in x:
    if type(i)!=list
       flatten.append(i)
    else:
        flatten.extend(flat(i))
    return flatten```