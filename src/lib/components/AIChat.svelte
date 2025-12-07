<script lang="ts">
  // AI Chat Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-blue-500 font-medium">AI Chat</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-12">Ask Amie to do or find anything</h2>
  
  <div class="grid lg:grid-cols-2 gap-16 mb-24">
    <div>
      <div class="flex gap-4 mb-8">
        <div class="text-6xl text-gray-200 font-serif leading-none">“</div>
        <div>
          <p class="text-lg font-medium text-gray-900 mb-2">
            It's like ChatGPT, but it has full context about my company and job. It's integrated with Gcal and Gmail. So no more copy+pasting.
          </p>
          <div class="text-sm text-gray-500">Dennis Müller • Founder, Amie</div>
        </div>
      </div>
      
      <div class="relative mt-12 bg-gray-50 p-6 rounded-xl border border-gray-100">
        <div class="absolute -top-8 left-0 text-green-500 font-handwriting transform -rotate-6 text-sm flex items-center gap-1">
          This is a real review we got 
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M10 10l5 5m0 0l-5 5m5-5H3" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </div>
        
        <!-- Email Mockup -->
        <div class="bg-white shadow-sm rounded border border-gray-200 p-4 text-sm">
           <div class="border-b border-gray-100 pb-2 mb-2">
             <div class="flex gap-2 mb-1"><span class="text-gray-500 w-12">From</span> <span class="font-medium">Nish Budhraja</span></div>
             <div class="flex gap-2"><span class="text-gray-500 w-12">Subject</span> <span class="font-medium">Feedback - Loving the new Amie!</span></div>
           </div>
           <div class="space-y-3 text-gray-700">
             <p>You absolutely cooked - loving the new Amie. Was an instant upgrade to Business for me. I had churned last year but you won me back.</p>
             <p>With tasks / calendar / meeting recordings, you replaced Superlist, Notion Calendar, and Granola for me.</p>
             <p class="font-bold">All-in-one solution has enabled some pretty magical workflows for me:</p>
             <p>1. Record meeting → follow up tasks logged → add tasks to my lists → add to calendar<br>
             2. Have a meeting → have AI assistant write follow up email → AI assistant has all of the context needed → writes amazing email → send directly from Amie</p>
           </div>
        </div>
        <div class="text-center mt-4 text-xs text-gray-400">Nish really was too kind with his review.</div>
      </div>
    </div>
    
    <!-- Chat Actions Visualization -->
    <div>
      <h3 class="font-bold text-lg mb-4">Chat Actions</h3>
      <p class="text-gray-600 mb-8 text-sm">
        Saving you time is our priority. And chat actions is the way we achieve that. You can ask Amie to draft emails, create or update meetings, rewrite summaries, create mind maps from summaries, and more.
      </p>
      
      <div class="bg-blue-50 p-3 rounded-lg inline-block mb-8 text-sm text-blue-800">
        <span class="font-bold">One of my favorite use cases:</span> "I'm sick, move everything to Thursday." and Amie will do it for you.
      </div>
    </div>
  </div>
  
  <!-- Large Interface Image for Chat Actions -->
  <div class="bg-gradient-to-b from-gray-800 to-gray-900 rounded-2xl p-2 md:p-8 shadow-2xl overflow-hidden">
    <div class="flex justify-between text-white/70 text-sm mb-4 px-4">
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-red-400 rounded-full"></div> Send follow-up emails</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-purple-400 rounded-full"></div> Combine actions</div>
       <div class="flex items-center gap-2"><div class="w-4 h-4 bg-blue-400 rounded-full"></div> Create Linear tickets</div>
    </div>
    
    <div class="bg-white rounded-t-xl overflow-hidden h-[500px] relative">
       <!-- Mock UI -->
       <div class="p-6">
         <div class="max-w-2xl mx-auto bg-white shadow-xl rounded-xl border border-gray-200 overflow-hidden">
           <div class="bg-gray-50 p-3 border-b border-gray-200 font-medium text-sm text-gray-700">
             Email everyone from my last meeting thanking them for joining, then create Linear tickets
           </div>
           <div class="p-6 space-y-4">
             <div class="flex gap-3">
               <div class="w-8 h-8 bg-gray-200 rounded-full shrink-0"></div>
               <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                 I'll help you draft an email to thank the participants from your "Amie x Linear" meeting, which was your most recent meeting.
               </div>
             </div>
             
             <!-- Email Draft Card -->
             <div class="border border-gray-200 rounded-lg p-4 ml-11">
               <div class="text-xs text-gray-500 mb-2">To: All participants</div>
               <div class="text-xs text-gray-500 mb-4">Subject: Thank you for joining the Amie UX test</div>
               <div class="text-sm text-gray-800 space-y-2">
                 <p>Hi everyone,</p>
                 <p>I wanted to thank you all for participating in our Amie UX test meeting yesterday. Your feedback on the new dashboard view, meeting notes feature, and task management was incredibly valuable.</p>
                 <p>Best,<br>Stefan</p>
               </div>
             </div>
             
             <div class="flex gap-3">
               <div class="w-8 h-8 bg-gray-200 rounded-full shrink-0"></div>
               <div class="bg-gray-100 rounded-2xl rounded-tl-none p-3 text-sm text-gray-700 max-w-[80%]">
                 Now I'll create a Linear issue to track the feedback:
               </div>
             </div>
             
             <!-- Linear Ticket Card -->
             <div class="border border-gray-200 rounded-lg p-4 ml-11 flex items-center gap-3">
               <div class="w-6 h-6 bg-blue-600 rounded"></div>
               <div class="text-sm font-medium">Connect to Linear</div>
               <button class="ml-auto text-xs bg-gray-100 px-2 py-1 rounded">Connect</button>
             </div>
           </div>
         </div>
       </div>
    </div>
  </div>
</section>
