#Lists

##Easily iterate list
Use `enumerate`:
`>>> list = [1, 2, 3]`
`>>> for index, value in enumerate(list):`
`...     print(f"{index}: {value}")`
`... `
`0: 1`
`1: 2`
`2: 3`

##Comprehension
Generally: [expression] for [variable] in [sequence]

This is computationally faster than a for loop

`# List comprehensions provide concise syntax for creating lists`
`letters = [letter for letter in word]`
