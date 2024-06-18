
<script>
	
const items = [
  {
    id: 0,
    subTitle: 'Lorem tagline',
    title: 'Educational boardgame.',
    img: '/images/photo_1.jpg',
    link: {
      title: '',
      href: '',      
      hidden: true
    },
    shortDesc: [`Our educational board game, enhanced by an interactive web application, offers you to become a real archaeologist. Explore ancient grounds, unearth artifacts, and explore historical discoveries!`],
    features: [
      {
        title: 'Materialistic Scenarios.',
        desc: 'Game scenarios are based on real archaeological excavations, which makes the game not only interesting but also educational. Learn about authentic archaeological discoveries made in Belarus and Poland.'
      },
      {
        title: 'Educational Value',
        desc: 'The boardgame has been developed together with expert archaeologists, which guarantees a high educational value. A great way for children and adults to learn more about ancient eras and archaeology.'
      },
      {
        title: 'Critical Thinking Growth',
        desc: 'Game problems solving and excavation requires logic and analysis, which promotes critical thinking and problem solving skills.'
      },
      {
        title: 'Visual Learning',
        desc: 'Real- world illustrations of archaeological artifacts and illustrations make the learning process visually rich and more memorable.'
      },
    ],
    align: 0
  },
  {
    id: 1,
    subTitle: 'Lorem tagline',
    title: 'Web application.',
    img: '/images/photo_2.jpg',
    link: {
      title: 'Go to APP',
      href: '/app',      
      hidden: false
    },
    shortDesc: [`Use the full capabilities of our web application for additional data and analysis of archaeological discoveries.`],
    features: [
      {
        title: 'Renewable Scenarios.',
        desc: 'Regular updates to scenarios and content ensure that the game is always interesting. New archaeological finds and discoveries will always be at your fingertips.'
      },
      {
        title: 'Extensive knowledge base.',
        desc: 'Access an extensive database with additional information about the artifacts, their historical context and historical significance. Deepen your knowledge and expand your horizons.'
      },
      {
        title: 'Personalized Learning.',
        desc: 'The web app adapts to your interests and knowledge level, offering personalized assignments and learning recommendations.'
      },
      {
        title: 'Video Lessons and Workshops.',
        desc: `
          Access videos and webinars featuring real archaeologists and historians. Learn more about excavation techniques and the history of ancient civilizations directly from the experts.`
      },

    ],
    align: 1
  },
{
    id: 2,
    subTitle: 'Lorem tagline',
    title: 'Educational quiz.',
    img: '/images/photo_3.jpg',
    link: {
      title: 'Go to QUIZ',
      href: '/quiz',
      hidden: false
    },
    shortDesc: [`Answer the questions to learn more about the findings and their significance. Each correct answer will earn you points and bring you a bit further towards the title of a true archaeologist!`],
    features: [
      {
        title: 'In-depth Learning',
        desc: 'The quiz offers additional questions and assignments that expand your knowledge of archaeology. Learn more about ancient civilizations, excavations, and artifacts.'
      },
      {
        title: 'Expert Questions',
        desc: 'Quiz questions are designed by archaeologists and historiсans to ensure the accuracy and educational value of each assignment.'
      },
      {
        title: 'Easy Access',
        desc: 'Quiz is available on all devices and platforms, allowing you to learn anytime, anywhere. Enjoy the quiz at home, on the road, or on an archaeological excavation.'
      },
      {
        title: 'Problem-Oriented Learning',
        desc: 'Challenge yourself with real archaeological problems and challenges by solving them with the help of quiz questions. This will help you better understand the process of excavating and analyzing finds.'
      },
    ],
    align: 0
  },

]
</script>


<section class='sec-2-2 '>
  <div class="px-4 py-12 mx-auto w-full sm:px-6 md:px-12 py-10 bg-[#793610]">
    <!-- <h1 class="mb-8 text-4xl font-nerkoOne leading-none tracking-tighter text-neutral-100 md:text-7xl lg:text-7xl text-center">Features</h1> -->

    <div class="wrapper   w-full max-h-[70vh] z-20 no-scrollbar overflow-y-scroll">
      {#each items as {subTitle, title, img, shortDesc, features, align, link}}
        <div class="flex mx-auto mb-20 flex-wrap justify-center content-center {align ? 'flex-row-reverse': ''} items-center">
      <div class="w-full  lg:max-w-lg lg:w-1/2 rounded-sm">
            <div class="h-full">
              <img class=" mx-auto rounded-sm h-full" alt="hero" src="{img}">
            </div>
      </div>
      <div class="flex flex-col items-start mt-12 mb-16 text-left  lg:flex-grow lg:w-1/2 lg:pl-6 xl:pl-24 md:mb-0 xl:mt-0">
        <!-- <span class="mb-8 text-xs font-satoshi-bold tracking-widest text-neutral-100 uppercase">{subTitle}  </span> -->
        <h1 class="mb-8 text-4xl font-nerkoOne leading-none tracking-tighter text-neutral-100 md:text-7xl lg:text-5xl">{title}</h1>
        {#each shortDesc as desc}
        <p class="mb-2 leading-relaxed max-w-2xl  text-left  font-satoshi text-neutral-100">{desc}</p>
        {/each}

        <div class:hidden={link.hidden} class="mt-8">
					<a href="{link.link}" target="_blank" class="yellow font-nanumPen text-2xl btn">
						<div>{link.title}</div>
					</a>
				</div>
        <div class="flex-col mt-2 max-w-7xl sm:flex">
          <div class="prose prose-md">
            <ul>
              {#each features as {title, desc}}
              <li class="text-neutral-100 ">
                <h3 class="font-satoshi-bold ">{title}</h3>
                <p class="font-satoshi">{desc}</p>
              </li>
              {/each}
            </ul>
          </div>
        </div>
      </div>
      </div>
      {/each}
    </div>
  </div>

  <a name="features"></a>

  <div class="wrapper">
		<div class="sec-2--li" />
		<div class="w-full see-more pt-20 pb-20">
			<div>
				<div class="font-veneer text-[#92633a]">
					<h2>SEE <br />MORE?</h2>
				</div>
				<div class="mt-8">
          <a href="/app" target="_blank" class="yellow font-nanumPen btn">
            <span class='text-2xl'>Other boardgames</span >
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
</section>



<style>
.no-scrollbar::-webkit-scrollbar {
    display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.no-scrollbar {
    -ms-overflow-style: none;  /* IE and Edge */
    scrollbar-width: none;  /* Firefox */
}

.see-more {
  padding-left: 100px;
}
/*
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
 */
/*
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
} */


.slide-sub {
  width: 90%;
  /* grid-column-gap: 0px;
  grid-row-gap: 0px; */
  background-color: var(--black);
  color: var(--white);
  /* grid-template-rows: auto;
  grid-template-columns: 1fr 1fr;
  grid-auto-columns: 1fr; */
  align-items: stretch;
  margin-left: auto;
  margin-right: auto;
  /* display: grid; */
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
