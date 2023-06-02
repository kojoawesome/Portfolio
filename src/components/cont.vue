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
        <div class="col-6">
            <img :src="Image" class="pic">
        </div>
       </div>
       <div class="row">
        <div class="col-12">
            <div class="about">
                <h1> about. </h1>
            <P>This portfolio showcases my professional work, skills, 
                and accomplishments as a highly motivated and versatile individual. 
                It encompasses a wide range of projects, including graphic designs, 
                web development, written content, and more.
            </P>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
    return {
      Image: require('@/assets/pp.png')
    }
  },
  
}
</script>

<style scoped>
.pic {
    width: auto;
    height: 500px;
}

#intro,.about {
    text-align: left;
}

.about h1{
    font-weight: bold;
    font-size: 70pt;
    color:#F7F197 ;
}

.about p {
    padding-right: 700px;
    font-size: 20pt;
}

.intro_texts h1{
    font-weight: bold;
    font-size: 70pt;
}

.intro_texts h3{
    font-weight:normal;
    font-size: 25pt;
}

.intro_texts, .about {
    margin-left: 100px;
}

.container-fluid {
    margin: 100px 0px 50px 0px;   
}



</style>

