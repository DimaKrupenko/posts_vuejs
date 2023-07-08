<template>
    <button class="btn">
    <slot></slot>
    </button>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
.btn {
  margin-top: 15px;
  align-self: flex-end;
  padding: 10px 15px;
  background-color: none;
  color: teal;
  border: 1px solid teal;
}
</style>