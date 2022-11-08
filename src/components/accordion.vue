<template>
    <div :class="open ? 'acc open':'acc'" @click="$emit('toggleAccordion',index)">
        <div class="acc-header">{{acc.header}}</div>
        <div class="acc-content">{{acc.name}}
            <input type="text">
            
        </div>

    </div>


</template>

<script>


export default{
    name:'accordion',
    props:['acc','index','open']
}

</script>