# program-to-compute-the-number-of-characters-words-and-lines-in-a-file.
f = open("D:/a.txt", "r")

char_count = 0
word_count = 0
line_count = 0

for line in f:
    line_count += 1
    char_count += len(line)
    word_count += len(line.split())

f.close()

print("The no. of characters is:", char_count)
print("The no. of words is:", word_count)
print("The no. of lines is:", line_count)


Output:
The no. of characters is: 27
The no. of words is: 5
The no. of lines is: 2

