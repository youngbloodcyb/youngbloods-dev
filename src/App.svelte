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
    <div id="main-text-box" class="w-5/6 lg:w-1/3 text-left">
      <h1 id="fade-1" class="lowercase text-5xl sm:text-6xl italic font-semibold">we are <span class="text-red"><strike>developers</strike></span></h1>
      <h1 id="fade-2" class="lowercase text-5xl sm:text-6xl italic font-semibold">we are brothers</h1>
    </div>
  </div>
  
  <footer class="py-6 flex justify-end items-end justify-items-end font-roboto self-center absolute bottom-0 italic">
    <nav>
        <ul class="flex items-center gap-6">
            <li>
                <a href="https://www.linkedin.com/in/cameron-youngblood/" class="transition-all duration-300 ease-in-out rounded-2xl hover:p-2 hover:text-red hover:font-extrabold hover:text-lg">linkedin</a>
            </li>
            <li>
                <a href="https://github.com/youngbloodcyb" class="transition-all duration-300 ease-in-out rounded-2xl hover:p-2 hover:text-red hover:font-extrabold hover:text-lg">github</a>
            </li>
            <li>
                <a href="https://twitter.com/youngbloodcyb" class="transition-all duration-300 ease-in-out rounded-2xl hover:p-2 hover:text-red hover:font-extrabold hover:text-lg">twitter</a>
            </li>
            <li>
                <a href="https://medium.com/@youngbloodcyb" class="transition-all duration-300 ease-in-out rounded-2xl hover:p-2 hover:text-red hover:font-extrabold hover:text-lg">medium</a>
            </li>
        </ul>
    </nav>
  </footer>
</main>

<style>
  #fade-1 { animation: fadeIn 3s; }
  #fade-2 { animation: fadeIn2 4s; }

  @keyframes fadeIn {
    0% {opacity: 0;}
    100% { opacity: 1;}
  }

  @keyframes fadeIn2 {
    0% {opacity: 0;}
    50% {opacity: 0;}
    100% { opacity: 1;}
  }

</style>