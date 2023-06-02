<template>
    <div class="container-fluid">
       <div class="row">
        <div class="col-6" id="intro">
            <div class="intro_texts">
                <h3> Hello, Im Kojo</h3>
                <h1> Full Stack <br> Developer</h1>
                <h3> based in Ghana </h3>
                <button> Resume </button>
            </div>
        </div>
        <div class="col-6" id="pic">
            <img src="" alt="Profile picture of Kojo">
        </div>
       </div>
    </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
#intro {
    text-align: left;
}

.intro_texts h1{
    font-weight: bold;
    font-size: 70pt;
}

.intro_texts h3{
    font-weight:normal;
    font-size: 25pt;
}

.intro_texts {
    margin-left: 100px;
}

.container-fluid {
    margin: 100px 0px 50px 0px;   
}


</style>

