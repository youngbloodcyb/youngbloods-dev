<script>
  import "./app.css"
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;0,700;0,900;1,900&display=swap" rel="stylesheet">
</svelte:head>

<main id="main-bg" class="flex flex-col w-screen h-screen font-roboto bg-cream text-black">

  <div class="m-6">
    <img src="src/assets/logo-yb.png" alt="yb-logo" width="100">
  </div>

  <div class="flex justify-center items-center w-screen my-24">
    <div id="main-text-box" class="w-1/3 text-left">
      <h1 class="lowercase text-6xl italic font-semibold">we are <span class="text-red"><strike>developers</strike></span></h1>
      <h1 class="lowercase text-6xl italic font-semibold">we are brothers</h1>
    </div>
  </div>

</main>