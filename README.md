import datetime

def pawanld():
    a=open("P 26 Pawan dite.txt","a")
    f=input("ENTER WHAT YOU ATE:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(f)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def pawanle():
    a=open("P 26 Pawan exercise.txt","a")
    e=input("ENTER WHAT YOU DID:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(e)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def pawanrd():
    a=open("P 26 Pawan dite.txt","r")
    print(a.read())
    a.close()
    
def pawanre():
    a=open("P 26 Pawan exercise.txt","r")
    print(a.read())
    a.close()


def santoshld():
    a=open("P 26 Santosh dite.txt","a")
    f=input("ENTER WHAT YOU ATE:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(f)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def santoshle():
    a=open("P 26 Santosh exercise.txt","a")
    e=input("ENTER WHAT YOU DID:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(e)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def santoshrd():
    a=open("P 26 Santosh dite.txt","r")
    print(a.read())
    a.close()
    
def santoshre():
    a=open("P 26 Santosh exercise.txt","r")
    print(a.read())
    a.close()


def radhald():
    a=open("P 26 Radha dite.txt","a")
    f=input("ENTER WHAT YOU ATE:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(f)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def radhale():
    a=open("P 26 Radha exercise.txt","a")
    e=input("ENTER WHAT YOU DID:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(e)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def radhard():
    a=open("P 26 Radha dite.txt","r")
    print(a.read())
    a.close()
    
def radhare():
    a=open("P 26 Radha exercise.txt","r")
    print(a.read())
    a.close()


def snehald():
    a=open("P 26 Sneha dite.txt","a")
    f=input("ENTER WHAT YOU ATE:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(f)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def snehale():
    a=open("P 26 Sneha exercise.txt","a")
    e=input("ENTER WHAT YOU DID:")
    a.write("["+str(datetime.datetime.now())+"] - "+str(e)+"\n")
    print("DATA SUCCESSFULLY FED TO THE SYSTEM.")
    a.close()
    
def snehard():
    a=open("P 26 Sneha dite.txt","r")
    print(a.read())
    a.close()
    
def snehare():
    a=open("P 26 Sneha exercise.txt","r")
    print(a.read())
    a.close()
    

print("PLESE TURN ON CAPS LOCK IF ITS NOT.")    
print("PAWAN - 1\nSANTOSH - 2\nRADHA - 3\nSNEHA - 4")
x=int(input("ENTER THE NAME OF THE CLIENT ID:"))

if x==1:
    y=input("TO LOCK DATA ENTER 'L' & TO RETRIEVE DATA ENTER 'R', WHAT DO YOU WANT TO DO LOCK DATA OR RETRIEVE DATA:")
    if y=="L":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            pawanld()
        if z=="E":
            pawanle()
    if y=="R":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            pawanrd()
        if z=="E":
            pawanre()

if x==2:
    y=input("TO LOCK DATA ENTER 'L' & TO RETRIEVE DATA ENTER 'R', WHAT DO YOU WANT TO DO LOCK DATA OR RETRIEVE DATA:")
    if y=="L":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            santoshld()
        if z=="E":
            santoshle()
    if y=="R":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            santoshrd()
        if z=="E":
            santoshre()

if x==3:
    y=input("TO LOCK DATA ENTER 'L' & TO RETRIEVE DATA ENTER 'R', WHAT DO YOU WANT TO DO LOCK DATA OR RETRIEVE DATA:")
    if y=="L":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            radhald()
        if z=="E":
            radhale()
    if y=="R":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            radhard()
        if z=="E":
            radhare()

if x==4:
    y=input("TO LOCK DATA ENTER 'L' & TO RETRIEVE DATA ENTER 'R', WHAT DO YOU WANT TO DO LOCK DATA OR RETRIEVE DATA:")
    if y=="L":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            snehald()
        if z=="E":
            snehale()
    if y=="R":
        z=input("FOR DITE ENTER 'D' & FOR EXCERISE ENTER 'E', WHAT DO YOU WANT TO DO LOCK DITE DATA OR EXERCISE DATA:")
        if z=="D":
            snehard()
        if z=="E":
            snehare()
