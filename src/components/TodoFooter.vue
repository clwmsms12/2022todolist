<template>
  <div class="clearAll" @click="$emit('clearAll')">
    전체삭제
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .clearAll{
    display: flex;justify-content: center;align-items: center;
    background: orange;
    color: white;
    height: 35px;
    border-radius: 10px;
    cursor: pointer;
  }
</style>