<template>
    <div class="container-fluid">
       <div class="row">
        <div class="col-6 col-m-6" id="intro">
            <div class="intro_texts">
                <h3> Hello, I'm Kojo</h3>
                <h1> Web Developer <br> & Brand Expect</h1>
                <h3> based in Ghana </h3>
                <br>
                <a href="https://drive.google.com/file/d/1GP1aWiR2lFgBuL8XsHVcSRxIJ06aWhBt/view?usp=sharing"  target="_blank" class="resume"> Resume 🚀 </a>
            </div>
        </div>
        <div class="col-6">
            <img :src="Image" class="pic">
        </div>
       </div>
       <div class="row">
        <div class="col-12 col-m-12">
            <div class="about">
                <h1> about. </h1>
            <P>A python code enthusiast / creative designer who loves to make an impact. 
              I'm a self-thought designer, who is passionate about design and 
              loves to create solutions for complex problems through illustrations and creative coding.
            </P>
            </div>
        </div>
        </div>
        <div class="row">
        <div class="col-12">
            <div class="Project">
                <h1> projects. </h1>
            <P>This portfolio showcases my professional work, skills, 
                and accomplishments as a highly motivated and versatile individual. 
                It encompasses a wide range of projects, including graphic designs, 
                web development, written content, and more. 
                Below are some of my projects.
            </P>
            </div>
        </div>
        </div>
        <div class="Stacked">
            <div class="row row-cols-1 row-cols-md-2 g-4">
  <div class="col">
      <div class="card">
        <a href="https://www.quarisolutions.com" target="_blank"> <img :src="QuariThumbnail" class="card-img-top" alt="Quari Thumbnail"> </a>
      <div class="card-body">
        <h5 class="card-title" style="text-align: ;">Quari Web</h5>
        <p class="card-text" style="text-align: left;">A global solutions platform providing services that combat Business and Startup challenges</p>
      </div>
    </div>
    
  </div>
  <div class="col">
    <div class="card">
      <a href="https://drive.google.com/file/d/1Hd8WquY8-qHuQRLOLYu7gyDlyLQjmHdG/view?usp=sharing" target="_blank"><img :src="GFCimage" class="card-img-top" alt=""></a>
      <div class="card-body">
        <h5 class="card-title">Give For Change Foundation</h5>
        <p class="card-text" style="text-align: left;">Brand identity developed for a philanthropic organization aimed to help people in need.</p>
      </div>
    </div>
  </div>
    <div class="col">
    <div class="card">
      <a href="https://astounding-crostata-87ed3b.netlify.app/" target="_blank"><img :src="Dadjoke" class="card-img-top" alt=""></a>
      <div class="card-body">
        <h5 class="card-title">Dad Jokes</h5>
        <p class="card-text">Simple app that generates Dad Jokes</p>
      </div>
    </div>
  </div>
</div>    
    </div>

    <div class="contact"  style="margin-bottom: 0px;">
                <div class="row">
                  <div class="col-6">
                    <h1> Contact. </h1>
                    <a href="mailto:kojokumi16.kk@gmail.com">📧 kojokumi16.kk@gmail.com</a>
                    <a href="https://github.com/kojoawesome" target="_blank"> 👩‍💻 Github</a>
                  </div>
                </div>
                
            </div>
    </div>
</template>

<script>
export default {
    data(){
    return {
      Image: require('@/assets/pp.png'),
      QuariThumbnail: require('@/assets/Quarilogo.jpg'),
      GFCimage: require('@/assets/GCF.png'),
      Dadjoke: require('@/assets/Dadjoke.png')
    }
  },
  
}
</script>

<style scoped>

.resume{
    padding-top: 10px;
    text-decoration: none;
    color: #474306;
}

.intro_texts{
    margin-top: 150px ;
    display: flex;
    flex-direction: column;
    align-content: center;
}
.resume:hover, .contact a:hover{
    color:#03045E;
}

.pic {
    width: auto;
    height: 700px;
}

.contact_pic{
    width: auto;
    height: 450px;
}

#intro,.about, .Project , .contact {
    text-align: left;
}

.about h1, .Project h1, .contact h1{
    font-weight: bold;
    font-size: 70pt;
    color:#474306;
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

.intro_texts, .about, .Project, .contact {
    margin-left: 100px;
    margin-bottom: 70px;
}

.container-fluid {
    margin: 100px 0px 0px 0px;   
}

.Stacked {
    margin: 10px 100px;
}

.contact a, .contact{
  text-decoration: none;
  display: block;
  color: #474306;
  padding-bottom: 10px;
}

.card:hover{box-shadow: 1px 1px 20px #dddc8b ;}


</style>

