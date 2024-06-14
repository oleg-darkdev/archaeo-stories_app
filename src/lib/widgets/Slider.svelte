<script>


</script>


<div class="sec-2-2">
	<div class="wrapper slide">
		<!-- <div class="rel">
              <div class="slide-header _3">
                <div class="web-block">
                  <div>
                    <h2 class="f4">Lorem impsum</h2>
                  </div>
                </div>
              </div>
              <div class="web-middle"></div>
            </div> -->
		<div class="sub-slider w-slider">
			<div class="w-slider-mask">
				<div class="w-slide">
					<div class="slide-sub">
						<div class="slide-t-holder bg-[#793610]">
							<div class="t-hold-sub">
								<div>
									<div class="">FOOD &amp; BEVERAGE</div>
								</div>
								<div>
									<h6 class="">
										Lorem Ipsum is simply dummy text of the printing and typesetting industr
									</h6>
								</div>
								<div>
									<div class="">Lorem Ipsum is simply</div>
									<p>Lorem Ipsum is simply dummy text of the printing and typesetting industr</p>
								</div>
								<div>
									<div class="">Lorem Ipsum is simply</div>
									<p>Lorem Ipsum is simply dummy text of the printing and typesetting industr</p>
								</div>
							</div>
							<div>
								<div class="tagline _2">Lorem Ipsum is simply</div>
							</div>
						</div>
						<div class="slide-i-holder">
							<img
								sizes="(max-width: 479px) 100vw, (max-width: 767px) 80vw, (max-width: 991px) 40vw, 45vw"
								alt=""
								src=""
								loading="lazy"
								class="i"
							/>
						</div>
					</div>
				</div>
			</div>
			<div class="sub-arrow left w-slider-arrow-left">
				<div class="text-black w-icon-slider-left" />
			</div>
			<div class="sub-arrow right w-slider-arrow-right">
				<div class="text-black w-icon-slider-right" />
			</div>
			<div class="h w-slider-nav" />
		</div>
	</div>
	<div class="wrapper">
		<div class="sec-2--li" />
		<div class="w-full see-more pt-20 pb-20">
			<div>
				<div class="font-veneer text-[#92633a]">
					<!-- WANNA <br> -->
					<h2>SEE <br />MORE?</h2>
				</div>
				<div class="pt2">
					<a href="https://44games.vercel.app/" target="_blank" class="w-inline-block btn">
						<div>More of our educational games</div>
					</a>
				</div>
			</div>
		</div>
		<!-- <div class="horse-man">
              <div class="lesspad">
                <div class="rot-rev">
                  <h3 class="f2 uppercase">Don’t get <br>trapped in <br>legacy branding </h3>
                </div>
              </div>
              <div class="horse-img multiply"></div>
            </div> -->
	</div>
</div>


<style>
.see-more {
  padding-left: 100px;
}

  .w-icon-slider-right:before {
  content: "";
}
.w-icon-slider-left:before {
  content: "";
}

[class^="w-icon-"],
[class*="\ w-icon-"] {
  speak: none;
  font-variant: normal;
  text-transform: none;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-style: normal;
  font-weight: 400;
  line-height: 1;
  font-family: webflow-icons !important;
}


.w-slider-arrow-left,
.w-slider-arrow-right {
  width: 80px;
  cursor: pointer;
  color: #fff;
  -webkit-tap-highlight-color: transparent;
  tap-highlight-color: transparent;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
  margin: auto;
  font-size: 40px;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  overflow: hidden;
}
.w-slider-arrow-left [class^="w-icon-"],
.w-slider-arrow-right [class^="w-icon-"],
.w-slider-arrow-left [class*="\ w-icon-"],
.w-slider-arrow-right [class*="\ w-icon-"] {
  position: absolute;
}


.slide-sub {
  width: 90%;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  background-color: var(--black);
  color: var(--white);
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr;
  grid-auto-columns: 1fr;
  align-items: stretch;
  margin-left: auto;
  margin-right: auto;
  display: grid;
  position: relative;
}

.w-slide {
  vertical-align: top;
  width: 100%;
  height: 100%;
  white-space: normal;
  text-align: left;
  display: inline-block;
  position: relative;
}

.w-slider-arrow-left:focus,
.w-slider-arrow-right:focus {
  outline: 0;
}
.w-slider-arrow-left {
  z-index: 3;
  right: auto;
}
.w-slider-arrow-right {
  z-index: 4;
  left: auto;
}
.w-icon-slider-left,
.w-icon-slider-right {
  width: 1em;
  height: 1em;
  margin: auto;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.w-slider-mask {
  z-index: 1;
  height: 100%;
  white-space: nowrap;
  display: block;
  position: relative;
  left: 0;
  right: 0;
  overflow: hidden;
}

.t-hold-sub {
  grid-column-gap: 2rem;
  grid-row-gap: 2rem;
  flex-direction: column;
  align-items: flex-start;
  display: flex;
}

.slide-i-holder {
  width: 100%;
  height: 100%;
  max-height: 110vh;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  display: flex;
  position: relative;
}

@media screen and (max-width: 767px) {
  .sec-2-2 {
    margin-top: 0;
    padding-top: 25px;
  }
  .wrapper.slide {
    width: 100%;
  }

  .slide-i-holder {
    height: 60vh;
    max-height: 400px;
  }
  .slide-i-holder.full {
    height: 100%;
    max-height: 100%;
  }

  .sub-arrow.right {
    right: -10px;
  }
  .sub-arrow.left {
    left: -10px;
  }

  .sec-2--li {
    width: 35vw;
    height: 100vh;
  }
  .see-more {
    padding-left: 25px;
  }
}


@media screen and (max-width: 479px) {
  .sub-arrow.right {
    right: -16px;
  }
  .sub-arrow.left {
    left: -16px;
  }

    .sec-2--li {
    width: 100vw;
    height: 42vh;
    /* background-image: url(); */
    right: -25%;
  }

}


@media screen and (min-width: 1920px) {
  .slide-i-holder {
    max-height: 100vh;
  }

  .sec-2--li {
    height: 100vh;
    left: 1%;
  }


}

@media screen and (max-width: 991px) {
  .slide-i-holder {
    max-height: 100vh;
  }

  .sec-2--li {
    top: -20vh;
    left: auto;
    right: 311px;
  }
}

  .slide-i-holder {
    height: 100%;
    max-height: 100%;
  }
.wrapper {
  width: 100%;
  max-width: 1500px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 3rem;
  position: relative;
}
.wrapper.slide {
  width: 100%;
  max-width: none;
}

.sec-2-2 {
  /* background-color: var(--papaya-whip); */
  margin-top: -250px;
  position: relative;
}


.sec-2--li {
  z-index: 3;
  width: 45vw;
  height: 110vh;
  object-fit: contain;
  background-image: url(/images/midle-map.svg);
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
  position: absolute;
  top: -35vh;
  bottom: auto;
  left: 8%;
}




</style>