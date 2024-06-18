
<script>
  const ages = [
    {
      title: 'Paleontology',
      desc: 'Explore the remains of grand dinosaurs and ancient animals as you discover the mysteries of the Mesozoic Era.',
      years: '(230000-66000 BC)'
    },
    {
      title: 'Archaeology',
      desc: 'Immerse yourself in the Neolithic and Bronze Age as you study pottery and its importance in the lives of ancient civilizations.',
      years: '(10000-3000 BC)'
    },
    {
      title: 'Archaeology',
      years: '(0-15000 AD)',
      desc: 'Discover the riches of Antiquity and the Middle Ages by exploring metal artifacts, coins, and everyday objects.'
    },
  ]

  const project = [
    {
      title: 'Education boardgame',
      desc: 'The educational boardgame is designed in collaboration with archaeologists and educators to provide in-depth knowledge and correct learning process.'
    },
    {
      title: 'Web application',
      desc: 'The web application is designed to make learning and playing as fun and educational as possible in line with the goals of EDUCATION4.0.'
    },
    {
      title: 'Historical Quiz',
      desc: 'The History Quiz is not just a knowledge test, but an exciting addition to your educational board game. It is designed to deepen your understanding of archaeology and make learning even more exciting.'
    },
    
  ]
</script>

    <div class="rel">
        <div class="slide-b-wrap _1">
        <div  class="test-slider _1 w-slider">

                <div class="w-slide">
                <div class="test-inner">
                <!-- <img sizes="(max-width: 479px) 80vw, 297.8125px"  alt="" src="images/paleontology.png" loading="lazy" class="test--i"> -->
              <div class="rot">
                <h1 class="font-veneer">Explore ancient ages <br> and make amazing <br> discoveries! </h1>
                </div>
                <div class="-rot">
                  <a href="/" target="_blank" class="yellow font-nanumPen text-2xl btn">
                    <div>Start the game</div>
                  </a>
                </div>
                {#each ages as {title, desc, years}}
                  <h3 class="font-nanumPen text-3xl px-4 bg-[#ad885d] rounded-sm -mb-6">{title} <span class="font-nanumPen text-3xl text-[#92633a] -mb-6">{years}</span> </h3>

                  <p class="font-satoshi mb-6 p-4 bg-[#ad885d] rounded-sm">
                      {desc}
                  </p>
                {/each}
                </div>
            </div>


        </div>
        <!-- <div class="sec-4-t1 rot">
            <div class="ch-smal">
            <h3 class="font-nanumPen uppercase">Lorem ipsum dolor sit amet consectetur </h3>
            </div>
        </div> -->


      </div>
        <div class="slide-b-wrap _2">
        <div class="test-slider _2 w-slider" >
            <div class="w-slider-mask">
            <div class="w-slide">
                <div class="test-inner">
                <!-- <img sizes="(max-width: 479px) 80vw, 297.8125px"  alt="" src="images/paleontology.png" loading="lazy" class="test--i"> -->
              <div class="-rot">
                <h1 class="font-veneer">education4.0 <br> concepts</h1>
                </div>
                <!-- <div class="rot">
                  <a href="/" target="_blank" class="yellow font-nanumPen text-2xl btn">
                    <div>Start the game</div>
                  </a>
                </div> -->
                {#each project as {title, desc }}
                  <h3 class="px-4 bg-[#ad885d] rounded-sm font-nanumPen text-3xl -mb-6">{title}</h3>

                  <p class="bg-[#ad885d] font-satoshi mb-6 p-4  rounded-sm">
                      {desc}
                  </p>
                {/each}
                </div>


            </div>
        </div>

    </div>

    </div>

    <div class="nugget multiply"></div>
<div class="wrapper no-b lll">
    <div class="rel">
        <div class="fvc tc fc1">
        <div class="rot-rev">
            <h2 class="font-nanumPen uppercase pb2">Lorem ipsum  <br>dolor sit amet <br>, consectetur  <br>adipiscing elit, sed. </h2>
        </div>
        </div>
    </div>
    </div>
    <!-- <div class="sec-4-i2 multiply"></div> -->
    <div class="mob-map-1"></div>
    <div class="mob-map-2"></div>
</div>


<style>
.-rot {
  transform: rotate(4deg);
}

.rot {
  transform: rotate(-4deg);
}


.test-inner {
  max-width: 50vw;
  grid-column-gap: 1.5rem;
  grid-row-gap: 1.5rem;
  color: var(--white);
  text-align: center;
  flex-direction: column;
  align-items: center;
  margin-left: auto;
  margin-right: auto;
  padding: 3rem 2rem 4rem;
  display: flex;
}

@media screen and (max-width: 991px) {
  .test-inner {
    max-width: none;
    text-align: center;
  }
}

@media screen and (max-width: 479px) {
  .test-inner {
    max-width: none;
  }
}
</style>
