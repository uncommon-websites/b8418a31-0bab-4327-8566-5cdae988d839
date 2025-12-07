<script lang="ts">
  // Meeting Notes Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-green-600 font-medium">Meeting Notes</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">Summarize any meeting, without a bot</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Replaces:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-purple-900"></div> Fireflies</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-500"></div> Otter</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-green-500"></div> Fathom</span>
  </div>

  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">Why Amie?</h3>
      <p class="text-gray-600 mb-4 leading-relaxed">
        There are 27 meeting notes apps out there. If summaries is all you need, any of them will do. Many of them will even be cheaper.
      </p>
      <p class="text-gray-600 leading-relaxed">
        If you want to use them to become better at your job, you'll need Amie. An app that knows your conversations, should be able to take over your busy work.
      </p>
    </div>
    
    <div class="space-y-8">
      <!-- Testimonial 1 -->
      <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Quentin di Silvestro</div>
            <div class="text-xs text-gray-500">GTM Lead • beam.ai</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          We use Amie daily, and without it, we'd be at least 50% less productive. It helps me to follow-up faster, which directly translates into more revenue closed.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-purple-900 rounded-md"></div>
      </div>

       <!-- Testimonial 2 -->
       <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Arnaud Mun</div>
            <div class="text-xs text-gray-500">Co-founder • dev-id</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          Because of Amie we understand our customer's projects better: It summarizes all our meetings and we ask AI questions to speed up our workflow. There is not tool better than Amie to save time. And that is priceless
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-pink-600 rounded-md"></div>
      </div>
    </div>
  </div>

  <div class="max-w-3xl mb-12">
    <h3 class="font-bold text-lg mb-4">Summaries & Action Items</h3>
    <p class="text-gray-600 mb-4 leading-relaxed">
      When meetings go undocumented, progress rarely happens. Topics resurface week after week. But every conversation should move your team forward. AI summaries often miss the mark because they don't understand your business. Ours do, and turn every meeting into clear next steps.
    </p>
    <p class="text-gray-600 leading-relaxed">
      The common problem with AI summaries is that they don't know the context of your meeting and company. We ensure great summaries in two ways.
    </p>
  </div>

  <!-- Large Interface Image -->
  <div class="w-full bg-gray-900 rounded-2xl overflow-hidden shadow-2xl border border-gray-800 pt-2 md:pt-8 px-2 md:px-8 pb-0">
    <!-- Feature Tabs (Dark Header) -->
    <div class="flex justify-center gap-8 mb-6 text-sm font-medium text-gray-400">
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        No bots in calls
      </div>
      <div class="flex items-center gap-2 text-white cursor-pointer">
        <div class="w-4 h-4 rounded-full bg-white text-gray-900 flex items-center justify-center text-[10px]">✨</div>
        Summary
      </div>
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Action items
      </div>
    </div>

    <!-- App Window -->
    <div class="bg-white rounded-t-lg overflow-hidden h-[500px] flex flex-col shadow-2xl relative">
       <!-- Header -->
       <div class="border-b border-gray-100 p-4 flex justify-between items-center bg-white z-10">
         <div class="flex items-center gap-3">
           <div class="w-8 h-8 bg-orange-100 rounded-lg flex items-center justify-center text-orange-600">📅</div>
           <div class="font-bold text-gray-900">Week Kickoff</div>
         </div>
         <div class="flex items-center gap-3">
           <div class="flex -space-x-2">
             <div class="w-6 h-6 rounded-full bg-gray-200 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-gray-300 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-gray-400 border-2 border-white"></div>
           </div>
           <div class="h-4 w-px bg-gray-200"></div>
           <button class="text-xs font-medium text-gray-500">Copy link</button>
           <button class="bg-blue-600 text-white px-3 py-1.5 rounded-md text-xs font-medium">Share</button>
         </div>
       </div>

       <!-- Content Area -->
       <div class="flex-1 overflow-y-auto bg-white p-6 md:p-8">
         <!-- Metadata -->
         <div class="grid grid-cols-[100px_1fr] gap-y-4 text-sm mb-8">
           <div class="text-gray-500">Created</div>
           <div class="text-gray-900">Mon, 10 Feb, 17:45 • 18:12</div>
           
           <div class="text-gray-500">Meeting</div>
           <div class="flex items-center gap-2">
             <div class="w-1 h-4 bg-orange-400 rounded-full"></div>
             <span class="font-medium">Week Kickoff</span>, 10 Feb, 5:45 PM - 6:00 PM
           </div>
           
           <div class="text-gray-500">Audio</div>
           <div class="flex items-center gap-2">
             <div class="w-6 h-6 rounded-full bg-gray-100 flex items-center justify-center text-gray-600 text-xs">▶</div>
             <div class="h-1 w-32 bg-gray-100 rounded-full overflow-hidden">
               <div class="h-full w-1/3 bg-gray-400"></div>
             </div>
             <span class="text-xs text-gray-500">27:18</span>
           </div>
         </div>
         
         <!-- Tabs -->
         <div class="flex gap-6 border-b border-gray-100 mb-6">
           <button class="pb-2 border-b-2 border-black font-medium text-sm">Summary</button>
           <button class="pb-2 border-b-2 border-transparent text-gray-500 font-medium text-sm hover:text-gray-800">Transcript</button>
         </div>
         
         <!-- Summary Content -->
         <div class="space-y-6 max-w-2xl">
            <div>
              <div class="flex items-center gap-2 mb-2">
                <span class="text-xs font-bold uppercase tracking-wider text-gray-400">Growth and Development Update</span>
              </div>
              <h4 class="font-bold text-gray-900 mb-2">Growth Metrics and Performance</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>Social media traffic has significantly increased: Twitter reaching 2.5k weekly views (from previous 100-150), while LinkedIn achieved 700 views</li>
                <li>Monthly Recurring Revenue (MRR) shows 5.6% growth month-to-date, with projections to reach 1.36m by month end</li>
                <li>Windows platform release has successfully expanded workspace usage and diversified the user base</li>
              </ul>
            </div>
            
             <div>
              <h4 class="font-bold text-gray-900 mb-2">Platform Expansion</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>Windows platform release has successfully expanded workspace usage</li>
                <li>Mobile app retention data: AI Notes users retain at 61%, AI Chat users at 92%</li>
              </ul>
            </div>
         </div>
       </div>
    </div>
  </div>

  <!-- Languages -->
  <div class="mt-12 text-center">
    <div class="flex flex-wrap justify-center gap-8 text-3xl font-serif text-gray-300 mb-4 select-none">
      <span>こんにちは</span>
      <span>Hei</span>
      <span>Bonjour</span>
      <span>Hallo</span>
      <span>नमस्ते</span>
      <span>Ciao</span>
      <span>Xin chào</span>
    </div>
    <p class="text-xs text-gray-400">
      We speak <span class="underline decoration-dotted">17 languages</span> really well. And <span class="underline decoration-dotted">82 more</span> without speaker labeling.
    </p>
  </div>
</section>
