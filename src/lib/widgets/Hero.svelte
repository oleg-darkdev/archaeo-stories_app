<div class="sec-2 mb-20">
	<div class="mob-map"></div>
	<div class="mapp"></div>
	<div class="sec-2-main">
	<div class="rel _100 _2">
		<div class="left">
		<h2 class="font-veneer">HI THERE,</h2>
		<div class="rot">
			<h1 class="font-veneer">we're on an <br /> archaeological <br /> excavation. </h1>
		</div>
		<div class="text-block2">
			<h4 class="uppercase font-nerkoOne">An educational board game that introduces players to the fascinating world of archaeology.</h4>
		</div>
		</div>
		<div class="_1--right">
		<img src="images/paleontology.png" loading="lazy" alt="Mountains image" class="right-image">
		<img src="images/archaeology_metal.png" loading="lazy" alt="" class="yk-map multiply">
		</div>
	</div>
	<div class="rel _100 _2 second ">
		<div class="man-wrap h-40 my-20">
		<!-- images/archaeology_metal.png -->
		<!-- <img src="" loading="lazy" alt="" class="Tourist man"> -->
		</div>
		<div class="left _2">
		<div class="right-align ">
			<div class="pt-10 ">
				<p class="font-nanumPen text-3xl">The game integrates traditional board game with modern digital technologies, creating a fun and educational experience for players of all ages.</p>
			</div>
			<!-- <img src="images/mountains-river.webp" loading="lazy" alt="" class="mob-img"> -->
			<div>
			<!-- <h4 class="f2 uppercase lra">Miles <br>Canyon </h4> -->
			</div>
		</div>
		</div>
	</div>

	</div>
</div>


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
    left: 0%;
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
  right: -52%;}

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
   .mapp {
    width: 120vw;
    display: none;
  }

   .mob-map {
    width: 110vw;
    height: 165vh;
    background-image: url(/images/big-map.svg);
    background-position: 50%;
    background-repeat: no-repeat;
    background-size: contain;
    display: block;
    position: absolute;
    top: -20vh;
    bottom: 0%;
    left: auto;
    right: -45vw;
    transform: rotate(-9deg);
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
