<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section id="product" class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
                Built for PE Deal Teams,<br />Trusted by Diligence Veterans
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Speed -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-bold text-gray-900 mb-8">3-5 Day Turnaround</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <div class="text-6xl font-bold text-primary-600">3-5</div>
                        <div class="text-sm text-gray-500 text-center mt-2">days</div>
                        <div class="absolute -right-8 top-4 text-gray-300 line-through text-2xl">4-6 weeks</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Get investor-grade market research in days, not weeks. Fast enough to keep deals moving without sacrificing quality or depth of analysis.
                </p>
            </div>

            <!-- Expert Sourcing -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-bold text-gray-900 mb-8">Expert Sourcing</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-primary-200 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-primary-400"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    We identify and vet the right experts for your specific diligence needs—from former executives to customers to competitors.
                </p>
            </div>

            <!-- Guided Implementation -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Dedicated Support</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-blue-100 border-2 border-white flex items-center justify-center text-blue-600 text-xs">F</div>
                        <div class="h-10 w-10 rounded-full bg-green-100 border-2 border-white flex items-center justify-center text-green-600 text-xs">S</div>
                        <div class="h-10 w-10 rounded-full bg-purple-100 border-2 border-white flex items-center justify-center text-purple-600 text-xs">H</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    White-glove support from our team of Blackstone and BCG diligence veterans who understand PE workflows and timelines.
                </p>
            </div>

            <!-- Custom-Trained Models -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Diligence-Trained AI</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white text-xs">D²</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    AI models trained specifically on commercial due diligence frameworks, ensuring outputs match the rigor and structure PE firms expect from traditional consulting.
                </p>
            </div>

            <!-- Governance & Permissions -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Deal Team Controls</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold text-gray-400">DEAL</div>
                            <div class="text-[10px] font-bold text-primary-600">ACTIVE</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Deal-level access controls ensure sensitive diligence data stays within your team. Comprehensive audit trails and compliance-ready governance for regulated PE environments.
                </p>
            </div>

            <!-- Single Tenant Deployment -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Secure Infrastructure</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-primary-600 flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Enterprise-grade security with flexible deployment options. Private cloud or on-premise installations available for firms with strict data residency requirements.
                </p>
            </div>
        </div>
    </div>
</section>
