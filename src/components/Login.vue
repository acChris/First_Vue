<template>
    <div id="firstcomponent">
        <h1>My first Component</h1>
        <a href="#">作者：acChris</a>
    </div>
</template>

<script type="text/javascript">

import axios from 'axios'

export default {
    name: 'Login',
    mounted: function(){
        axios.post('/Login')
        .then(function (response){
            console.log(response);
        })
        .catch(function (response){
            console.log(response);
        });
    }
    }
</script>
