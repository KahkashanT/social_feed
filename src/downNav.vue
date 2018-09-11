


<template>

    <div id="downNav">
       
        <user id='userpicture' sourcefile='./src/user.png' ></user>
        <writeComment></writeComment>
    </div>

</template>
<script>
    
    
     import  user from './user.vue';
      import  writeComment from './writeComment.vue';

    export default {
      name: 'downNav',
    components:{
    user,writeComment
    },
      
    };
</script>
<style>

#downNav{
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