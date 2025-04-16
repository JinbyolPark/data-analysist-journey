# Day 02 - Understanding Variables

## ✅ What I did
- Revisited the basic age calculator
- Focused on understanding what a **variable** is and how it changes
- Used the `age` variable in different expressions (past/future age)

## ✍️ Thought process (EN)
Today I wanted to get a real feel for what a variable actually is.  
I realized that a variable is not just a name for a fixed value—it's a value that can **change depending on context and calculations.**  
By using `age` to calculate past and future ages, I started to understand the idea of “value that changes over time.”

This hands-on approach helped me go from “just assigning a value” to actually **seeing how variables work dynamically.**

## ✍️ 생각 정리 (KR)
오늘은 "변수"라는 개념을 실제로 몸으로 느껴보는 걸 목표로 했다.  
단순히 상자에 값을 넣는 게 아니라,  
그 값이 계산에 따라 바뀌고 다양하게 활용될 수 있다는 걸 직접 해보며 이해하게 됐다.

예를 들어 `age`라는 변수를 만든 뒤,  
`age - 5`, `age + 5` 같은 계산을 해보면서  
“아, 이 값은 시간의 흐름에 따라 변할 수 있는 값이구나” 라는 개념이 실감 났다.

## 📚 Key concepts
Variables can be updated, reused, and calculated

The = sign doesn’t mean “equal” like in math — it means “assign this value to this name”

Variables let you store information and do things with it


## 🧪 Code snippet

```python
print("Hi, this is Age Calculator")
birth_year = input("What year were you born? ")
birth_year = int(birth_year)
age = 2025 - birth_year

print("You are", age,"years old. You are way too young!")
print("You were", age-5, "5 years ago.")
print("And you will be", age+5, "in 2030.")
