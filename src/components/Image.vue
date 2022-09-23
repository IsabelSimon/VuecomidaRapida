<template>
    <div>
      <slot></slot>
    </div>
</template>

<style scoped>
 div{       
        border-radius: 10px !important;
        color:transparent;
    }
    :slotted(img){
        border: 8px solid #fff !important;
        height:12em;
    }
</style>