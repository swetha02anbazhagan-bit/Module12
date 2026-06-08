# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
stack = []
for i in range(3):
value = input(f"Enter value {i + 1}: ")
stack.append(value)
top_element = stack[-1]
print("Top element of the stack is:", top_element)



## Output
<img width="607" height="253" alt="image" src="https://github.com/user-attachments/assets/ca336f0a-4afa-4a08-b2ea-1761cbe5e235" />

## Result
Thus, the program has been execueted successfully.
