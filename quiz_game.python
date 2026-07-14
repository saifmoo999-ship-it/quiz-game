from rapidfuzz import fuzz
print("welcome to my computer quiz ")

playing = input("do you want to play? ")

if playing.lower() != "yes" :
    quit()

print("ok let's play ")
result = 0


correct_answer = "graphics processing unit"

answer = input("What does GPU stand for? ")

score = fuzz.ratio(answer.lower().strip(), correct_answer)

if score >= 75:
    print("Correct!")
    result += 1
else:
    print("Incorrect!")

print(f"correct")

from rapidfuzz import fuzz

correct_answer = "random acsess memory"

answer = input("What does ram stand for? ")

score = fuzz.ratio(answer.lower().strip(), correct_answer)

if score >= 75:
    print("Correct!")
    result += 1
else:
    print("Incorrect!")


from rapidfuzz import fuzz

correct_answer = "power supply"

answer = input("What does ps stand for? ")

score = fuzz.ratio(answer.lower().strip(), correct_answer)

if score >= 75:
    print("Correct!")
    result += 1
else:
    print("Incorrect!")

print(f"Similarity: {score}%")

print("you got "+ str(result) + " right question/s")
print ("ypu got " + str((result/3)*100) + "%")


 