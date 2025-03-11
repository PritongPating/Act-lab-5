# Act-lab-5

def ilang_taon(age):
    
    if age < 0:
        print("Invalid age! wag neg na age par.")
    
    elif age <= 12:
        print("ubing, CHILD.")
    elif age <= 19:
        print("feeling matanda, TEEN.")
    elif age <= 64:
        print("medyo matanda, ADULT.")
    else:
        print("may app ka na, SENIOR.")


print("Welcome sa age classifier dto mo malalman kung anong uri ka ng kupal")

while True:
    try:
        
        boi = input("Ilang taon mo kupal? : ")
        
        ilang_taon(int(boi))
    except ValueError:
        print("wag yang may decimal point!.")
