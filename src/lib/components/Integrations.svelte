<script lang="ts">
  // Integrations Section
</script>

<section class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <div class="mb-4">
      <span class="text-primary-600 font-medium">Integrations</span>
    </div>
    
    <h2 class="text-4xl font-bold mb-6">Orchestrate your entire stack</h2>
    
    <p class="text-gray-600 max-w-3xl mx-auto mb-16">
      Seren doesn't just connect tools; it weaves them into a single execution engine. Our deep integrations with technical tools like GitHub, Linear, and Notion ensure that your data is always in sync and your team is always moving forward.
      <br><br>
      The kinetic data weaving technology maps relationships between your PRs, documentation, tasks, and communications, creating a unified context that powers real-time AI orchestration.
    </p>
    
    <!-- Integration Diagram Mockup -->
    <div class="relative max-w-4xl mx-auto h-[400px] mb-16 flex items-center justify-center">
      <!-- Center Hub -->
      <div class="w-32 h-32 bg-primary-600 rounded-3xl shadow-2xl z-10 flex items-center justify-center">
        <div class="text-white font-bold text-4xl">S</div>
      </div>
      <div class="absolute bottom-28 text-gray-400 font-serif italic text-xl">via SEREN</div>
      
      <!-- Connections (Simplified with CSS) -->
      <div class="absolute inset-0 flex items-center justify-center">
         <!-- Left Side Icons -->
         <div class="absolute left-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-black font-bold text-xl border border-gray-100" title="GitHub">G</div>
         <div class="absolute left-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-600 font-bold text-xl border border-gray-100" title="VS Code">V</div>
         <div class="absolute left-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-orange-500 font-bold text-xl border border-gray-100" title="Linear">L</div>
         
         <!-- Right Side Icons -->
         <div class="absolute right-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-black font-bold text-xl border border-gray-100" title="Notion">N</div>
         <div class="absolute right-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-400 font-bold text-xl border border-gray-100" title="Slack">S</div>
         <div class="absolute right-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-pink-500 font-bold text-xl border border-gray-100" title="Figma">F</div>
         
         <!-- Connecting Lines (SVG) -->
         <svg class="absolute inset-0 w-full h-full pointer-events-none -z-10 text-primary-100" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M350,200 C300,200 100,100 80,60" />
            <path d="M350,200 C300,200 100,300 80,340" />
            <path d="M350,200 C300,200 80,200 60,200" />
            
            <path d="M550,200 C600,200 800,100 820,60" />
            <path d="M550,200 C600,200 800,300 820,340" />
            <path d="M550,200 C600,200 820,200 840,200" />
         </svg>
      </div>
    </div>
    
    <p class="text-xs text-gray-400 mb-16">Orchestrate GitHub, Notion, Slack, Linear, Coda, and more. Request integrations at hello@seren.ai</p>
    
    <!-- Integration List Grid -->
    <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-left max-w-4xl mx-auto">
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-black rounded flex items-center justify-center text-white font-bold text-xs">G</div>
        <div>
          <div class="font-bold text-sm">GitHub</div>
          <div class="text-xs text-gray-500">Sync PRs and code changes</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-black rounded flex items-center justify-center text-white font-bold text-xs">N</div>
        <div>
          <div class="font-bold text-sm">Notion</div>
          <div class="text-xs text-gray-500">Update docs and roadmaps</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-blue-400 rounded flex items-center justify-center text-white font-bold text-xs">S</div>
        <div>
          <div class="font-bold text-sm">Slack</div>
          <div class="text-xs text-gray-500">Orchestrate from conversations</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-orange-500 rounded flex items-center justify-center text-white font-bold text-xs">L</div>
        <div>
          <div class="font-bold text-sm">Linear</div>
          <div class="text-xs text-gray-500">Automate task management</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-black rounded flex items-center justify-center text-white font-bold text-xs">C</div>
        <div>
          <div class="font-bold text-sm">Coda</div>
          <div class="text-xs text-gray-500">Sync data and workflows</div>
        </div>
      </div>
      <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center text-white font-bold text-xs">V</div>
        <div>
          <div class="font-bold text-sm">VS Code <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">In-IDE orchestration</div>
        </div>
      </div>
    </div>
  </div>
</section>
