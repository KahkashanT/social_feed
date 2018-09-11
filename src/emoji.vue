


<template>
<div>
    <div id="emoji">
       <icon iconname='em em---1' id="icon"/>
        <icon iconname='    em em-heart' id="icon"/>
        <icon iconname='em em-astonished' id="icon"/>
        <p style="color:blue;margin-top:15px;float:left;">1.6M</p>
        <p style="color:blue;margin-top:15px;float:right; margin-right:15px;">Top Comments</p>
    </div>
</div>
</template>
<script>
    
     import  icon from './icon.vue';
     import  user from './user.vue';

    export default {
      name: 'emoji',
    components:{
    icon,user
    },
      
    };
</script>
<style>
#emoji{
overflow:hidden;
background-color:#e6e6e6;
width:80%;
margin:auto;

margin-bottom:10px;
}
#icon{
margin-left:0px;
margin-right:0px;
}

</style>