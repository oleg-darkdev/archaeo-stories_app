
<header style='z-index: 100;' class=" p-4">
	<div class="container flex justify-between h-16 mx-auto md:justify-center md:space-x-8">

    <slot name='left-links' />

		<a rel="noopener noreferrer" href="/" aria-label="Back to homepage" class="z-20 mx-auto flex items-center p-2">
      <img src="images/header-logo.svg" loading="lazy"   alt="Archeo stories logo" class="travel">
		</a>

		<slot name='right-links' />

		<button title="Button" type="button" class="p-4 md:hidden">
			<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6 text-gray-800">
				<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
			</svg>
		</button>
	</div>
</header>


<style>


@media screen and (min-width: 767px) {
  .travel {
    z-index: 5;
    width: 200px;
    bottom: auto;
    right: auto;
  }
}


@media screen and (max-width: 767px) {
  .travel {
    z-index: 5;
    width: 160px;
    bottom: auto;
    right: auto;
  }
}

</style>
