# 2ECEB_Santos-Experiment-1

#ALPHABET SOUP PROBLEM:
#Funtion that takes the possible word inside as a string
def alphabet_soup(text):
    # Sorts the letters of the word in the string in alphabetical order
    return ''.join(sorted(text))

#Inputting Word 
text = input("Enter string: ")
#Output Sentence
print(alphabet_soup(text))



#EMOTICON PROBLEM:
def emotify(words):
    #The Dictionary, Assigning specific words to their specific special characters 

    #Split the inputed sentence into words then replacing the specific words to their assigned special characters in the dictionary 
    emoticons = {"smile":":)", "grin": ":D", "sad": ":((", "mad": ">:("}
    #Returning the edited sentence
    return " ".join(emoticons.get(word, word) for word in words.split())

#Inputing the Sentence 
words = input("Enter an sentence:") 
#Printing the Output with the changes
print(emotify(words))




#UNPACKING LIST PROBLEM:
#List of Integers 
list = [1, 2, 3, 4, 5, 6]

#Getting the first, middle, and last elements of the list of Integers
first = list[0]
middle = list[1:-1]
last = list[-1]

#Output of elements
print("first:", first , "  middle:",middle, " last:",last)
    



