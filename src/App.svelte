<script lang="ts">
  import js from "/src/assets/Unofficial_JavaScript_logo_2.svg";
</script>
<svelte:body on:click={document.body.requestFullscreen}></svelte:body>
<section id="slide-0" class="w-screen h-screen justify-items-center items-center grid grid-flow-row">
  <a href="#slide-1" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-1" class="w-screen h-screen justify-items-center items-center grid grid-flow-row bg-white">
  <h1 class="text-7xl -mb-32 text-black">Javascript</h1>
  <img src="{js}" alt="" width="256">
  <a href="#slide-2" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-2" class="w-screen h-screen flex justify-center items-center flex-row bg-black">
  <h1 class="text-7xl text-white">1995 at netscape</h1>
  <a href="#slide-3" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-3" class="w-screen h-screen flex justify-center items-center flex-row bg-[#282a36]">
  <h1 class="text-7xl text-[#f8f8f2]">History was made</h1>
  <a href="#slide-4" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-4" class="w-screen h-screen flex justify-center items-center flex-row bg-[#6272a4]">
  <h1 class="text-5xl text-[#f8f8f2]">element.addEventListener("click", myFunction);</h1>
  <a href="#slide-5" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-5" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2]">
  <div class="block">
    <h1 class="text-5xl text-[#6272a4]">{`<button onClick={sayHello}>`}</h1>
  </div>
  <a href="#slide-6" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-6" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2] text[#282a36]">
  <div class="block">
    <h1 class="text-5xl">{`<div on:click={toggle}>`}</h1>
  </div>
  <a href="#slide-1" class="w-screen h-screen absolute z-10"></a>
</section>