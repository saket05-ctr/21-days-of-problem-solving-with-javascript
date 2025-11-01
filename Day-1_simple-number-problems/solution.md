### 1. Print Numbers from 1 to N

```
const num = 100

for (let i = 1; i<=num; i++){
    console.log(i)
}

```

---

### 2. Print Numbers from N to 1 without changing the loop condition of above question

```
const num = 100

for (let i = 1; i<=num; i++){
    console.log(num-i+1)
}
```

---

### 3. Print All Even Numbers from 1 to N

```
const num = 100

for (let i = 1; i<=num; i++){
    if (i % 2 === 0){
        console.log(i)
    }
}

```

---

### 4. Sum of First N Natural Numbers

```
const num = 5
let sum = 0
for (let i = 1; i<=num; i++){
    sum = sum+i

}
console.log(sum)

```

---

### 5. Product (Factorial) of N

```
const num = 5
let sum = 1
for (let i = 1; i<=num; i++){
    sum = sum*i

}
console.log(sum)
```

---

### 6. Sum of All Even Numbers up to N

```
const num = 10
let sum = 0

for (let i = 1; i<=num; i++){
    if (i % 2 === 0){
        sum = sum + i
    }
}
console.log(sum)

```

---

### 7. Print Squares of Numbers from 1 to N

```
const num = 10

for (let i = 1; i<=num; i++){
   console.log(i*i)
}

```

