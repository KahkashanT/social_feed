

<template>
<div >
    <div>
    <input type="text" class="form-control" id="writeSomething" placeholder="Write Something on this page..."/>
    </div>
    <div>
    <icon iconname='fa fa-camera' id="icons_down"/>
    <icon iconname='fa fa-smile-o' id="icons_down2"/>
    </div>
</div>
</template>
<script>
    import  icon from './icon.vue';
    export default {
      name: 'writeComment',
    components:{
    icon
    },
    };
</script>
<style>
#writeSomething{
float:left;
width:90%;
margin-top:15px;
}
#icons_down{
display:inline-block;
margin-top:10px;
margin-left:-70px;
}
#icons_down2{
display:inline-block;
margin-top:10px;
margin-left:-20px;
}
</style>

