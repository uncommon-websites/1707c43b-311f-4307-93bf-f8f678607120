<script>
    import { FileText, Database, Settings, Search } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-bold text-gray-900 leading-tight max-w-4xl">
                Traditional consulting takes weeks and costs $50K+. <span class="text-primary-600">We deliver investor-grade insights in days.</span>
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <!-- Left: Image/Interface -->
            <div class="relative">
                <div class="relative rounded-lg overflow-hidden shadow-2xl bg-gray-900 aspect-[4/3]">
                    <img 
                        src="/generated/image-business-analyst-working-on-laptop-with--1765282025647-2.webp" 
                        alt="Modern due diligence workflow" 
                        class="absolute inset-0 w-full h-full object-cover"
                    />
                    
                    <!-- Floating Comparison Card -->
                    <div class="absolute inset-0 flex items-center justify-center p-8">
                        <div class="bg-white rounded-lg shadow-xl w-full max-w-md p-6">
                            <div class="grid grid-cols-2 gap-4 mb-4">
                                <div class="text-center p-3 bg-gray-50 rounded">
                                    <div class="text-xs text-gray-500 mb-1">Traditional CDD</div>
                                    <div class="text-2xl font-bold text-gray-400">4-6 weeks</div>
                                    <div class="text-xs text-gray-400 mt-1">$50K-$150K</div>
                                </div>
                                <div class="text-center p-3 bg-primary-50 rounded border-2 border-primary-600">
                                    <div class="text-xs text-primary-700 mb-1">DiligenceSquared</div>
                                    <div class="text-2xl font-bold text-primary-600">3-5 days</div>
                                    <div class="text-xs text-primary-600 mt-1">80% less cost</div>
                                </div>
                            </div>
                            <div class="text-xs text-gray-500 text-center">
                                Same quality insights, fraction of the time and cost
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right: Features List -->
            <div class="space-y-12">
                <h3 class="text-2xl font-bold text-gray-900">
                    Built by PE Diligence Veterans<br/>from Blackstone and BCG
                </h3>

                <div class="space-y-8">
                    {#each [
                        { id: '01', title: 'AI-moderated expert interviews', icon: Database },
                        { id: '02', title: 'Automated synthesis & analysis', icon: Search },
                        { id: '03', title: 'Investor-grade deliverables', icon: Settings },
                        { id: '04', title: 'Days, not weeks turnaround', icon: FileText }
                    ] as feature}
                        <div class="flex items-start gap-4 group cursor-pointer">
                            <div class="flex-shrink-0 relative">
                                <div class="h-10 w-10 rounded-full border-2 border-gray-200 flex items-center justify-center text-xs font-mono text-gray-500 group-hover:border-primary-600 group-hover:text-primary-600 transition-colors bg-white z-10 relative">
                                    {feature.id}
                                </div>
                                {#if feature.id !== '04'}
                                    <div class="absolute top-10 left-1/2 -translate-x-1/2 w-px h-8 bg-gray-100 -z-0"></div>
                                {/if}
                            </div>
                            <div class="pt-2">
                                <h4 class="text-lg text-gray-700 group-hover:text-gray-900 transition-colors">
                                    {feature.title}
                                </h4>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
</section>
