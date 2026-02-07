<script lang="ts">
  // Calendar & Todos Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-orange-500 font-medium">Calendar & Todos</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">Organize your day on autopilot</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Replaces:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-500"></div> Gcal</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-400"></div> Things 3</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-gray-800"></div> Motion</span>
  </div>
  
  <p class="text-gray-600 max-w-3xl mb-16">
    Combine action items from your calls with todos from eg Notion or Todoist in one place. From there, we use AI to schedule your day. Whenever your plans change, we shuffle around your schedule to keep you on track.
  </p>
  
  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">AI Scheduling</h3>
      <p class="text-gray-600 mb-8 text-sm">
        We'll put together your schedule on automatically. You'll keep app deadlines, and will work on the highest priority items first.
      </p>
      
      <!-- Mockup Checklist -->
      <div class="bg-gray-50 p-6 rounded-xl border border-gray-100">
        <div class="space-y-3">
          <div class="flex items-center gap-3">
            <div class="w-5 h-5 border-2 border-gray-300 rounded"></div>
            <span class="text-sm text-gray-700">Send newsletter</span>
            <div class="ml-auto bg-blue-100 text-blue-600 text-xs px-2 py-1 rounded">4</div>
          </div>
          <div class="flex items-center gap-3 relative">
            <div class="w-5 h-5 border-2 border-gray-300 rounded"></div>
            <span class="text-sm text-gray-700">Finish up website</span>
            
            <!-- Floating tooltip mockup -->
            <div class="absolute left-32 top-[-10px] bg-[#0099ff] text-white text-xs p-2 rounded shadow-lg z-10">
              <div class="font-bold">Send newsletter</div>
              <div>09:00 - 09:45</div>
            </div>
          </div>
          <div class="flex items-center gap-3">
            <div class="w-5 h-5 border-2 border-gray-300 rounded"></div>
            <span class="text-sm text-gray-700">Pick up laundry</span>
          </div>
        </div>
      </div>
    </div>
    
    <div>
      <h3 class="font-bold text-lg mb-4">AI Calendar</h3>
      <p class="text-gray-600 mb-8 text-sm">
        Ask the chat to create or update your events. Ask it how much time you've spent on demo calls last week. Or have it prepare today's agendas.
      </p>
      
      <div class="bg-white border border-gray-200 rounded-xl p-4 shadow-sm">
        <div class="flex items-start gap-3">
          <div class="w-4 h-4 mt-1 border border-gray-300 rounded"></div>
          <div>
            <div class="font-medium text-sm">Finish website</div>
            <div class="text-xs text-gray-500 mt-1">Wrap up the feature section for meeting notes, collections and chat.</div>
            <div class="mt-2 flex items-center gap-2 text-xs text-gray-400">
              <div class="w-4 h-4 rounded-full bg-gray-200"></div>
              <span>48m</span>
              <div class="w-4 h-4 rounded bg-blue-100 text-blue-600 flex items-center justify-center font-bold">N</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Testimonials Grid -->
  <div class="grid md:grid-cols-3 gap-8">
    <div class="bg-gray-50 p-6 rounded-xl relative">
       <div class="text-orange-400 text-xs mb-2">★★★★★</div>
       <div class="flex items-center gap-2 mb-2">
         <div class="w-6 h-6 bg-gray-300 rounded-full"></div>
         <div class="text-xs font-bold">Oz, Founder</div>
       </div>
       <p class="text-xs text-gray-600">It doesn't have to suck to be productive, Seren reminds you of that</p>
       <div class="absolute top-4 right-4 w-4 h-4 bg-black rounded"></div>
    </div>
    
    <div class="bg-gray-50 p-6 rounded-xl relative">
       <div class="text-orange-400 text-xs mb-2">★★★★★</div>
       <div class="flex items-center gap-2 mb-2">
         <div class="w-6 h-6 bg-gray-300 rounded-full"></div>
         <div class="text-xs font-bold">Raf, Designer</div>
       </div>
       <p class="text-xs text-gray-600">nothing but joy. opening a calendar shouldn't be stressful. can't imagine to go back</p>
       <div class="absolute top-4 right-4 w-4 h-4 bg-black rounded"></div>
    </div>
    
    <div class="bg-gray-50 p-6 rounded-xl relative">
       <div class="text-orange-400 text-xs mb-2">★★★★★</div>
       <div class="flex items-center gap-2 mb-2">
         <div class="w-6 h-6 bg-gray-300 rounded-full"></div>
         <div class="text-xs font-bold">Noah, Founder</div>
       </div>
       <p class="text-xs text-gray-600">I can finally do time blocking and to-do lists from one interface.</p>
       <div class="absolute top-4 right-4 w-4 h-4 bg-black rounded"></div>
    </div>
  </div>
</section>
