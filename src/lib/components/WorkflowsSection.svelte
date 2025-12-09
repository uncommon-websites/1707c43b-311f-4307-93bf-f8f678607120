<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section id="how-it-works" class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
                How DiligenceSquared<br />Delivers Fast, Quality Insights
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: AI-Moderated Interviews -->
            <div class="group">
                <div class="mb-6 bg-primary-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Expert Interview: SaaS Market Dynamics</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-green-700">
                                <Check size={12} /> <span class="text-gray-600">Interview in progress...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Market sizing questions</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Competitive landscape</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Growth drivers & risks</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-gray-900 mb-3">AI-Moderated Interviews</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Our AI conducts structured interviews with industry experts, customers, and competitors—capturing nuanced insights at scale while maintaining the rigor PE firms expect from traditional consulting.
                </p>
            </div>

            <!-- Card 2: Automated Synthesis -->
            <div class="group">
                <div class="mb-6 bg-primary-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Key Themes from 12 Expert Interviews</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">AI</div>
                            <span class="text-[10px] text-gray-400">Synthesis complete</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Theme</div>
                                <div class="col-span-2 text-right">Confidence</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-green-500 rounded-sm"></div> Market growing 25%+ YoY</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-secondary-500 rounded-sm"></div> Customer churn concerns</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-500 rounded-sm"></div> Strong competitive moat</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-5/6 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-gray-900 mb-3">Automated Synthesis</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Advanced AI analyzes interview transcripts, identifies key themes, and synthesizes findings into actionable insights—delivering the analysis depth of a BCG report in a fraction of the time.
                </p>
            </div>

            <!-- Card 3: Investor-Grade Deliverables -->
            <div class="group">
                <div class="mb-6 bg-primary-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">D²</div>
                            <span class="text-[10px] text-gray-500">CDD Report Ready</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Your commercial due diligence report is complete with executive summary, market analysis, and risk assessment.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-red-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">CDD_Report_Final.pdf</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Interview_Transcripts.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-gray-900 mb-3">Investor-Grade Deliverables</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Receive comprehensive CDD reports with executive summaries, market sizing, competitive analysis, and risk assessments—formatted to match the standards your investment committee expects.
                </p>
            </div>
        </div>
    </div>
</section>
