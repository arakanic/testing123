# testing123
This function takes a list of strings and returns each line prepended by the correct number, similar to an object with numbered keys to values.

number([]) -> []

number(["a", "b", "c", "d", "e"]) -> ["1: a", "2: b", "3: c", "4: d", "5: e"]

number(["", "", "", "", ""]) -> ["1: ", "2: ", "3: ", "4: ", "5: "]
