<script>
	import { Header, Contact, Quiz } from '$widgets';
	// import { } from '$entities';
	import { HeaderLink } from '$shared';
</script>


<svelte:head>
	<title>QIUZ - Archaeo stories</title>
</svelte:head>

<Header>
  <ul class="items-stretch hidden space-x-3 md:flex" slot='left-links'>
    <HeaderLink link='/#about' title='About'/>
  </ul>

  <ul class="items-stretch hidden space-x-3 md:flex" slot='right-links'>
    <HeaderLink link='/quiz' title='Quiz'/>
  </ul>

</Header>

<main class="page_main bg-[#eae0c7] h-screen">
  <div class="sec-2 mb-20">
    <div class="mob-map"></div>
    <div class="mapp"></div>
    <div class="sec-2-main">
    <div class="rel ">
      <div class="left">
      <h2 class="font-veneer bg-[#eae0c7] px-4 text-center">Thank you for your interest  <br /> for <a href='/' class='text-[#793610]'>ARCHAE-STORIES</a>.</h2>
      <div class="rot">
        <h1 class="font-veneer text-center bg-[#eae0c7]">Web application<br />  in development </h1>
      </div>
      <div class="text-block2 bg-[#eae0c7]">
        <h4 class="uppercase font-veneer  px-10 text-center py-4">The web application  <br />   will be available soon.</h4>
      </div>
      </div>
    </div>
    <div class="rel _100 _2 second ">

      <div class="left _2">
      <div class="right-align ">
        <div class="py-20 ">

        </div>
         <div>
        </div>
      </div>
      </div>
    </div>

    </div>
  </div>


</main>


<style>
	.man-wrap {
  flex-direction: column;
  align-items: flex-start;
  display: flex;
  position: relative;
  top: -150px;
  left: 50px;
}

.yk-map {
  width: 25rem;
  margin-top: 2rem;
}
.yk-map.multiply {
  position: relative;
  top: -27px;
}


._1--right {
  width: 35vw;
  flex-direction: column;
  display: flex;
}

.mob-map {
  display: none;
}

.rot {
  transform: rotate(-4deg);
}

.text-block2 {
  max-width: 400px;
  margin-top: 4rem;
}

.sec-2 {
  width: 100%;
  background-color: var(--papaya-whip);
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding-top: 5rem;
  display: flex;
  position: relative;
}

.sec-2-main {
  z-index: 5;
  width: 100%;
  flex-direction: column;
  align-items: center;
  padding-top: 2rem;
  display: flex;
}

.right-image {
  width: 30vw;
  position: relative;
  top: -66px;
}

.right-align {
  text-align: right;
}

@media screen and (max-width: 991px) {
  .mapp {
    left: -14%;
     width: 100vw;
  height: 96%;
  background-image: url(/images/banner-map.svg);
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
  flex-direction: column;
  align-items: center;
  margin-top: -50px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  position: absolute;
  top: 0%;
  bottom: 0%;
  /* left: -8%; */
  right: 0%;

  }
  .man-wrap {
    top: 20px;
    left: 0;
  }
.right-image {
    width: 25vw;
    margin-left: 20%;
  }
}

@media screen and (max-width: 767px) {
   .rel._100._2.second {
    flex-direction: column-reverse;
  }
.man-wrap {
    top: -24px;
  }
    .right-align.mob {
    text-align: left;
  }
.right-image {
    display: none;
  }


.mapp {
   height: 100%;
    left: -20%;
  background-image: url(/images/banner-map.svg);
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
  flex-direction: column;
  align-items: center;
  margin-top: -50px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  position: absolute;
  top: 0%;
  bottom: 0%;
  /* right: -52%; */
}

.yk-map.multiply {
    display: none;
    right: 106px;
  }
}

@media screen and (max-width: 479px) {
    .yk-map.multiply {
    display: none;
    right: 85px;
  }
    .right-align.mob {
    width: 64vw;
  }

}


@media screen and (min-width: 991px) {

.mapp {
  width: 100vw;
  height: 96%;
  background-image: url(/images/banner-map.svg);
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
  flex-direction: column;
  align-items: center;
  margin-top: -50px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  position: absolute;
  top: 0%;
  bottom: 0%;
  left: -8%;
  right: 0%;
}
}

</style>
