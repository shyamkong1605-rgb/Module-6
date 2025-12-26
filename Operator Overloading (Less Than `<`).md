# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
      class A:
          def __init__(self,a):
              self.a = a
          def __lt__(self,other):
              if self.a < other.a:
                  print(f"\n{self.a} is less than {other.a}")
              else:
                  print(f"\n{self.a} is not less than {other.a}")
      
      a = int(input())
      b = int(input())
      print("\nThe program to demonstrate operator overloading is executing........")
      print("Operator overloading for overloading 'less than (<)' operator......")
      ob1 = A(a)
      ob2 = A(b)
      ob1 < ob2


## Output:
<img width="1919" height="908" alt="503591344-4a484874-e255-4763-8468-703646b4067c" src="https://github.com/user-attachments/assets/fb8133ae-75f2-4594-8882-b605ca25bb85" />
<img width="1919" height="320" alt="503591492-315d96eb-ed2a-4929-863c-0958805189e8" src="https://github.com/user-attachments/assets/89af7f98-7395-4c43-98c0-59ae82e80853" />
## Result:
Thus, The Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class was executed successfully.
