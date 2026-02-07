<script lang="ts">
  // Meeting Notes Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-primary-600 font-medium">Kinetic Data Weaving</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">Your data, finally in sync</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Orchestrates:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-black"></div> Notion</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-gray-800"></div> GitHub</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-400"></div> Slack</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-orange-500"></div> Linear</span>
  </div>

  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">Why Seren?</h3>
      <p class="text-gray-600 mb-4 leading-relaxed">
        Most tools are silos. You update a task in Linear, then manually copy the status to Notion, then ping the team on Slack. This fragmentation kills momentum.
      </p>
      <p class="text-gray-600 leading-relaxed">
        Seren weaves these threads together. When you merge a PR, Seren knows to update the documentation, notify the relevant stakeholders, and adjust the project timeline—automatically.
      </p>
    </div>
    
    <div class="space-y-8">
      <!-- Testimonial 1 -->
      <div class="bg-gray-50 p-6 rounded-2xl relative border border-gray-100">
        <div class="flex text-primary-500 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Alex Rivera</div>
            <div class="text-xs text-gray-500">CTO • Velocity Labs</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          Seren is the first tool that actually understands our development lifecycle. It’s like having a chief of staff for our codebase.
        </p>
      </div>

       <!-- Testimonial 2 -->
       <div class="bg-gray-50 p-6 rounded-2xl relative border border-gray-100">
        <div class="flex text-primary-500 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Sarah Chen</div>
            <div class="text-xs text-gray-500">Product Lead • Flux</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          The kinetic data weaving is magic. I don't have to ask for status updates anymore; Seren just shows me the ground truth across all our tools.
        </p>
      </div>
    </div>
  </div>

  <div class="max-w-3xl mb-12">
    <h3 class="font-bold text-lg mb-4">Real-time Orchestration</h3>
    <p class="text-gray-600 mb-4 leading-relaxed">
      Fragmented workflows are the silent killer of startups. Seren provides a unified execution layer that sits on top of your existing stack. It doesn't just sync data; it orchestrates action.
    </p>
  </div>

  <!-- Large Interface Image -->
  <div class="w-full bg-gray-950 rounded-2xl overflow-hidden shadow-2xl border border-gray-800 pt-2 md:pt-8 px-2 md:px-8 pb-0">
    <!-- Feature Tabs (Dark Header) -->
    <div class="flex justify-center gap-8 mb-6 text-sm font-medium text-gray-400">
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Data Weaving
      </div>
      <div class="flex items-center gap-2 text-white cursor-pointer">
        <div class="w-4 h-4 rounded-full bg-primary-500 text-white flex items-center justify-center text-[10px]">⚡</div>
        AI Orchestration
      </div>
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Unified Execution
      </div>
    </div>

    <!-- App Window -->
    <div class="bg-white rounded-t-lg overflow-hidden h-[500px] flex flex-col shadow-2xl relative">
       <!-- Header -->
       <div class="border-b border-gray-100 p-4 flex justify-between items-center bg-white z-10">
         <div class="flex items-center gap-3">
           <div class="w-8 h-8 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600">⚡</div>
           <div class="font-bold text-gray-900">Execution Stream</div>
         </div>
         <div class="flex items-center gap-3">
           <button class="text-xs font-medium text-gray-500">Live View</button>
           <button class="bg-primary-600 text-white px-3 py-1.5 rounded-md text-xs font-medium">Deploy Action</button>
         </div>
       </div>

       <!-- Content Area -->
       <div class="flex-1 overflow-y-auto bg-white p-6 md:p-8">
         <!-- Metadata -->
         <div class="grid grid-cols-[100px_1fr] gap-y-4 text-sm mb-8">
           <div class="text-gray-500">Status</div>
           <div class="flex items-center gap-2">
             <div class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></div>
             <span class="text-gray-900 font-medium">Orchestrating</span>
           </div>
           
           <div class="text-gray-500">Active Weaves</div>
           <div class="flex items-center gap-3">
             <span class="px-2 py-0.5 bg-gray-100 rounded text-xs">GitHub → Notion</span>
             <span class="px-2 py-0.5 bg-gray-100 rounded text-xs">Linear → Slack</span>
             <span class="px-2 py-0.5 bg-gray-100 rounded text-xs">Figma → Linear</span>
           </div>
         </div>
         
         <!-- Stream -->
         <div class="space-y-6">
            <div class="border-l-2 border-primary-200 pl-4 py-1">
              <div class="text-xs font-bold text-primary-500 uppercase mb-1">10:42 AM • GitHub</div>
              <div class="text-sm font-bold text-gray-900">PR #892 Merged: Auth Refactor</div>
              <div class="text-sm text-gray-600 mt-1">Seren is updating documentation in Notion and closing related Linear issues.</div>
            </div>
            
            <div class="border-l-2 border-gray-200 pl-4 py-1">
              <div class="text-xs font-bold text-gray-400 uppercase mb-1">10:43 AM • Notion</div>
              <div class="text-sm font-bold text-gray-900">Documentation Updated</div>
              <div class="text-sm text-gray-600 mt-1">"Auth Service Architecture" page refreshed with latest schema changes.</div>
            </div>

            <div class="border-l-2 border-blue-200 pl-4 py-1">
              <div class="text-xs font-bold text-blue-500 uppercase mb-1">10:45 AM • Slack</div>
              <div class="text-sm font-bold text-gray-900">Team Notified</div>
              <div class="text-sm text-gray-600 mt-1">Summary of changes posted to #engineering-updates.</div>
            </div>
         </div>
       </div>
    </div>
  </div>
</section>
