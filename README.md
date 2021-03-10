# Как можно создать data() в ES6 синтаксисе:
```
Vue.createApp({
    data: () => ({
         ....
    })
}).mount('#app')
```
# Во Vue можно вызывать несколько функции сразу (через запятую):
```
<button @click="remove(index), color()">Удалить</button>
```
