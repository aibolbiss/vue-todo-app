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
# Свойство template:
```
Vue.createApp({
    data(){
       return{
          title: 'Hello world'
       }
    },
    template: `
       <h1>{{ title }}</h1>
       <button @click="title='Hello Aibol'">Изменить</button>
    `
}).mount('#app')
```
