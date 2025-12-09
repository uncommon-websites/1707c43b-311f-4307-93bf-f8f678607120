<script>
    const expertTypes = [
        { name: "Industry Executives", icon: "👔", color: "bg-primary-600" },
        { name: "Former Operators", icon: "⚙️", color: "bg-primary-700" },
        { name: "Customers & End Users", icon: "👥", color: "bg-secondary-600" },
        { name: "Competitors", icon: "🎯", color: "bg-secondary-700" },
        { name: "Technology Experts", icon: "💻", color: "bg-primary-500" },
        { name: "Supply Chain Partners", icon: "🔗", color: "bg-gray-600" },
        { name: "Industry Analysts", icon: "📊", color: "bg-primary-800" },
        { name: "Regulatory Specialists", icon: "⚖️", color: "bg-gray-700" },
        { name: "Sales & Distribution", icon: "📈", color: "bg-secondary-500" },
        { name: "Product Managers", icon: "🛠️", color: "bg-primary-400" },
        { name: "Investors & Board Members", icon: "💼", color: "bg-gray-800" },
        { name: "Market Researchers", icon: "🔍", color: "bg-secondary-800" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">Vetted Expert Network</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                Access our curated network of industry experts across sectors. Every expert is vetted for relevant experience and compliance, ensuring you get high-quality insights from the right people for your diligence needs.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each expertTypes as expert}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${expert.color}`}>
                        {expert.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{expert.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
