
<template>
<div >
<p style='color:grey; margin-top:15px;margin-left:10px;' id='icon'>&nbsp;&nbsp;<i :class=iconname style='color:grey;'></i>&nbsp;{{status}}&nbsp;</p>
</div>
</template>
<script>
    
    export default {
      name: 'icon',
    data(){
    return{
        
        }
    },
    props:[
        'iconname',
        'status'
    ]
      
    };
</script>
<style>
#icon{
float:left;
}

</style>
