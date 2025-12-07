<script lang="ts">
  // Integrations Section
</script>

<section class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <div class="mb-4">
      <span class="text-blue-500 font-medium">Integrations</span>
    </div>
    
    <h2 class="text-4xl font-bold mb-6">Keep your tools updated, with one click</h2>
    
    <p class="text-gray-600 max-w-3xl mx-auto mb-16">
      Too many tools require you to use them all the time to be useful. Amie works just as well in the background. The integrations with Google and Apple Calendar make sure every meeting gets recorded.
      <br><br>
      The Gmail integration lets us re-create your writing style. To AI-draft your emails just like you wrote it.
      <br><br>
      We know that you likely have a system of record already. We've built integrations with Slack, Notion, Hubspot and Pipedrive. So that you can get the summaries there with a few clicks.
    </p>
    
    <!-- Integration Diagram Mockup -->
    <div class="relative max-w-4xl mx-auto h-[400px] mb-16 flex items-center justify-center">
      <!-- Center Hub -->
      <div class="w-32 h-32 bg-gradient-to-br from-purple-500 to-pink-500 rounded-3xl shadow-2xl z-10 flex items-center justify-center">
        <div class="text-white font-bold text-4xl">A</div>
      </div>
      <div class="absolute bottom-28 text-gray-400 font-serif italic text-xl">via AMIE</div>
      
      <!-- Connections (Simplified with CSS) -->
      <div class="absolute inset-0 flex items-center justify-center">
         <!-- Left Side Icons -->
         <div class="absolute left-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-red-500 font-bold text-xl border border-gray-100">M</div>
         <div class="absolute left-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-500 font-bold text-xl border border-gray-100">C</div>
         <div class="absolute left-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-blue-400 font-bold text-xl border border-gray-100">Z</div>
         
         <!-- Right Side Icons -->
         <div class="absolute right-10 top-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-green-600 font-bold text-xl border border-gray-100">P</div>
         <div class="absolute right-10 bottom-10 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-black font-bold text-xl border border-gray-100">N</div>
         <div class="absolute right-0 top-1/2 -translate-y-1/2 w-12 h-12 bg-white shadow-lg rounded-xl flex items-center justify-center text-orange-500 font-bold text-xl border border-gray-100">H</div>
         
         <!-- Connecting Lines (SVG) -->
         <svg class="absolute inset-0 w-full h-full pointer-events-none -z-10 text-gray-200" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M350,200 C300,200 100,100 80,60" />
            <path d="M350,200 C300,200 100,300 80,340" />
            <path d="M350,200 C300,200 80,200 60,200" />
            
            <path d="M550,200 C600,200 800,100 820,60" />
            <path d="M550,200 C600,200 800,300 820,340" />
            <path d="M550,200 C600,200 820,200 840,200" />
         </svg>
      </div>
    </div>
    
    <p class="text-xs text-gray-400 mb-16">Export meeting notes to Pipedrive, Notion, Slack, Hubspot, Linear. Request integrations at care@amie.so</p>
    
    <!-- Integration List Grid -->
    <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-left max-w-4xl mx-auto">
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-orange-500 rounded flex items-center justify-center text-white font-bold text-xs">H</div>
        <div>
          <div class="font-bold text-sm">Hubspot</div>
          <div class="text-xs text-gray-500">Add to leads/meetings</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-black rounded flex items-center justify-center text-white font-bold text-xs">N</div>
        <div>
          <div class="font-bold text-sm">Notion</div>
          <div class="text-xs text-gray-500">Add to databases</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-purple-600 rounded flex items-center justify-center text-white font-bold text-xs">S</div>
        <div>
          <div class="font-bold text-sm">Slack</div>
          <div class="text-xs text-gray-500">Send to any channel or person</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-black rounded flex items-center justify-center text-white font-bold text-xs">L</div>
        <div>
          <div class="font-bold text-sm">Linear</div>
          <div class="text-xs text-gray-500">Create tickets from transcripts</div>
        </div>
      </div>
      <div class="flex items-start gap-3">
        <div class="w-8 h-8 bg-green-600 rounded flex items-center justify-center text-white font-bold text-xs">P</div>
        <div>
          <div class="font-bold text-sm">Pipedrive</div>
          <div class="text-xs text-gray-500">Add to leads/customers</div>
        </div>
      </div>
      <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-pink-500 rounded flex items-center justify-center text-white font-bold text-xs">A</div>
        <div>
          <div class="font-bold text-sm">Attio <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">Add to leads/customers</div>
        </div>
      </div>
      <!-- More items... truncated for brevity as per screenshot pattern -->
      <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-gray-400 rounded flex items-center justify-center text-white font-bold text-xs">P</div>
        <div>
          <div class="font-bold text-sm">Personio <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">Add to applicants</div>
        </div>
      </div>
       <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-purple-400 rounded flex items-center justify-center text-white font-bold text-xs">A</div>
        <div>
          <div class="font-bold text-sm">Ashby <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">Add to applicants</div>
        </div>
      </div>
       <div class="flex items-start gap-3 opacity-50">
        <div class="w-8 h-8 bg-green-400 rounded flex items-center justify-center text-white font-bold text-xs">G</div>
        <div>
          <div class="font-bold text-sm">Greenhouse <span class="font-normal text-gray-400">Soon</span></div>
          <div class="text-xs text-gray-500">Add to applicants</div>
        </div>
      </div>
    </div>
  </div>
</section>
