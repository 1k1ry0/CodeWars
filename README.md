# CodeWars

def toJadenCase(string):
    new_string=''
    for x in range(0,len(string)):
        if x==0:
            new_string=new_string+string[x].upper()
        else:
            if string[x-1]==' ':
                new_string=new_string+string[x].upper()
            else:
                new_string=new_string+string[x].lower()
    print(new_string)

toJadenCase('ABc nsd NWW')

bestPractice

def toJadenCase(string):        
    return " ".join(w.capitalize() for w in string.split())
    
    ----------------------------------------------------------------------------------------------------------------------------------
    
