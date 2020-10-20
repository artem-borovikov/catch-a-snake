# Строковые операторы

Чтобы очистить пробелы из строки.

```code 
  message = ' hello! '
  
  # очистка с правой стороны
  # очистка с левой
  # strip() - с обоих концов
  
  print(message.rstrip().lstrip())
  
  # hello!

```
Изменение регистра

```code
  msg = 'hello world'
  print(msg.title()) # Hello World
  
  msg = msg.upper()
  print(msg) # HELLO WORLD
  
  msg = msg.lower()
  pring(msg) # hello world

```
Использование переменных внутри строк
```code
  name = 'user'
  print(f"hello, {name}")


```
