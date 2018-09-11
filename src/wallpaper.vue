

<template>
<div>
    <div id="wallpaper">
       
        <user id="pic" sourcefile='./src/wallpaper.jpg' ></user>
<hr>
    </div>
</div>
</template>
<script>
    
     
     import  user from './user.vue';

    export default {
      name: 'wallpaper',
    components:{
    user
    },
      
    };
</script>
<style>
#wallpaper{
overflow:hidden;
background-color:white;
margin:auto;
margin-top:10px;
margin-bottom:10px;
}

#pic img{

border:1px solid #e6e6e6;
display:block;
height:500px;
width:80%;
margin:auto;
}
</style>