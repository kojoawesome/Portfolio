<template>
    <div class="container-fluid">
       <div class="row">
        <div class="col-6" id="intro">
            <div class="intro_texts">
                <h3> Hello, Im Kojo</h3>
                <h1> Full Stack <br> Developer</h1>
                <h3> based in Ghana </h3>
                <a href="#" class="resume"> Resume</a>
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
        <div class="row">
        <div class="col-12">
            <div class="Project">
                <h1> Projects. </h1>
            <P>This portfolio showcases my professional work, skills, 
                and accomplishments as a highly motivated and versatile individual. 
                It encompasses a wide range of projects, including graphic designs, 
                web development, written content, and more.
            </P>
            </div>
        </div>
        </div>
        <div class="Stacked">
            <div class="row row-cols-1 row-cols-md-2 g-4">
  <div class="col">
    <div class="card">
      <img src="" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="" class="card-img-top" alt="">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="" class="card-img-top" alt="">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="" class="card-img-top" alt="">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
</div>    
    </div>

    <div class="Project">
                <h1> Contact. </h1>
                
            </div>
    </div>
</template>

<script>
export default {
    data(){
    return {
      Image: require('@/assets/pp.png'),
      Contact_image: require('@/assets/telephone.jpg')
    }
  },
  
}
</script>

<style scoped>

.resume {
    margin-top:30px;
    padding: 20px;
    border: solid;
}
.pic {
    width: auto;
    height: 500px;
}

.contact_pic{
    width: auto;
    height: 450px;
}

#intro,.about, .Project {
    text-align: left;
}

.about h1, .Project h1{
    font-weight: bold;
    font-size: 70pt;
    color:#F7F197 ;
}

.about p, .Project p {
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

.intro_texts, .about, .Project {
    margin-left: 100px;
    margin-bottom: 70px;
}

.container-fluid {
    margin: 100px 0px 50px 0px;   
}

.Stacked {
    margin: 10px 100px;
}


</style>

