<script lang="ts">
  // AI Chat Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-primary-600 font-medium">AI Orchestration</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-12">Ask Seren to orchestrate your workflow</h2>
  
  <div class="grid lg:grid-cols-2 gap-16 mb-24">
    <div>
      <div class="flex gap-4 mb-8">
        <div class="text-6xl text-gray-200 font-serif leading-none">“</div>
        <div>
          <p class="text-lg font-medium text-gray-900 mb-2">
            It's like having a senior engineer who only does the boring stuff. It has full context about our codebase, our roadmap, and our Slack conversations.
          </p>
          <div class="text-sm text-gray-500">James Wilson • Founder, Seren</div>
        </div>
      </div>
      
      <div class="relative mt-12 bg-gray-50 p-6 rounded-xl border border-gray-100">
        <div class="absolute -top-8 left-0 text-primary-600 font-handwriting transform -rotate-6 text-sm flex items-center gap-1">
          Real feedback from our early builders
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M10 10l5 5m0 0l-5 5m5-5H3" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </div>
        
        <!-- Feedback Mockup -->
        <div class="bg-white shadow-sm rounded border border-gray-200 p-4 text-sm">
           <div class="border-b border-gray-100 pb-2 mb-2">
             <div class="flex gap-2 mb-1"><span class="text-gray-500 w-12">From</span> <span class="font-medium">Elena Rodriguez</span></div>
             <div class="flex gap-2"><span class="text-gray-500 w-12">Subject</span> <span class="font-medium">Seren is a game changer for us</span></div>
           </div>
           <div class="space-y-3 text-gray-700">
             <p>The AI orchestration is actually insane. I just merged a massive refactor and Seren automatically updated the technical specs in Notion and notified the frontend team in Slack with a summary of the API changes.</p>
             <p>It replaced three different manual sync processes for us. We're shipping so much faster now.</p>
             <p class="font-bold">The kinetic weaving is the killer feature:</p>
             <p>1. Merge PR → Sync Notion → Notify Slack<br>
             2. Slack discussion → Create Linear issue → Link to Figma spec</p>
           </div>
        </div>
      </div>
    </div>
    
    <!-- Chat Actions Visualization -->
    <div>
      <h3 class="font-bold text-lg mb-4">Orchestration Actions</h3>
      <p class="text-gray-600 mb-8 text-sm">
        Seren doesn't just answer questions; it executes tasks. You can ask Seren to sync documentation, update roadmaps, notify teams, or even draft changelogs based on your actual work.
      </p>
      
      <div class="bg-primary-50 p-3 rounded-lg inline-block mb-8 text-sm text-primary-800 border border-primary-100">
        <span class="font-bold">Try this:</span> "Summarize the last 3 PRs and update the #product-updates channel in Slack."
      </div>
    </div>
  </div>
  
  <!-- Large Interface Image for Chat Actions -->
  <div class="bg-gradient-to-b from-gray-900 to-black rounded-2xl p-2 md:p-8 shadow-2xl overflow-hidden">
    <div class="flex justify-between text-white/70 text-sm mb-4 px-4">
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-primary-500 rounded-full"></div> Sync Documentation</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-blue-400 rounded-full"></div> Update Roadmap</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-orange-400 rounded-full"></div> Create Linear Issues</div>
    </div>
    
    <div class="bg-white rounded-t-xl overflow-hidden h-[500px] relative">
       <!-- Mock UI -->
       <div class="p-6">
         <div class="max-w-2xl mx-auto bg-white shadow-xl rounded-xl border border-gray-200 overflow-hidden">
            <div class="bg-gray-50 p-3 border-b border-gray-200 font-medium text-sm text-gray-700 flex items-center gap-2">
              <span class="text-primary-600">⚡</span>
              Summarize PR #402 and update the technical spec in Notion
            </div>
            <div class="p-6 space-y-4">
              <div class="flex gap-3">
                <div class="w-8 h-8 bg-primary-100 rounded-full shrink-0 flex items-center justify-center text-primary-600 text-xs font-bold">S</div>
                <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                  I've analyzed PR #402 (Auth Refactor). Here's the summary and the plan for the Notion update.
                </div>
              </div>
              
              <!-- PR Summary Card -->
              <div class="border border-gray-200 rounded-lg p-4 ml-11">
                <div class="text-xs font-bold text-primary-600 mb-2 uppercase tracking-wider">PR #402 Summary</div>
                <div class="text-sm text-gray-800 space-y-2">
                  <ul class="list-disc pl-4 space-y-1">
                    <li>Implemented JWT-based authentication</li>
                    <li>Added middleware for role-based access control</li>
                    <li>Updated user schema to include 'last_login'</li>
                  </ul>
                </div>
              </div>
              
              <div class="flex gap-3">
                <div class="w-8 h-8 bg-primary-100 rounded-full shrink-0 flex items-center justify-center text-primary-600 text-xs font-bold">S</div>
                <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                  Updating "Technical Architecture" page in Notion...
                </div>
              </div>
              
              <!-- Notion Update Status -->
              <div class="border border-gray-200 rounded-lg p-4 ml-11 flex items-center gap-3">
                <div class="w-6 h-6 bg-black rounded flex items-center justify-center text-white text-[10px]">N</div>
                <div class="text-sm font-medium text-gray-900">Notion: Technical Architecture</div>
                <div class="ml-auto flex items-center gap-2 text-xs text-green-600 font-medium">
                  <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  Updated
                </div>
              </div>
            </div>
         </div>
       </div>
    </div>
  </div>
</section>
