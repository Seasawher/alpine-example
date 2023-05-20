# alpine-example

## +と-ボタンを持つカウンタ

see: https://codepen.io/Seasawher/pen/abRQXqK

```html
<div x-data="{ count: 0 }">
   <button x-on:click="count--">-</button>
   <span x-text="count"></span>
   <button x-on:click="count++">+</button>
</div>
```
