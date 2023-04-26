<script lang="ts">
  import { Prism } from '@svelteuidev/prism';
  import js from "/src/assets/Unofficial_JavaScript_logo_2.svg";
  const codeSvelte = `<div on:click={toggle}>`;
  const codeReact = `<button onClick={sayHello}>`;
  const codeJS = `element.addEventListener("click", myFunction);`;
  const exampleCode = 
  `
  <div class="w-[100%] relative flex flex-row">
		<a href="/" class="ml-1 text-4xl text-neutral-50">jake hackl</a>
		<ul class="align-items-center">
			<li><a href="/blog" class="text-4xl mr-3 ">blog</a></li>
			<li><a href="/about" class="btn text-4xl mr-0.5 font-bold text-right uppercase">about</a></li>
        </ul>
  </div>
  `;
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
<section id="slide-4" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2]">
  <div class="block psm">
    <Prism copy={false} language="javascript" code={codeJS}></Prism>
  </div>
  <a href="#slide-5" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-5" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2]">
  <div class="block psm">
    <Prism copy={false} language="svelte" code={codeReact}></Prism>
  </div>
  <a href="#slide-6" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-6" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2] text-[#282a36]">
  <div class="block psm">
    <Prism copy={false} language="svelte" code={codeSvelte}></Prism>
  </div>
  <a href="#slide-7" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-7" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2] text-[#282a36]">
  <div class="w-[100%] relative flex flex-row align-center bg-neutral-900 pt-2 pb-2 navbar">
		<a href="/" class="ml-1 text-4xl text-neutral-50 font-bold mr-auto uppercase">jake hackl</a>
		<ul class="hidden list-none sm:flex flex-row border-l-white align-items-center">
			<li><a href="/blog" class="text-4xl mr-3 text-neutral-50 font-bold text-right uppercase">blog</a></li>
			<li><a href="/about" class="btn hover:bg-neutral-800 hover:text-neutral-100 bg-neutral-50 text-neutral-900 text-4xl mr-0.5 font-bold text-right uppercase">about</a></li>
    </ul>
	</div>
  <a href="#slide-8" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-8" class="w-screen h-screen flex justify-center items-center flex-row bg-[#f8f8f2] text-[#282a36]">
  <div class="block psm-small">
    <Prism copy={false} language="svelte" code={exampleCode}></Prism>
  </div>
  <a href="#slide-9" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-9" class="w-screen h-screen justify-items-center items-center grid grid-flow-row bg-[#282a36]">
  <h1 class="text-7xl text-[#f8f8f2]">το τέλος</h1>
  <a href="#slide-10" class="w-screen h-screen absolute z-10"></a>
</section>
<section id="slide-10" class="w-screen h-screen justify-center items-center grid text-white bg-[#282a36] gap-0">
  <p>Ecma International. “ECMA-262 - Ecma International.” Ecma International, 15 July 2022, www.ecma-international.org/publications-and-standards/standards/ecma-262/. Accessed 18 Apr. 2023.</p>
  <p>Greif, Sacha, and Eric Burel. “State of JavaScript 2022.” Stateofjs.com, 2022, 2022.stateofjs.com/en-US/. Accessed 18 Apr. 2023.</p>
  <p>“Netscape.” Archive.org, 2023, web.archive.org/web/20070916144913/wp.netscape.com/newsref/pr/newsrelease67.html. Accessed 18 Apr. 2023.</p>
  <a href="#slide-1" class="w-screen h-screen absolute z-10"></a>
</section>
<style>
  .psm > :global(*) {
    font-size: 3rem;
    background-color: inherit;
  }
  .psm-small > :global(*) {
    font-size: 1.3rem;
    background-color: inherit;
  }
</style>