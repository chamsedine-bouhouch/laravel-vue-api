<template>
    <div class="todoListContainer">
        <div class="heading">
            <h2 id="title">Todo List</h2>
            <add-item-form></add-item-form>
        </div>
        <list-view/>
    </div>
</template>
<script>
import addItemForm from "./addItemForm"
import listView from "./listView"
export default {
    name:"App",
    comments:{
        addItemForm,
        listView
    }
}
</script>
<style >
   .todoListContainer{
       width: 350px;
       margin: auto;
   } 
   
</style>