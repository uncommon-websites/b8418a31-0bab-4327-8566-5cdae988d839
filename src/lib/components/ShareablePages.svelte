<script lang="ts">
  // Shareable Pages Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-primary-600 font-medium">Execution Contexts</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-6">Unified context for every project</h2>
  
  <p class="text-gray-600 max-w-3xl mb-8">
    Seren automatically organizes your fragmented data into unified execution contexts. Whether it's a specific project, a customer account, or a team initiative, Seren weaves all relevant information into a single stream.
  </p>
  
  <p class="text-gray-600 max-w-3xl mb-12">
    When you ask Seren a question, it doesn't just search; it understands the kinetic relationships between your tools. It knows that a Slack thread from Tuesday is related to a GitHub PR from Wednesday and a Notion doc from last month.
  </p>
  
  <div class="border-l-4 border-primary-500 pl-6 py-2 mb-16">
    <p class="text-lg font-medium text-gray-900 italic mb-2">
      Seren has finally solved the "where is that info?" problem. It's like having a perfectly organized brain for our entire company.
    </p>
    <div class="text-sm text-gray-500">Marcus Thorne • Lead Engineer @ Railway</div>
  </div>
  
  <!-- Interface Mockup -->
  <div class="bg-gray-200 rounded-t-2xl p-1 pb-0 overflow-hidden">
    <div class="bg-primary-900/20 p-2 flex gap-4 text-xs text-primary-900 font-medium justify-center">
      <div class="flex items-center gap-1">Unified Execution</div>
      <div class="flex items-center gap-1">Kinetic Weaving</div>
      <div class="flex items-center gap-1">Real-time Orchestration</div>
    </div>
    
    <div class="bg-white rounded-t-xl mt-2 p-8 h-[500px] flex shadow-2xl relative">
       <!-- Sidebar -->
       <div class="w-64 border-r border-gray-100 pr-4 hidden md:block">
         <div class="space-y-4">
           <!-- Fake List Items -->
           <div class="flex items-center justify-between text-sm text-gray-700 p-2 bg-blue-50 rounded">
             <div class="flex items-center gap-2">
               <div class="w-4 h-4 bg-blue-500 rounded-full"></div>
               <span>remote.com</span>
             </div>
             <span class="text-gray-400">1</span>
           </div>
           
           {#each ['getdecipher.com', 'screen.studio', 'dennis x adam', 'thymeholdings.com', 'bjmt.tax', 'craft.do', 'balint x dennis', 'sparkcapital.com', 'risecalendar.com', 'beam.ai', 'product'] as item}
            <div class="flex items-center justify-between text-sm text-gray-600 p-2 hover:bg-gray-50 rounded">
             <div class="flex items-center gap-2">
               <div class="w-4 h-4 bg-gray-200 rounded-full"></div>
               <span>{item}</span>
             </div>
             <span class="text-gray-400">1</span>
           </div>
           {/each}
         </div>
       </div>
       
       <!-- Main Area -->
       <div class="flex-1 pl-8 relative">
         <div class="absolute inset-0 flex items-center justify-center">
           <!-- Connecting Lines Annotation -->
           <div class="absolute left-[-40px] top-[100px] flex items-center">
             <span class="text-orange-500 text-xs font-bold mr-2">Company Pages</span>
             <div class="w-8 h-px bg-orange-500"></div>
             <div class="w-2 h-2 bg-orange-500 rounded-full"></div>
           </div>
           
           <div class="absolute left-[-40px] bottom-[100px] flex items-center">
             <span class="text-orange-500 text-xs font-bold mr-2">Custom Page</span>
             <div class="w-8 h-px bg-orange-500"></div>
             <div class="w-2 h-2 bg-orange-500 rounded-full"></div>
           </div>
         </div>
       </div>
    </div>
  </div>
  
  <!-- Bottom Grid -->
  <div class="grid md:grid-cols-3 gap-8 mt-16">
    <div>
      <h3 class="font-bold text-lg mb-2">By recurring event</h3>
      <p class="text-sm text-gray-600 mb-4">See how your project is progressing over time.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-3/4"></div>
          <div class="h-2 bg-gray-200 rounded w-1/2"></div>
        </div>
      </div>
    </div>
    
    <div>
      <h3 class="font-bold text-lg mb-2">By domain</h3>
      <p class="text-sm text-gray-600 mb-4">Make sure your customers get the care they deserve.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-full"></div>
          <div class="h-2 bg-gray-200 rounded w-2/3"></div>
        </div>
      </div>
    </div>
    
    <div>
      <h3 class="font-bold text-lg mb-2">Manually</h3>
      <p class="text-sm text-gray-600 mb-4">Keep track of topics, projects, or anything else.</p>
      <div class="bg-gray-50 p-4 rounded-lg border border-gray-100 h-24 flex items-center justify-center">
        <div class="w-full space-y-2">
          <div class="h-2 bg-gray-200 rounded w-1/2"></div>
          <div class="h-2 bg-gray-200 rounded w-3/4"></div>
        </div>
      </div>
    </div>
  </div>
</section>
