


<template>

    <div id="detail">
       <user id='picture' sourcefile='./src/template.jpg' ></user>
        <div>
    <p><b>Template.net</b> changed their cover photo</p>
    <icon status='2 min' iconname='fa fa-globe' /></p>

    </div>
    </div>
    
</template>
<script>
    
     import  user from './user.vue';
    import  icon from './icon.vue';
    export default {
      name: 'detail',
    components:{
    user,icon
    },
      
    };
</script>
<style>
#detail{
overflow:hidden;
background-color:white;
width:80%;
margin:auto;
margin-top:10px;
margin-bottom:10px;
}
#picture img
{
display:inline;
float:left;
border:1px solid #black;
  
height:70px;
width:70px;
}

</style>