---
title: Blogging Like a Hacker
lang: en-US
---

![](https://s3.bmp.ovh/imgs/2022/07/26/26570030f508dc34.jpg)

## {{ $frontmatter.title }}

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

::: danger STOP
Danger zone, do not proceed
:::

::: details Click me to view the code

```js
console.log("Hello, VitePress!");
```

:::

```html
<ul>
  <li v-for="todo in todos" :key="todo.id">{{ todo.text }}</li>
</ul>
```

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

<script setup lang="ts">
import { useData } from 'vitepress'

const { page } = useData()
</script>

<pre>{{ page }}</pre>
