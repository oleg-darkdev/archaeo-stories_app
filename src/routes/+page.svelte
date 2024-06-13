<script>
	// import {  } from '$widgets';
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
        <!-- <div class="page_code_color w-embed"> -->
          <!-- <link rel="stylesheet" href="css/color.css"> -->
          <!-- <style id="lumos-colors">
            /* COLOR STYLES */
            /**%#**/
            /* btn and link mode transitions */
            [btn-mode],
            [class*="bm0"],
            [link-mode],
            [class*="lm0"] {
              transition-property: background-color, color, border-color, box-shadow;
              transition-duration: 200ms;
            }

            /* applies default border width to cards, elements, and buttons */
            [card-mode]:not([card-mode=""]),
            [class*="cm0"],
            [element-mode]:not([element-mode=""]),
            [class*="em0"],
            [btn-mode]:not([btn-mode=""]),
            [class*="bm0"] {
              --border-width: var(--bw1);
            }

            /**#%**/
            /* global swatches */
            html {
              --dark-1: 34, 34, 32;
              --dark-2: 53, 53, 49;
              --light-1: 244, 244, 241;
              --light-2: 255, 255, 255;
              --brand-1: 198, 251, 80;
              --alt-selection-bg: rgba(var(--brand-1), 1);
              --alt-selection-fc: rgba(var(--dark-1), 1);
            }

           
            /* section mode 2 (dark mode) */
            [section-mode="2"],
            [class*="sm0-2"],
            /* card mode 2 */
            [card-mode="2"],
            [class*="cm0-2"],
            /* styles card mode 2 when inside section mode 1 */
            :is([section-mode="1"], [class*="sm0-1"]) :is([card-mode="2"], [class*="cm0-2"]) {
              /* section mode 2 */
              --m-bg1: rgba(var(--dark-1), 1);
              --m-fc1: rgba(var(--light-2), 1);
              --m-fc2: rgba(var(--light-2), 0.7);
              --m-bc1: rgba(var(--light-2), 0.2);
              --m-sc1: rgba(var(--brand-1), 1);
              /* element mode 1 (tag) */
              --em1-bg1: rgba(var(--brand-1), 0.1);
              --em1-fc1: rgba(var(--brand-1), 1);
              --em1-bc1: rgba(var(--brand-1), 0.2);
              /* btn mode 1 (primary) */
              --bm1-bg1: rgba(var(--brand-1), 1);
              --bm1-bg1b: rgba(var(--brand-1), 1);
              --bm1-fc1: rgba(var(--dark-1), 1);
              --bm1-bg1-hover: rgba(var(--light-2), 1);
              --bm1-bg1b-hover: rgba(var(--light-2), 1);
              --bm1-fc1-hover: rgba(var(--dark-1), 1);
              /* btn mode 2 (secondary) */
              --bm2-bg1b: rgba(var(--light-2), 0.2);
              --bm2-fc1: rgba(var(--light-2), 1);
              --bm2-bg1-hover: rgba(var(--light-2), 1);
              --bm2-bg1b-hover: rgba(var(--light-2), 1);
              --bm2-fc1-hover: rgba(var(--dark-1), 1);
              /* link mode 1 (tab link) */
              --lm1-fc1: rgba(var(--light-1), 0.6);
              --lm1-fc1-hover: rgba(var(--light-1), 1);
              --lm1-bg1b-active: rgba(var(--brand-1), 1);
              --lm1-fc1-active: rgba(var(--light-1), 1);
            }

            /* card mode 1 when inside section mode 2 */
            :is([section-mode="2"], [class*="sm0-2"]) :is([card-mode="1"], [class*="cm0-1"]) {
              --m-bg1: rgba(var(--dark-2), 1);
              --m-fc2: rgba(var(--light-2), 0.7);
              --m-bc1: rgba(var(--light-2), 0.2);
              --m-sc1: rgba(var(--brand-1), 1);
            }

            /* card mode 1 default style */
            :is([card-mode="1"], [class*="cm0-1"]),
            /* card mode 1 when inside section mode 1 */
            :is([section-mode="1"], [class*="sm0-1"]) :is([card-mode="1"], [class*="cm0-1"]) {
              --m-bg1: rgba(var(--light-2), 1);
              --m-fc2: rgba(var(--dark-1), 0.7);
              --m-bc1: rgba(var(--dark-1), 0.2);
              --m-sc1: rgba(var(--dark-1), 1);
            }

            /**%{{element mode: tag}**/
            [element-mode="1"],
            [class*="em0-1"] {
              --m-bg1: var(--em1-bg1);
              --m-fc1: var(--em1-fc1);
              --m-bc1: var(--em1-bc1);
            }

            /**}%**/
            /**%{{btn mode: solid}**/
            [btn-mode="1"],
            [class*="bm0-1"] {
              --m-bg1: var(--bm1-bg1);
              --m-fc1: var(--bm1-fc1);
              --m-bg1-hover: var(--bm1-bg1-hover);
              --m-fc1-hover: var(--bm1-fc1-hover);
            }

            /**}%**/
            /**%{{btn mode: outlined}**/
            [btn-mode="2"],
            [class*="bm0-2"] {
              --m-bg1b: var(--bm2-bg1b);
              --m-fc1: var(--bm2-fc1);
              --m-bg1-hover: var(--bm2-bg1-hover);
              --m-bg1b-hover: var(--bm2-bg1b-hover);
              --m-fc1-hover: var(--bm2-fc1-hover);
              --selection-bg: var(--alt-selection-bg);
              --selection-fc: var(--alt-selection-fc);
            }

            /**}%**/
            /**%{{link mode: nav}**/
            [link-mode="1"],
            [class*="lm0-1"] {
              --m-fc1: var(--lm1-fc1);
              --m-fc1-hover: var(--lm1-fc1-hover);
              --m-bg1b-active: var(--lm1-bg1b-active);
              --m-fc1-active: var(--lm1-fc1-active);
              --selection-bg: var(--alt-selection-bg);
              --selection-fc: var(--alt-selection-fc);
            }

            /**}%**/
            /* backgrounds */
            [class*="bg0"] {
              background-color: transparent;
            }

            [class*="bg0-1"] {
              background-color: currentColor;
            }

            [class*="bg1"] {
              background-color: var(--bg1);
              background-image: var(--bg1i);
              border-color: var(--bg1b);
              box-shadow: var(--bg1s);
            }

            [class*="bg2"] {
              background-color: var(--bg2);
              background-image: var(--bg2i);
              border-color: var(--bg2b);
              box-shadow: var(--bg2s);
            }

            /* font colors */
            [class*="fc0"] {
              color: transparent;
            }

            [class*="fc0-1"] {
              color: currentColor;
            }

            [class*="fc0-2"] {
              color: inherit;
            }

            [class*="fc1"] {
              color: var(--fc1);
            }

            [class*="fc2"] {
              color: var(--fc2);
            }

            /* border colors */
            [class*="bc0"] {
              border-color: transparent;
            }

            [class*="bc0-1"] {
              border-color: currentColor;
            }

            [class*="bc0-2"] {
              border-color: inherit;
            }

            [class*="bc1"] {
              border-color: var(--bc1);
            }

            [class*="bc2"] {
              border-color: var(--bc2);
            }

            /* text stroke colors */
            [class*="sc0"] {
              -webkit-text-stroke-color: transparent;
            }

            [class*="sc0-1"] {
              -webkit-text-stroke-color: currentColor;
            }

            [class*="sc0-2"] {
              -webkit-text-stroke-color: inherit;
            }

            [class*="sc1"] {
              -webkit-text-stroke-color: var(--sc1);
            }
          </style>
        </div> -->
        <!-- <div class="page_code_utilities w-embed">

          <style>
            /* UTILITY STYLES */
            /* defaults */
            * {
              --text-stroke-width: 0;
              -webkit-text-stroke-width: var(--text-stroke-width);
              --border-radius: 0;
              border-radius: var(--border-radius);
              --border-width: 0;
              border-width: var(--border-width);
              border-style: solid;
            }

            /* variables */
            html {
              /* small section padding */
              --vt1: var(--size3);
              --vb1: var(--size3);
              /* medium section padding */
              --vt2: var(--size5);
              --vb2: var(--size5);
              /* large section padding */
              --vt3: var(--size9);
              --vb3: var(--size9);
              /* page padding */
              --pp1: 3rem;
              /* max width */
              --mw1: 90rem;
              --mw2: 70rem;
              /* stroke width */
              --sw1: var(--bw1);
              --sw2: var(--bw2);
              /* border radius */
              --br1: 0.5rem;
              --br2: 1rem;
              --br3: 100vw;
              /* border width */
              --bw1: 1.5px;
              --bw2: 3px;
              /* default grid gap */
              --default-grid-gap: 1rem;
              --default-row-gap: var(--default-grid-gap);
              --default-column-gap: var(--default-grid-gap);
              /* spacing scale */
              --spacing-scale: 1;
            }

            /* tablet */
            @media screen and (max-width: 991px) {
              html {
                /* page padding */
                --pp1: 1.5rem;
                /* spacing scale */
                --spacing-scale: 0.75;
              }
            }

            /* landscape */
            @media screen and (max-width: 767px) {
              html {
                /* page padding */
                --pp1: 1.25rem;
                /* spacing scale */
                --spacing-scale: 0.5;
              }
            }

            /* portrait */
            @media screen and (max-width: 479px) {
              html {
                /* page padding */
                --pp1: 1rem;
              }
            }

            /* section styles */
            main section,
            header,
            footer {
              position: relative;
              padding-top: var(--vt2);
              padding-bottom: var(--vb2);
            }

            /* small */
            [class*="vt1"],
            [vertical-top="1"] {
              padding-top: var(--vt1);
            }

            [class*="vb1"],
            [vertical-bottom="1"] {
              padding-bottom: var(--vb1);
            }

            /* medium */
            [class*="vt2"],
            [vertical-top="2"] {
              padding-top: var(--vt2);
            }

            [class*="vb2"],
            [vertical-bottom="2"] {
              padding-bottom: var(--vb2);
            }

            /* large */
            [class*="vt3"],
            [vertical-top="3"] {
              padding-top: var(--vt3);
            }

            [class*="vb3"],
            [vertical-bottom="3"] {
              padding-bottom: var(--vb3);
            }

            /* none */
            [class*="vt0"],
            [vertical-top="0"] {
              padding-top: 0;
            }

            [class*="vb0"],
            [vertical-bottom="0"] {
              padding-bottom: 0;
            }

            /* container styles */
            .w-container {
              position: relative;
              padding-left: var(--pp1);
              padding-right: var(--pp1);
              width: 100%;
              max-width: var(--mw1);
            }

            /* page padding */
            [class*="pp1"] {
              padding-left: var(--pp1);
              padding-right: var(--pp1);
            }

            [class*="pp0"] {
              padding-left: 0;
              padding-right: 0;
            }

            /* max width */
            [class*="mw1"] {
              max-width: var(--mw1);
            }

            [class*="mw2"] {
              max-width: var(--mw2);
            }

            [class*="mw0"] {
              max-width: none;
            }

            /* stroke width */
            [class*="sw1"] {
              --text-stroke-width: var(--sw1);
            }

            [class*="sw2"] {
              --text-stroke-width: var(--sw2);
            }

            [class*="sw0"] {
              --text-stroke-width: 0px;
            }

            /* border radius */
            [class*="br1"] {
              --border-radius: var(--br1);
            }

            [class*="br2"] {
              --border-radius: var(--br2);
            }

            [class*="br3"] {
              --border-radius: var(--br3);
            }

            [class*="br0"] {
              --border-radius: 0rem;
            }

            /* border width */
            [class*="bw1"] {
              border-width: var(--bw1);
              border-style: solid;
            }

            [class*="bw2"] {
              border-width: var(--bw2);
              border-style: solid;
            }

            [class*="bw0"] {
              border-width: 0;
            }

            /* border direction */
            /**%{{border: top}**/
            [class*="bw1t"],
            [class*="bw2t"] {
              border-bottom-width: 0;
              border-left-width: 0;
              border-right-width: 0;
            }

            /**}%**/
            /**%{{border: bottom}**/
            [class*="bw1b"],
            [class*="bw2b"] {
              border-top-width: 0;
              border-left-width: 0;
              border-right-width: 0;
            }

            /**}%**/
            /**%{{border: left}**/
            [class*="bw1l"],
            [class*="bw2l"] {
              border-top-width: 0;
              border-bottom-width: 0;
              border-right-width: 0;
            }

            /**}%**/
            /**%{{border: right}**/
            [class*="bw1r"],
            [class*="bw2r"] {
              border-top-width: 0;
              border-bottom-width: 0;
              border-left-width: 0;
            }

            /**}%**/
            /**%{{border: vertical}**/
            [class*="bw1v"],
            [class*="bw2v"] {
              border-left-width: 0;
              border-right-width: 0;
            }

            /**}%**/
            /**%{{border: horizontal}**/
            [class*="bw1h"],
            [class*="bw2h"] {
              border-top-width: 0;
              border-bottom-width: 0;
            }

            /**}%**/
            /* pointer events */
            [class*="pe0"] {
              pointer-events: none;
            }

            [class*="pe1"] {
              pointer-events: auto;
            }

            /**%{{pointer-events: children}**/
            [class*="pe2"] {
              pointer-events: none;
            }

            [class*="pe2"]>* {
              pointer-events: auto;
            }

            /**}%**/
            /* icon styles */
            /**%#**/
            [class*="ic1"] svg,
            [class*="ic2"] svg {
              width: 100% !important;
              height: 100% !important;
            }

            /**#%**/
            [class*="ic1"] * {
              fill: currentColor !important;
            }

            [class*="ic2"] * {
              stroke: currentColor !important;
            }

            /* cover */
            [class*="cf1"] {
              width: 100%;
              height: 100%;
            }

            [class*="ca1"] {
              position: absolute;
              width: 100%;
              height: 100%;
              top: 0;
              left: 0;
            }
          </style>
        </div> -->
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
      <!-- <div data-animation="default" data-collapse="medium" data-duration="400" data-easing="ease" data-easing2="ease" role="banner" class="navbar-logo-left-container shadow-three w-nav">
        <div class="container">
          <div class="navbar-wrapper">
            <a href="/" class="navbar-brand w-nav-brand">
              <img src="images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29.webp" loading="lazy" sizes="(max-width: 479px) 140px, 150px" srcset="images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-500.webp 500w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-800.webp 800w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-1080.webp 1080w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-1600.webp 1600w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-2000.webp 2000w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-2600.webp 2600w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29-p-3200.webp 3200w, images/6511e23b756346924af9d82c_One_Colour_Black_Horizontal_Logo%20%282%29.webp 6868w" alt="">
            </a>

          </div>
        </div>
      </div> -->
      <main class="page_main">
        <div class="sec-2">
          <img src="images/header-logo.svg" loading="lazy" sizes="(max-width: 479px) 100px, (max-width: 991px) 150px, 250px"  alt="Archeo stories logo" class="travel">
          <div class="mob-map"></div>
          <div class="mapp"></div>
          <div class="sec-2-main">
            <div class="rel _100 _2">
              <div class="left">
                <h2 class="f4">HI THERE,</h2>
                <div class="rot">
                  <h1 class="fs0 f4">WE'RE <br>MAMMOTH </h1>
                </div>
                <div class="text-block2">
                  <h4 class="tt2">A Full-Service creative agency with SPIRIT, specializing in tourism, food and beverage AND MORE.</h4>
                </div>
              </div>
              <div class="_1--right">
                <img src="images/mountains.webp" loading="lazy" alt="Mountains image" class="right-image">
                <img src="images/second-img.webp" loading="lazy" sizes="(max-width: 767px) 100vw, (max-width: 1919px) 35vw, 400px" alt="" class="yk-map multiply">
              </div>
            </div>
            <div class="rel _100 _2 second">
              <div class="man-wrap">
                <img src="images/tourist.webp" loading="lazy" alt="" class="Tourist man">
              </div>
              <div class="left _2">
                <div class="right-align mob">
                  <div class="pt1">
                    <p class="p">We’re an eclectic bunch of creative thinkers and doers that help clients enter new markets, extend product lines and elevate their businesses to the next level.</p>
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
            <div  class="sub-slider w-slider">
              <div class="w-slider-mask">
                <div class="w-slide">
                  <div class="slide-sub tbb">
                    <div class="slide-t-holder">
                      <div class="t-hold-sub">
                        <div>
                          <div class="tagline">FOOD &amp; BEVERAGE</div>
                        </div>
                        <div>
                          <h6 class="slide-title">Lorem Ipsum is simply dummy text of the printing and typesetting industr</h6>
                        </div>
                        <div>
                          <div class="sub-title">Lorem Ipsum is simply</div>
                          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industr</p>
                        </div>
                        <div>
                          <div class="sub-title">Lorem Ipsum is simply</div>
                          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industr</p>
                        </div>
                      </div>
                      <div>
                        <div class="tagline _2">Lorem Ipsum is simply</div>
                      </div>
                    </div>
                    <div class="slide-i-holder">
                      <img sizes="(max-width: 479px) 100vw, (max-width: 767px) 80vw, (max-width: 991px) 40vw, 45vw"  alt="" src="images/slider-1.webp" loading="lazy" class="i">
                    </div>
                  </div>
                </div>
                <div class="w-slide">
                  <div class="slide-sub ab">
                    <div class="slide-t-holder">
                      <div class="t-hold-sub">
                        <div>
                          <div class="tagline">FOOD &amp; BEVERAGE</div>
                        </div>
                        <div>
                          <h6 class="slide-title">New Identity for an Expanding Restaurant &amp; Liquor Retailer</h6>
                        </div>
                        <div>
                          <div class="sub-title">Mammoth Approach</div>
                          <p>Developed a multi-tiered brand strategy for the largest private liquor retailer North of 60, providing the foundation to build a new brand website with ease.</p>
                        </div>
                        <div>
                          <div class="sub-title">The Outcome</div>
                          <p>Consistent brand &amp; online experience for consumers across all three businesses.</p>
                        </div>
                      </div>
                      <div>
                        <div class="tagline _2">created by mammoth agency 2023</div>
                      </div>
                    </div>
                    <div class="slide-i-holder">
                      <img src="images/650465cea7b12ffeb656dc61_bb.webp" loading="lazy" sizes="(max-width: 479px) 100vw, (max-width: 767px) 80vw, (max-width: 991px) 40vw, 45vw" alt="" class="i con">
                    </div>
                  </div>
                </div>
                
              </div>
              <div class="sub-arrow left w-slider-arrow-left">
                <div class="black-ico w-icon-slider-left"></div>
              </div>
              <div class="sub-arrow right w-slider-arrow-right">
                <div class="black-ico w-icon-slider-right"></div>
              </div>
              <div class="h w-slider-nav"></div>
            </div>
          </div>
          <div class="wrapper">
            <div class="sec-2--li"></div>
            <div class="_100 see-more pt2 pb2">
              <div>
                <div class="f4 burgundy">
                  <h2>WANNA <br>SEE <br>MORE? </h2>
                </div>
                <div class="pt2">
                  <a href="/" class="btn w-inline-block">
                    <div>See More Projects</div>
                  </a>
                </div>
              </div>
            </div>
            <div class="horse-man">
              <div class="lesspad">
                <div class="rot-rev">
                  <h3 class="f2 tt2">Don’t get <br>trapped in <br>legacy branding </h3>
                </div>
              </div>
              <div class="horse-img multiply"></div>
            </div>
          </div>
        </div>
        <div class="sec-3">
          <div class="wrapper fvc">
            <div class="rel">
              <div class="pl aa">
                <div class="rot">
                  <h1 class="fs0 f4">REVIEWS</h1>
                </div>
              </div>
              <div class="_100 pt4">
                <div class="_80vw fc1">
                  <h1 class="tt2 tc">Don’t take it from us, here’s what clients have to say about working with Mammoth.</h1>
                </div>
              </div>
            </div>
            <img src="images/64fb5dc0eafa3fed194074e1_image_1042-removebg-preview.webp" loading="lazy" alt="" class="sec-3-img-2 multiply">
          </div>
        </div>
        <div class="sec-4">
          <div class="sec-4-bg multiply"></div>
          <div class="wrapper full mob">
            <div class="rel">
              <div class="slide-b-wrap _1">
                <div  class="test-slider _1 w-slider">
                  
                  <div class="w-slide">
                      <div class="test-inner">
                        <!-- <img sizes="(max-width: 479px) 80vw, 297.8125px" srcset="images/65051584a148878dfed621fb_Frame%20128-p-500.webp 500w, images/65051584a148878dfed621fb_Frame%20128-p-800.webp 800w, images/65051584a148878dfed621fb_Frame%20128-p-1080.webp 1080w, images/65051584a148878dfed621fb_Frame%20128-p-1600.webp 1600w, images/65051584a148878dfed621fb_Frame%20128.webp 1866w" alt="" src="images/65051584a148878dfed621fb_Frame%20128.webp" loading="lazy" class="test--i"> -->
                        <p class="p _80">"Mammoth steered our ownership group towards a single vision that bridged three businesses into one, giving a cohesive brand experience." <br>
                          <span class="co-name">- Big Bear Co.</span>
                        </p>
                      </div>
                    </div>
                  <div class="w-slider-nav w-round"></div>
                </div>
                <div class="sec-4-t1 rot">
                  <div class="ch-smal">
                    <h3 class="f2 tt2">HUNT DOWN LONG-TERM RESULTS</h3>
                  </div>
                </div>
              </div>
              <div class="slide-b-wrap _2">
                <div class="test-slider _2 w-slider" >
                  <div class="w-slider-mask">
                    <div class="w-slide">
                      <div class="test-inner">
                        <img sizes="(max-width: 479px) 80vw, 297.8125px"  alt="" src="images/650473e15204616247ec5eb8_Frame%20132.webp" loading="lazy" class="test--i">
                        <p class="p _80">"The Mammoth team helped bring my vision into reality, honouring indigenous communities and creating a platform for education and storytelling for #Reconcilation!" <br>
                          <span class="co-name">- First People's Coffee</span>
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
                  <h2 class="f2 tt2 pb2">Mine your <br>Golden Ideas <br>with Mammoth <br>Agency </h2>
                </div>
              </div>
            </div>
          </div>
          <div class="sec-4-i2 multiply"></div>
          <div class="mob-map-1"></div>
          <div class="mob-map-2"></div>
        </div>
        <div class="sec-5 _1">
          <div class="white-rot"></div>
          <div class="wrapper padding">
            <div class="half">
              <div class="gd1--gp2 left">
                <h1 class="tt2">Discover what our new Calgary clients are raving about!</h1>
                <p class="p">We now offer our full branding, website development, and packaging design services across Alberta! From the Yukon to your doorstep — find out how Mammoth can help your business. #BeyondTheYukon</p>
                <div class="btn calendly w-embed w-script">

                </div>
              </div>
              <div id="w-node-_47034ffa-3d5c-f285-f176-a80e3188370b-570e3a99" class="rel fvc">
                <img src="images/64fa2b4e140eb5798a6633ba_image_1084-removebg-preview.webp" loading="lazy" alt="" class="multiply sec-5-i1">
                <img src="images/6501d8192ced15622456afae_matt.png" loading="lazy" alt="" class="matt-img">
              </div>
            </div>
          </div>
        </div>
        <div class="sec-5 tw _2">
          <div class="white-rot _2"></div>
          <div class="wrapper padding">
            <div class="_800 lra zz">
              <div class="fvc tc">
                <h2 class="tt2">STILL UNSURE IF THIS APPLIES TO YOUR BUSINESS? TAKE OUR FREE QUIZ, NO STRINGS ATTACHED!</h2>
                <div class="pt2 pb2">
                  <p class="p w2">Take our free quiz below and learn how Mammoth can help your business venture beyond the ordinary.</p>
                </div>
                <a href="https://form.typeform.com/to/Bs1JxY2a" target="_blank" class="btn yellow w-inline-block">
                  <div>TAKE THE QUIZ</div>
                </a>
              </div>
            </div>
          </div>
          <img src="images/64f7a0d7bdbef7009ade0be3_image%20957.webp" loading="lazy" sizes="(max-width: 767px) 60vw, 400px"  alt="" class="sec-5-left multiply">
          <img src="images/64f7a0d78ff0813757143544_image%201045.webp" loading="lazy" sizes="(max-width: 767px) 200px, 300px"  alt="" class="sec-5-right multiply">
        </div>
        <div class="sec-6">
          <div class="wrapper padding">
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
                <div id="w-node-_75f3c98f-f27f-ff4f-6582-a18d392489e1-570e3a99" class="form-block w-form">
                  <!-- <form id="wf-form-OOT-Footer-Form" name="wf-form-OOT-Footer-Form" data-name="OOT Footer Form" method="get" class="form" data-wf-page-id="64f79baf8ff08137570e3a99" data-wf-element-id="75f3c98f-f27f-ff4f-6582-a18d392489e2">
                    <div class="right-align pb2 mob">
                      <h2>Wanna chat? <br>Send us a note! </h2>
                    </div>
                    <input class="field w-input" maxlength="256" name="name" data-name="Name" placeholder="Your Name" type="text" id="name" required="">
                    <input class="field w-input" maxlength="256" name="email" data-name="Email" placeholder="Your email" type="email" id="email" required="">
                    <textarea id="Message" name="Message" maxlength="5000" data-name="Message" placeholder="Message" required="" class="field ta textarea w-input"></textarea>
                    <input type="submit" data-wait="Please wait..." class="btn calendly w-button" value="Submit">
                  </form> -->
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
          </div>
          <div class="sec-6-bg">
            <div class="sec-6-boat multiply"></div>
          </div>
        </div>
      </main>
    </div>
