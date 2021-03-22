# Spoken To Written
This is a Python module which can that can convert a paragraph of spoken english to written english.

For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.

# ans.py
Code for the above statment , was taken from https://github.com/vishaldhiman28/Spoken-To-Written-English

# with_add_rule.py
The above code is modified in such a way that we can add new rules.
we have to pass rules in as 3 different variables like , for suppose we need to add a rule Numbers:{hun:100} we need to pass it as Numbers,hun,100 to the function Add_rule which will access the method rule in the class SpokenToWritten.
