<template>
  <div :style="{fontSize:'2rem'}" :class="['red',{underline:true}]">
    <input type="checkbox" value="A" v-model.trim="checkList" title="A">
    <input type="checkbox" value="B" v-model="checkList" title="B">
    <input type="checkbox" value="C" v-model="checkList" title="C">
    <p>{{ checkList }}</p>
  </div>
</template>

<script>

export default {
  name: 'MyVue1',
  data() {
    return {
      checkList: [],
    };
  },
};
</script>

<style>
.red {
  color: red;
}

.underline {
  text-decoration: underline;
}
</style>
