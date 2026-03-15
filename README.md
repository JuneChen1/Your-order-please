# Codewars-Your order, please (Javascript)

```
function order(words){
  const result = [];
  words = words.split(' ');
  for (let i=1; i<=words.length; i++){
    let item = words.filter(word => word.includes(i.toString()));
    result.push(item[0]);
  };
  return result.join(' ');
}
```

[KATA](https://www.codewars.com/kata/55c45be3b2079eccff00010f/javascript)
