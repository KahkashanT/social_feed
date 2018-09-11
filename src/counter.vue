

<template>
<div>
    <div id="counter">
       <icon iconname='fa fa-thumbs-up' status='Like'/>
        <icon iconname='fa fa-comments-o' status='Comments'/>
        <icon iconname='glyphicon glyphicon-share-alt' status='Share'/>
        <user id="userpic" sourcefile='./src/user.png' ></user>
    </div>
</div>
</template>
<script>
    
     import  icon from './icon.vue';
     import  user from './user.vue';

    export default {
      name: 'counter',
    components:{
    icon,user
    },
      
    };
</script>
<style>
#counter{
overflow:hidden;
background-color:white;
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