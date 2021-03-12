<template>
  <div class="addItem">
    <input />
    <font-awesome-icon 
    icon="plus-square" 
    />
  </div>
</template>
<script>
export default {
  name: "add-item-form",
};
</script>
<style scoped>
.addItem {
  display: flex;
  justify-content: center;
  align-items: center;
}

input {
  background: #f7f7f7;
  border: 0px;
  outline: none;
  padding: 5px;
  margin-right: 10px;
  width: 85%;
}

.plus {
  font-size: 20px;
}
.active {
  color: #00ce25;
}
.inactive {
  color: #999999;
}
</style>
