# {{ name }}

> {{ description }}

```plain
npm i {{ name }}@2.x  # for Vue2
npm i {{ name }}@1.x  # for Vue1
```

```vue
<template>
  <comp :msg="msg"></comp>
</template>

<script>
import Comp from '{{ name }}'

export default {
  components: { Comp },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
```
