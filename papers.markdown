---
layout: page
title: Research papers read
permalink: /papers/
---


<style>
    *,
    *::before,
    *::after{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    html{
        font-family: 'Roboto', sans-serif;
        font-size: 10px;
    }

    img{
        width: 100%;
    }

    .card{
        width: 100%;
        max-width: 98rem;
        padding: 5rem;
        /* background-color: #fff; */
        background-color: #f8efe8;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.2s;
        display: flex;
        align-items: center;
        border-radius: .8rem;
    }

    .card_image{
        min-width: 30rem;
        max-width: 30rem;
        height: 35rem;
        transform: translateX(-8rem);
        position: relative;
    }

    .card_image img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        display: block;
        border-radius: .8rem;
    }

    .card_image::before{
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background: linear-gradient(to right, rga(79,172,254,.8),
                                              rga(0, 242, 254, .8));
        box-shadow: .5rem .5rem 3rem 1px rgba(0,0,0,.05);
        border-radius: .8rem;
    }

</style>


<!-- <div class="card background1">
    <div class="card_image">
            <img src="../resources/attention.png">
    </div>
    <div class="card_info">
        <div class="card_date">
            <span>Sunday</span>
            <span>January 21 2024</span>
        </div>
        <h1 class="card_title">Attntion Is All You Need</h1>
        <p class="card_desc">
        asdasdasdasdasdasd
        </p>
        <a href="#" class="card_cta">Read more</a>
    </div>
</div> -->

<div class="card">
        <div class="card_image">
            <img src="../resources/attention.png">
        </div>
        <div class="card_info">
            <div class="card_date">
                <span>Sunday</span>
                <span>January 21 2024</span>
            </div>
            <h1 class="card_title">Attntion Is All You Need</h1>
            <p class="card_desc">
            asdasdasdasdasdasd
            </p>
            <a href="/attention" class="card_cta">Read more</a>
        </div>
</div>

<!-- <style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.2s;
  width: 100%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
}
</style> -->

<!-- <div class="card">
  <img src="img_avatar.png" alt="Avatar" style="width:100%">
  <div class="container">
    <h4><b>John Doe</b></h4> 
    <p>Architect & Engineer</p> 
  </div>
</div> -->

<!-- <style>
.float-layout {
  padding: 5px 5px;
  float: left;
  width: 100%;
  height: auto;
  box-sizing: border-box;
  margin: 0;
}

.card-container {
  overflow: hidden;
}

.card {
  background-color: dodgerblue;
  color: black;
  min-height: 100%; /*replace this it in width: 100%*/
  width: 50%;
  float: right;
}

.card-title {
  font-size: 30px;
  text-align: center;
  font-weight: bold;
  padding-top: 20px;
}

.card-desc {
  padding: 10px;
  text-align: left;
  font-size: 18px;
}

/*add this it*/
.card-image {
  display: flex;
}
/*-------------*/

div.card-image img {
  width: 50%;
  height: auto;
}

/* Phone Devices Query */
@media only screen and (max-width: 37.5em) {
  div.card-image img {
    width: 100%;
    height: auto;
  }
  
  /*add this it*/
  .card-image {
     flex-direction: column;
  }
  /*----------------------*/

  .card {
    width: 100%;
    margin-top: -4px;
  }
}
</style>


<div class="card-container">
  <div class="float-layout">
    <div class="card-image">
      <img src="./resources/attention.png">
      <div class="card">
        <div class="card-title">Title</div>
        <div class="card-desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce ullamcorper
          mollis tempus. Mauris eu maximus lectus, eu auctor justo. Aenean porta purus
          vel commodo consequat.
        </div>
      </div>
    </div>
  </div>
</div>
 -->
