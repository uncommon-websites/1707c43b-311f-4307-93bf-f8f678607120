<script>
  export let active = "Product";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <svg width="32" height="32" viewBox="0 0 93 92" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M46.2451 17.9688C36.2169 17.9688 28.0872 9.92388 28.0872 0H15.982C15.982 16.5399 29.5311 29.9479 46.2451 29.9479C62.9591 29.9479 76.5083 16.5399 76.5083 0H64.403C64.403 9.92388 56.2734 17.9688 46.2451 17.9688ZM28.0872 91.0417C28.0872 81.1179 36.2169 73.0729 46.2451 73.0729C56.2734 73.0729 64.403 81.1179 64.403 91.0417H76.5083C76.5083 74.5018 62.9591 61.0937 46.2451 61.0937C29.5311 61.0937 15.982 74.5018 15.982 91.0417H28.0872ZM18.403 45.5208C18.403 35.597 10.2735 27.5521 0.245117 27.5521V15.5729C16.959 15.5729 30.5083 28.981 30.5083 45.5208C30.5083 62.0607 16.959 75.4688 0.245117 75.4688V63.4896C10.2735 63.4896 18.403 55.4446 18.403 45.5208ZM74.0872 45.5208C74.0872 35.597 82.2169 27.5521 92.2451 27.5521V15.5729C75.5311 15.5729 61.982 28.981 61.982 45.5208C61.982 62.0607 75.5311 75.4688 92.2451 75.4688V63.4896C82.2169 63.4896 74.0872 55.4446 74.0872 45.5208Z" fill="#0A0D12"/>
        </svg>
        <span class="text-xl font-semibold tracking-tight font-sans">DiligenceSquared</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["Product", "How It Works", "Pricing", "About"] as item}
          <a href="#{item.toLowerCase().replace(/\s+/g, '-')}" class="text-sm font-medium text-gray-600 hover:text-primary-600 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium text-gray-900 hover:text-primary-600">
        Log in
      </a>
      <a href="#demo" class="rounded-full bg-primary-600 px-4 py-2 text-sm font-medium text-white hover:bg-primary-700 transition-colors">
        Get Started
      </a>
    </div>
  </div>
</header>
