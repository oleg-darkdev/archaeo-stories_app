<script>
	import { Slider, Quiz, Contact, Header } from '$widgets';
	// import { } from '$entities';
	// import {  } from '$shared';
</script>

<svelte:head>
	<title>Archaeo stories</title>
</svelte:head>


    <div data-w-id="/" style="" class="page_wrap">
      <div class="page_code_wrap">
        <div class="page_code_typography w-embed">
          <style>
            /* TYPOGRAPHY STYLES */
            /* defaults */
            [class*="fs0"],
            h1,
            [class*="fs1"],
            h2,
            [class*="fs2"],
            h3,
            [class*="fs3"],
            h4,
            [class*="fs4"],
            h5,
            [class*="fs5"],
            h6,
            [class*="fs6"],
            p,
            [class*="fs7"] {
              font-size: inherit;
              font-family: inherit;
              font-weight: inherit;
              line-height: inherit;
              letter-spacing: inherit;
              text-transform: inherit;
            }

            body {
              font-smoothing: antialiased;
              -webkit-font-smoothing: antialiased;
            }

            h1,
            h2,
            h3,
            h4,
            h5,
            h6,
            p {
              margin-top: 0;
              margin-bottom: 0;
            }

            :is(h1, h2, h3, h4, h5, h6, p) a {
              text-decoration: underline;
            }

            .w-richtext>*:first-child {
              margin-top: 0;
            }

            .w-richtext>*:last-child {
              margin-bottom: 0;
            }

            /* body font styles */
            body {
              font-size: 1.125rem;
              font-family: var(--ff1);
              font-weight: var(--fw1);
              line-height: var(--lh1);
              letter-spacing: var(--ls1);
              text-transform: var(--tt1);
            }

            /* heading font styles */
            [class*="fs0"],
            h1,
            [class*="fs1"],
            h2,
            [class*="fs2"],
            h3,
            [class*="fs3"],
            h4,
            [class*="fs4"],
            h5,
            [class*="fs5"],
            h6,
            [class*="fs6"] {
              /* font-family: var(--ff0); */
              font-weight: var(--fw2);
              line-height: var(--lh4);
              letter-spacing: var(--ls2);
              /* text-transform: var(--tt0); */
            }

            /* individual font styles */
            [class*="fs0"] {
              font-size: 7rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h1,
            [class*="fs1"] {
              font-size: 5.5rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h2,
            [class*="fs2"] {
              font-size: 3.75rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h3,
            [class*="fs3"] {
              font-size: 3.25rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h4,
            [class*="fs4"] {
              font-size: 2.5rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h5,
            [class*="fs5"] {
              font-size: 2rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            h6,
            [class*="fs6"] {
              font-size: 1.5rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            [class*="fs7"] {
              font-size: inherit;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            [class*="fs7-1"] {
              font-size: 1.5rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            [class*="fs7-2"] {
              font-size: 0.875rem;
              /* font-family: var(--ff0); */
              /* font-weight: var(--fw0); */
              /* line-height: var(--lh0); */
              /* letter-spacing: var(--ls0); */
              /* text-transform: var(--tt0); */
            }

            /* responsive font styles */
            @media screen and (max-width: 991px) {

              /* tablet font styles */
              [class*="fs0"] {
                font-size: 5.5rem;
              }

              h1,
              [class*="fs1"] {
                font-size: 4.2rem;
              }

              h2,
              [class*="fs2"] {
                font-size: 3.2rem;
              }

              h3,
              [class*="fs3"] {
                font-size: 2.8rem;
              }

              h4,
              [class*="fs4"] {
                font-size: 2.4rem;
              }

              h5,
              [class*="fs5"] {
                /* font-size: 0rem; */
              }

              h6,
              [class*="fs6"] {
                /* font-size: 0rem; */
              }

              body {
                /* font-size: 0rem; */
              }

              [class*="fs7-1"] {
                /* font-size: 0rem; */
              }

              [class*="fs7-2"] {
                /* font-size: 0rem; */
              }
            }

            @media screen and (max-width: 767px) {

              /* landscape font styles */
              [class*="fs0"] {
                font-size: 4.8rem;
              }

              h1,
              [class*="fs1"] {
                font-size: 3.8rem;
              }

              h2,
              [class*="fs2"] {
                font-size: 2.8rem;
              }

              h3,
              [class*="fs3"] {
                font-size: 2.6rem;
              }

              h4,
              [class*="fs4"] {
                /* font-size: 0rem; */
              }

              h5,
              [class*="fs5"] {
                /* font-size: 0rem; */
              }

              h6,
              [class*="fs6"] {
                /* font-size: 0rem; */
              }

              body {
                /* font-size: 0rem; */
              }

              [class*="fs7-1"] {
                /* font-size: 0rem; */
              }

              [class*="fs7-2"] {
                /* font-size: 0rem; */
              }
            }

            @media screen and (max-width: 479px) {

              /* portrait font styles */
              [class*="fs0"] {
                font-size: 4rem;
              }

              h1,
              [class*="fs1"] {
                font-size: 3.2rem;
              }

              h2,
              [class*="fs2"] {
                /* font-size: 0rem; */
              }

              h3,
              [class*="fs3"] {
                /* font-size: 0rem; */
              }

              h4,
              [class*="fs4"] {
                /* font-size: 0rem; */
              }

              h5,
              [class*="fs5"] {
                /* font-size: 0rem; */
              }

              h6,
              [class*="fs6"] {
                /* font-size: 0rem; */
              }

              body {
                /* font-size: 0rem; */
              }

              [class*="fs7-1"] {
                /* font-size: 0rem; */
              }

              [class*="fs7-2"] {
                /* font-size: 0rem; */
              }
            }

            /* variables */
            html {
              /* font family */
              --ff0: inherit;
              --ff1: Nerko One, sans-serif;
              /* font weight */
              --fw0: inherit;
              --fw1: 400;
              --fw2: 500;
              --fw3: 700;
              /* line height */
              --lh0: inherit;
              --lh1: 1.5;
              --lh2: 1.3;
              --lh3: 1.1;
              --lh4: 0.9;
              /* letter spacing */
              --ls0: inherit;
              --ls1: 0em;
              --ls2: -0.03em;
              /* text transform */
              --tt0: inherit;
              --tt1: none;
              --tt2: uppercase;
              --tt3: capitalize;
              --tt4: lowercase;
            }

            /* utilities */
            /* font family */
            [class*="ff1"] {
              font-family: var(--ff1);
            }

            [class*="ff0"] {
              font-family: var(--ff0);
            }

            /* font weight */
            [class*="fw1"] {
              font-weight: var(--fw1);
            }

            [class*="fw2"] {
              font-weight: var(--fw2);
            }

            [class*="fw3"] {
              font-weight: var(--fw3);
            }

            [class*="fw0"] {
              font-weight: var(--fw0);
            }

            /* line height */
            [class*="lh1"] {
              line-height: var(--lh1);
            }

            [class*="lh2"] {
              line-height: var(--lh2);
            }

            [class*="lh3"] {
              line-height: var(--lh3);
            }

            [class*="lh4"] {
              line-height: var(--lh4);
            }

            [class*="lh0"] {
              line-height: var(--lh0);
            }

            /* letter spacing */
            [class*="ls1"] {
              letter-spacing: var(--ls1);
            }

            [class*="ls2"] {
              letter-spacing: var(--ls2);
            }

            [class*="ls0"] {
              letter-spacing: var(--ls0);
            }

            /* text transform */
            [class*="tt1"] {
              text-transform: var(--tt1);
            }

            [class*="tt2"] {
              text-transform: var(--tt2);
            }

            [class*="tt3"] {
              text-transform: var(--tt3);
            }

            [class*="tt4"] {
              text-transform: var(--tt4);
            }

            [class*="tt0"] {
              text-transform: var(--tt0);
            }

            /* line clamp */
            [class*="lc1"],
            [class*="lc2"],
            [class*="lc3"],
            [class*="lc4"] {
              display: -webkit-box;
              overflow: hidden;
              -webkit-line-clamp: 1;
              -webkit-box-orient: vertical;
            }

            [class*="lc2"] {
              -webkit-line-clamp: 2;
            }

            [class*="lc3"] {
              -webkit-line-clamp: 3;
            }

            [class*="lc4"] {
              -webkit-line-clamp: 4;
            }

            /* text wrap */
            [class*="tw1"] {
              text-wrap: balance;
            }
          </style>
        </div>
      
        <div class="page_code_custom w-embed">
          <style>
            /* CUSTOM STYLES */
            /* remove scroll bounce */
            body {
              overscroll-behavior: none;
            }

            /* prevent horizontal scroll */
            .page_wrap {
              /* overflow: clip; */
            }

            /* enable setting w-button border radius with utilities */
            .w-button {
              border-radius: var(--border-radius);
            }

            /* hide container ::before & ::after */
            .w-container::before,
            .w-container::after {
              display: none;
            }

            /* empty div in designer view when utilities are added */
            .wf-empty[class*="--"] {
              padding-bottom: 0;
              padding-right: 0;
            }

            /* flex: reverse direction */
            [reverse-direction="true"] {
              flex-direction: row-reverse;
            }

            /* btn small */
            [btn-main-small="true"] {
              padding: 0.6rem 1rem;
            }

            /* btn hovers */
            @media (pointer: fine) {
              a:hover [btn-main="icon"] {
                transform: translateX(0.2rem);
              }

              a:hover [btn-play="base"] {
                transform: scale(1.1);
              }
            }

            /* form styles */
            /* field placeholder */
            .w-input::placeholder,
            .w-select::placeholder {
              color: var(--fc2);
            }

            /* field focus */
            .w-input:focus,
            .w-select:focus {
              border-color: var(--bc2);
            }

            /* checkbox and radio selected */
            .w-checkbox-input.w--redirected-checked,
            .w-radio-input.w--redirected-checked {
              background-color: rgba(var(--brand-1), 1);
              border-color: rgba(var(--brand-1), 1);
            }

            .multiply {
              mix-blend-mode: multiply;
            }
          </style>
        </div>
        <div class="scroll w-embed">
          <style>


            /* ===== Scrollbar CSS ===== */
            /* Firefox */
            * {
              scrollbar-width: auto;
              scrollbar-color: #444444;
            }

            /* Chrome, Edge, and Safari */
            *::-webkit-scrollbar {
              width: 5px;
            }

            *::-webkit-scrollbar-track {
              background: #000;
            }

            *::-webkit-scrollbar-thumb {
              background-color: #C19F7A;
              border-radius: 8px;
              border: 3px solid #C19F7A;
            }
          </style>
        </div>
      </div>
      <Header />
      <main class="page_main">
        <div class="sec-2">
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
                  <h4 class="tt2">An educational board game that introduces players to the fascinating world of archaeology.</h4>
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
                <div class="right-align mob">
                  <div class="pt1">
                    <p class="p">The game integrates traditional board game with modern digital technologies, creating a fun and educational experience for players of all ages.</p>
                  </div>
                  <!-- <img src="images/mountains-river.webp" loading="lazy" alt="" class="mob-img"> -->
                  <div>
                    <!-- <h4 class="f2 tt2 lra">Miles <br>Canyon </h4> -->
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
        <Slider />
        <div class="sec-3">
          <div class="wrapper fvc">
            <div class="rel">
              <div class="pl aa">
                <div class="rot">
                  <h1 class="font-veneer">about <br/> project</h1>
                </div>
              </div>
              <div class="_100 pt4">
                <div class="_80vw fc1">
                  <h1 class="tt2 tc">Lorem ipsum is placeholder text commonly used.</h1>
                </div>
              </div>
            </div>
            <!-- <img src="images/64fb5dc0eafa3fed194074e1_image_1042-removebg-preview.webp" loading="lazy" alt="" class="sec-3-img-2 multiply"> -->
          </div>
        </div>
        <div class="sec-4">
          <div class="sec-4-bg multiply "></div>
          <div class="wrapper full mob">
            <div class="rel">
              <div class="slide-b-wrap _1">
                <div  class="test-slider _1 w-slider">

                  <div class="w-slide">
                      <div class="test-inner">
                        <!-- <img sizes="(max-width: 479px) 80vw, 297.8125px" srcset="images/65051584a148878dfed621fb_Frame%20128-p-500.webp 500w, images/65051584a148878dfed621fb_Frame%20128-p-800.webp 800w, images/65051584a148878dfed621fb_Frame%20128-p-1080.webp 1080w, images/65051584a148878dfed621fb_Frame%20128-p-1600.webp 1600w, images/65051584a148878dfed621fb_Frame%20128.webp 1866w" alt="" src="images/65051584a148878dfed621fb_Frame%20128.webp" loading="lazy" class="test--i"> -->
                        <p class="p _80">
                          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                         </p>
                         <p class="p _80">
                          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
                          <span class="co-name">- Big Bear Co.</span>
                        </p>
                      </div>
                    </div>
                  <div class="w-slider-nav w-round"></div>
                </div>
                <div class="sec-4-t1 rot">
                  <div class="ch-smal">
                    <h3 class="f2 tt2">Lorem ipsum dolor sit amet consectetur </h3>
                  </div>
                </div>
              </div>
              <div class="slide-b-wrap _2">
                <div class="test-slider _2 w-slider" >
                  <div class="w-slider-mask">
                    <div class="w-slide">
                      <div class="test-inner">
                        <!-- <img sizes="(max-width: 479px) 80vw, 297.8125px"  alt="" src="images/650473e15204616247ec5eb8_Frame%20132.webp" loading="lazy" class="test--i"> -->
                        <p class="p _80">
                          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                         </p>
                         <p class="p _80">
                          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. <br>
                          <span class="co-name">- Big Bear Co.</span>
                        </p>
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
                  <h2 class="f2 tt2 pb2">Lorem ipsum  <br>dolor sit amet <br>, consectetur  <br>adipiscing elit, sed. </h2>
                </div>
              </div>
            </div>
          </div>
          <!-- <div class="sec-4-i2 multiply"></div> -->
          <div class="mob-map-1"></div>
          <div class="mob-map-2"></div>
        </div>
        <Contact />
        <Quiz />
        <!-- <div class="sec-6 w-full"> -->
          <!-- <div class="wrapper padding">
            <div class="rel">
              <div data-w-id="e271c2dd-0ad0-06b3-961e-4390888b876c" class="footer-sub">
                <div class="footer-fvl">
                  <a href="/" class="footer-logo w-inline-block">
                    <img src="images/650218ce47a4a607d331642b_mammoth-logo.webp" loading="lazy" sizes="250px"  alt="">
                  </a>
                  <div class="fvl _2">
                    <a href="https://goo.gl/maps/ikrR7yaezA4DAmHc9" class="bold w-inline-block">
                      <div class="p">301 Hoge St, <br>Whitehorse, <br>YTY1A 1V8 </div>
                    </a>
                    <a href="mailto:hello@mammothagency.ca" class="bold w-inline-block">
                      <div class="p">hello@mammothagency.ca</div>
                    </a>
                    <div class="fhl">
                      <a href="https://www.facebook.com/mammothyukon" target="_blank" class="footer-ico w-inline-block">
                        <div>FB</div>
                      </a>
                      <a href="https://www.instagram.com/mammothyukon/" target="_blank" class="footer-ico w-inline-block">
                        <div>IG</div>
                      </a>
                      <a href="https://www.linkedin.com/company/mammoth-agency-yukon/?originalSubdomain=ca" target="_blank" class="footer-ico w-inline-block">
                        <div>IN</div>
                      </a>
                    </div>
                  </div>
                </div>
                <div id="w-node-_75f3c98f-f27f-ffont-veneerf-6582-a18d392489e1-570e3a99" class="form-block w-form">

                  <div class="success-message w-form-done">
                    <div class="succ">
                      <div>Thank you! Your submission has been received!</div>
                    </div>
                  </div>
                  <div class="w-form-fail">
                    <div>Oops! Something went wrong while submitting the form.</div>
                  </div>
                </div>
              </div>
            </div>
          </div> -->
          <!-- <div class="sec-6-bg">
            <div class="sec-6-boat multiply"></div>
          </div>
        </div> -->
      </main>
    </div>
