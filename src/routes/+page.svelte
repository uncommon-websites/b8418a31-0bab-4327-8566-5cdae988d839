<script lang="ts">
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import ValueProp from '$lib/components/ValueProp.svelte';
  import MeetingNotes from '$lib/components/MeetingNotes.svelte';
  import NoBots from '$lib/components/NoBots.svelte';
  import WorksWherever from '$lib/components/WorksWherever.svelte';
  import Achievements from '$lib/components/Achievements.svelte';
  import AIChat from '$lib/components/AIChat.svelte';
  import Integrations from '$lib/components/Integrations.svelte';
  import ShareablePages from '$lib/components/ShareablePages.svelte';
  import CalendarTodos from '$lib/components/CalendarTodos.svelte';
  import BottomCTA from '$lib/components/BottomCTA.svelte';
  import FAQ from '$lib/components/FAQ.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white font-sans text-gray-900 selection:bg-blue-100 selection:text-blue-900">
  <Navbar />
  <main>
    <Hero />
    <ValueProp />
    <MeetingNotes />
    <NoBots />
    <WorksWherever />
    <Achievements />
    <AIChat />
    <Integrations />
    <ShareablePages />
    <CalendarTodos />
    <BottomCTA />
    <FAQ />
  </main>
  <Footer />
</div>

