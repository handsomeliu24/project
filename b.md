```python
# 範例程式：計算兩個數字的和

def add_numbers(a, b):
    """
    傳回兩個數字的和
    """
    return a + b

# 主程式
if __name__ == "__main__":
    num1 = float(input("請輸入第一個數字: "))
    num2 = float(input("請輸入第二個數字: "))
    result = add_numbers(num1, num2)
    print(f"兩個數字的和是: {result}")
```