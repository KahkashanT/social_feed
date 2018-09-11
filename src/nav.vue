
<template>
<div>
    <div id="navbar">
       <icon iconname='fa fa-pencil' status='Status'/>
        <icon iconname='fa fa-camera' status='Photo/Video'/>
        <user id="userpic" sourcefile='./src/user.png' ></user>
    </div>
</div>
</template>
<script>
    
     import  icon from './icon.vue';
     import  user from './user.vue';

    export default {
      name: 'navbar',
    components:{
    icon,user
    },
      
    };
</script>
<style>
#navbar{
overflow:hidden;
background-color:#e6e6e6;
width:80%;
margin:auto;
margin-top:10px;
margin-bottom:10px;
}

#userpic img{
float:right;
border:1px solid #e6e6e6;
display:block;
height:50px;
width:50px;
}
</style>