

<template>

    <div id="textbar">
       
        <user id='userpicture' sourcefile='./src/user.png' ></user>
        <write></write>
    </div>

</template>
<script>
    
    
     import  user from './user.vue';
      import  write from './write.vue';

    export default {
      name: 'textbar',
    components:{
    user,write
    },
      
    };
</script>
<style>
#textbar{
overflow:hidden;
background-color:white;
width:80%;
margin:auto;
margin-top:10px;
margin-bottom:10px;
}
#userpicture img
{
display:inline;
float:left;
border:1px solid #black;
    
height:50px;
width:50px;
}
</style>