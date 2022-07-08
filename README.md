# python-solutions
#solution to python questions.
from string import punctuation


punctuations = '''!()-[]{};:'"\,<>./?@#$%^&*_~'''" "

work = input("Enter a word or a sentence")

no_punct =""

for char in work:

    if char not in punctuation:

        no_punct = no_punct + char


new = no_punct.lower()

new_2 = new.replace(' ','')

print(new_2)  



list_1 = list(new_2.strip(""))



list_2 = list_1[::-1]


print(list_1)

print(list_2)

if list_1 == list_2:

    print("True")

else:
    print ('false')       
    

