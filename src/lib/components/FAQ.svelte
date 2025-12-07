<script lang="ts">
  let openIndex: number | null = null;
  
  const faqs = [
    "Can I use Amie at my company?",
    "Where do I connect more accounts?",
    "How does Amie protect my privacy?",
    "When can I use Amie on my device?",
    "Where can I send a feature request or report a bug?",
    "Which video call providers do you support?"
  ];
  
  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-3xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-center mb-4">FAQs</h2>
    <p class="text-center text-gray-500 mb-12 text-sm">
      If you can't find the answer to your question below, email us at <span class="text-black font-medium">care@amie.so</span>
    </p>
    
    <div class="space-y-4">
      {#each faqs as faq, i}
        <div class="bg-white rounded-xl overflow-hidden shadow-sm">
          <button 
            class="w-full flex justify-between items-center p-6 text-left font-medium text-gray-900 hover:bg-gray-50 transition-colors"
            on:click={() => toggle(i)}
          >
            {faq}
            <svg 
              class="w-5 h-5 text-gray-400 transform transition-transform {openIndex === i ? 'rotate-180' : ''}" 
              fill="none" 
              viewBox="0 0 24 24" 
              stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
            </svg>
          </button>
          {#if openIndex === i}
            <div class="px-6 pb-6 text-gray-600 text-sm">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</section>
