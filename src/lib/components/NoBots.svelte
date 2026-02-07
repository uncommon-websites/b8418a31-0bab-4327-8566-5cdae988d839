<script lang="ts">
  // No Bots Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">Zero-friction execution</h2>
        <p class="text-gray-600 mb-8">
          Seren works in the background, weaving your data and orchestrating your workflow without you ever having to leave your IDE or terminal.
        </p>
        
        <ul class="space-y-4">
          {#each ['Auto-syncs GitHub PRs with Notion docs', 'Orchestrates Linear tasks from Slack threads', 'Generates technical specs from code changes', 'Eliminates manual status updates across tools'] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-primary-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-primary-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Laptop/Screen Mockup -->
        <div class="bg-gradient-to-br from-primary-100 to-gray-100 rounded-2xl p-8 shadow-lg">
           <div class="bg-gray-900 rounded-xl overflow-hidden shadow-2xl relative aspect-video flex items-center justify-center">
              <!-- Command Palette UI -->
              <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-white rounded-lg shadow-2xl border border-gray-200 z-10 w-3/4 p-4">
                 <div class="flex items-center gap-3 border-b border-gray-100 pb-3 mb-3">
                   <div class="text-primary-600">
                     <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
                   </div>
                   <div class="text-gray-400 text-sm">Orchestrate...</div>
                 </div>
                 <div class="space-y-2">
                   <div class="flex items-center justify-between bg-primary-50 p-2 rounded border border-primary-100">
                     <div class="flex items-center gap-2">
                       <span class="text-xs font-bold text-primary-600">EXECUTE</span>
                       <span class="text-sm text-gray-900">Sync PR #892 with Notion roadmap</span>
                     </div>
                     <span class="text-[10px] text-gray-400 font-mono">⌘↵</span>
                   </div>
                   <div class="flex items-center justify-between p-2 rounded">
                     <div class="flex items-center gap-2">
                       <span class="text-xs font-bold text-gray-400">WEAVE</span>
                       <span class="text-sm text-gray-700">Connect Slack thread to Linear issue</span>
                     </div>
                     <span class="text-[10px] text-gray-400 font-mono">⌘W</span>
                   </div>
                 </div>
              </div>

              <!-- Fake Code Background -->
              <div class="w-full h-full p-4 font-mono text-[10px] text-gray-500 overflow-hidden opacity-30">
                <pre>
export async function orchestrate(data) &#123;
  const weave = await seren.weave(data.source, data.target);
  if (weave.kinetic) &#123;
    return await seren.execute(weave.plan);
  &#125;
&#125;

// Kinetic data weaving in action
const pr = await github.getPR(892);
await seren.sync(pr, notion.roadmap);
                </pre>
              </div>
           </div>
        </div>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-primary-50 rounded-xl border border-primary-100">
      <p class="text-sm text-primary-800">
        <span class="font-bold">Seren has completely eliminated the "where did we talk about this?" problem.</span> It weaves our technical decisions directly into our documentation and task management. It's the first tool that actually feels like it's working for us, not the other way around.
      </p>
      <div class="mt-2 text-xs text-primary-600 font-medium">Marcus Thorne • Lead Engineer @ Railway</div>
    </div>
  </div>
</section>
