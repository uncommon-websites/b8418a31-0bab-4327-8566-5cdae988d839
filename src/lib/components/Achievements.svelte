<script lang="ts">
  let activeTab = 'Today';
  const tabs = ['Today', 'Day 3', 'Day 7'];
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-4xl font-bold mb-12">
      Accelerate your shipping cycle<br />with Seren <span class="bg-primary-100 text-primary-600 px-2 rounded">in just 7 days</span>
    </h2>
    
    <div class="flex justify-center gap-4 mb-16">
      {#each tabs as tab}
        <button 
          class="px-6 py-2 rounded-full text-sm font-medium transition-colors {activeTab === tab ? 'bg-primary-600 text-white' : 'bg-gray-200 text-gray-500 hover:bg-gray-300'}"
          on:click={() => activeTab = tab}
        >
          {tab}
        </button>
      {/each}
    </div>
    
    <div class="grid md:grid-cols-3 gap-8 text-left">
      <!-- Card 1 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Unify your stack</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Connect GitHub, Notion, and Slack in seconds</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Map your first kinetic data weave</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">See your fragmented tools become a unified engine</span>
          </li>
        </ul>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Orchestrate action</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Automate roadmap updates from PR merges</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Sync technical specs with live codebase changes</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Eliminate "where is this document?" from Slack</span>
          </li>
        </ul>
      </div>

      <!-- Card 3 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Ship at velocity</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Reduce context-switching by 70%</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Increase team shipping velocity by 3x</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-primary-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Focus on building, not tool maintenance</span>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="mt-16">
       <button class="bg-primary-600 text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-primary-700 transition-colors">
        Start shipping faster
      </button>
    </div>
  </div>
</section>
