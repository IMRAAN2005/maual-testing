# SHAIK MAHAMMAD IMRAAN
# 212223100053



## Amazon Manual Testing

This project contains manual testing test cases for the Amazon website.

### Test Cases

[View Test Cases in Google Sheets](https://docs.google.com/spreadsheets/d/1HBCrMPDGjNr3KllQ3siRudYNEWmWURwS3qdphtI7-cY/edit?usp=sharing)

## EPTESTING

https://docs.google.com/spreadsheets/d/1VbvkMAnUs-37PHee11ZsHUVhWdKDs1j3/edit?usp=drive_link&ouid=106271844084758099020&rtpof=true&sd=true


## Python Code (23.09.2026)


- *1 Question*

```python
numbers =  input().split(',')
res=[]
for i in numbers:
    dec = int(i,2)
    if dec%5==0:
        res.append(i)
print(','.join(res))
```

 - *2 Question*

```python
numbers = input().split(',')
res = []

for n in numbers:
    fact = 1
    for i in range(1, int(n) + 1):
        fact *= i
    res.append(str(fact))

print(','.join(res))
```

- *3 Question*

```python

s = input()
letters = 0
digits = 0

for ch in s:
    if ch.isalpha():
        letters += 1
    elif ch.isdigit():
        digits += 1

print("LETTERS", letters)
print("DIGITS", digits)
```
