<svelte:head>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
</svelte:head>

<div class="fixed inset-0 overflow-hidden pointer-events-none z-0">
  <div class="absolute top-0 right-0 w-[600px] h-[600px] bg-[#FD366E] opacity-10 blur-[150px] rounded-full"></div>
  <div class="absolute bottom-0 left-0 w-[500px] h-[500px] bg-[#8B5CF6] opacity-10 blur-[150px] rounded-full"></div>
</div>

<div class="relative z-10 min-h-screen">
  <main class="px-16 py-24">
    <div class="max-w-5xl">
      <div class="mb-4 text-[#FD366E] font-semibold text-sm tracking-wider uppercase">Application</div>
      
      <h1 class="text-7xl font-black mb-16 leading-[1.1] tracking-tight">
        Why <span class="gradient-text">Appwrite</span>
      </h1>

      <div class="space-y-8 text-[17px] text-gray-300 leading-[1.8] font-medium">
        <p class="text-xl text-white">
          I'm <a href="https://www.siddharththakkar.xyz/" target="_blank" class="text-[#FD366E] hover:text-[#FF8A9B] transition-colors">Sid</a>, and Appwrite has been my go-to tool for every mobile build I've started. It's not just a backend platform, it's the reason I dove deep into Svelte, learned its internals, and raised PRs to give back to the ecosystem that made building so effortless.
        </p>

        <p>
          The Developer Advocate role feels like it was written for someone like me. I'm an aggressive builder who thrives on shipping fast, learning faster, and documenting everything in between. Whether it's <a href="https://quackstack.siddharththakkar.xyz/" target="_blank" class="text-[#FD366E] hover:text-[#FF8A9B] transition-colors">QuackStack</a> (my AI CLI tool that indexes codebases, generates embeddings, and lets you chat with your code using any AI provider) or <a href="https://glitchcn-ui.vercel.app/" target="_blank" class="text-[#FD366E] hover:text-[#FF8A9B] transition-colors">Glitchcn/ui</a> (my cyberpunk take on component libraries), I'm constantly pushing boundaries.
        </p>

        <p>
          I don't just build useful tools, I jump on trends, memes, and hype cycles because that's where the fun is. When "justfuckinguse.xyz" was trending, I built <a href="https://justfuckinguseanything.vercel.app" target="_blank" class="text-[#FD366E] hover:text-[#FF8A9B] transition-colors">justfuckinguseanything.vercel.app</a> to let people create aggressive landing pages. When people kept posting "just got a new Mac, what should I install," I wrote a <a href="https://devbackup.vercel.app/" target="_blank" class="text-[#FD366E] hover:text-[#FF8A9B] transition-colors">bash script</a> to backup and migrate entire setups in a single tar.gz file. I'm a do-er, and I love every second of it.
        </p>

        <p>
          Writing detailed blogs about these builds brings me immense joy. Breaking down complex ideas, sharing lessons learned, and helping others replicate what I've built is where I thrive. That's exactly what Developer Advocacy is about. Building in public, creating content that resonates, and empowering developers to do more with the tools they love.
        </p>

        <p class="text-white text-lg font-semibold">
          I'm not just looking for a role at Appwrite. I'm looking to amplify what you're already doing. I want to be the person who builds with your platform, writes about it, advocates for it, and helps the community fall in love with it the same way I did.
        </p>
      </div>

      <div class="mt-16 flex items-center gap-6">
        <a href="https://siddharththakkar.xyz" target="_blank" class="hover:text-[#FD366E] transition-colors">
          Who am I?
        </a>
        <div class="flex gap-4 text-sm text-gray-400">
          <a href="https://blog.siddharththakkar.xyz" target="_blank" class="hover:text-[#FD366E] transition-colors">Blog</a>
        </div>
      </div>
    </div>
  </main>

  <footer class="py-8 mt-20 px-16">
    <div class="max-w-5xl text-gray-500 text-sm">
      Built to impress
    </div>
  </footer>
</div>

<style>
  :global(*) {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  
  :global(body) {
    background: #0B0B0F;
    color: white;
    overflow-x: hidden;
  }
  
  :global(.gradient-text) {
    background: linear-gradient(135deg, #FD366E 0%, #FF8A9B 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
</style>