# 
const leter = document.querySelectorAll('.zA');
let b = 1;
leter.forEach(item => {
  if(b%3 == 0){
    item.style.display = "none";
  }
  b++;
})