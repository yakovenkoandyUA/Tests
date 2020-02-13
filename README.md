
### Task 2

```

const letter = document.querySelectorAll('.zA');
let b = 1;
letter.forEach(item => {
  if(b%3 == 0){
    item.style.display = "none";
  }
  b++;
})
```