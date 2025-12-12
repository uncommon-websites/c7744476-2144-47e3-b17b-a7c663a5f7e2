<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Button from '$lib/components/Button.svelte';
  import PlannerIcon from '$lib/components/icons/PlannerIcon.svelte';
  import LightningIcon from '$lib/components/icons/LightningIcon.svelte';
  import MindIcon from '$lib/components/icons/MindIcon.svelte';
  import PhoneUI from '$lib/components/PhoneUI.svelte';
</script>

<div class="min-h-screen bg-white text-black font-sans selection:bg-gray-200">
  <Header />

  <main class="flex flex-col items-center w-full">
    <!-- Hero Section -->
    <section class="flex flex-col items-center text-center pt-10 pb-12 px-4 max-w-4xl mx-auto">
      <h2 class="text-sm font-semibold mb-6">XOXO</h2>
      
      <h1 class="text-5xl md:text-7xl font-bold tracking-tight leading-[1.1] mb-10">
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <MindIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
          <span>Ambient AI</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>that</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <LightningIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
          <span>anticipates</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>your</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <PlannerIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
          <span>needs</span>
        </div>
      </h1>

      <div class="mb-12">
        <Button>
          <span class="text-base">Join Waitlist</span>
        </Button>
      </div>

      <!-- Social Proof -->
      <div class="flex flex-wrap justify-center gap-8 md:gap-12 text-gray-400 text-xs font-medium">
        <div class="flex flex-col items-center leading-tight">
          <span class="text-2xl font-bold text-gray-900 mb-1">$50B</span>
          <span class="text-gray-400">Market Opportunity</span>
        </div>
        <div class="flex flex-col items-center leading-tight">
          <span class="text-2xl font-bold text-gray-900 mb-1">24/7</span>
          <span class="text-gray-400">Ambient Awareness</span>
        </div>
        <div class="flex flex-col items-center leading-tight">
          <span class="text-2xl font-bold text-gray-900 mb-1">0</span>
          <span class="text-gray-400">Intrusive Prompts</span>
        </div>
      </div>
    </section>

    <!-- Phone Showcase -->
    <section class="w-full max-w-[1000px] px-4 mb-24 relative flex justify-center">
      <!-- Background glow/shadow simulation -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-gray-100/50 rounded-full blur-3xl -z-10"></div>
      
      <!-- Phone Container -->
      <!-- Since we don't have the hand image, we'll present the phone UI in a nice frame -->
      <div class="relative w-[300px] md:w-[340px] h-[680px] md:h-[720px] transition-transform hover:scale-[1.02] duration-500">
        <PhoneUI />
      </div>
    </section>

    <!-- Features Text -->
    <section class="max-w-4xl mx-auto px-6 pb-32 space-y-24 text-center">
      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          XOXO creates proactive intelligence through ambient context awareness, understanding your world without constant input
        </h3>
      </div>

      <!-- Feature Image 1 -->
      <div class="w-full rounded-3xl overflow-hidden shadow-2xl">
        <img 
          src="/generated/image-tech-professional-working-naturally-with-1765565022933-0.webp" 
          alt="Tech professional working with ambient AI"
          class="w-full h-auto"
        />
      </div>

      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Built for tech professionals who want meaningful AI assistance that feels natural, not intrusive or disconnected
        </h3>
      </div>

      <!-- Feature Image 2 -->
      <div class="w-full rounded-3xl overflow-hidden shadow-2xl">
        <img 
          src="/generated/image-person-seamlessly-interacting-with-ambie-1765565025976-1.webp" 
          alt="Seamless ambient technology integration"
          class="w-full h-auto"
        />
      </div>

      <div class="space-y-10">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Human-centered AI that integrates seamlessly into your daily life, anticipating needs before you ask
        </h3>
        
        <div class="pt-4">
          <Button>
            <span class="text-base">Join Waitlist</span>
          </Button>
        </div>
      </div>
    </section>

    <!-- Differentiation Section -->
    <section class="w-full bg-gray-50 py-24 px-6">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-3xl md:text-5xl font-bold tracking-tight text-center mb-16">
          AI that understands context, not just commands
        </h2>
        
        <div class="grid md:grid-cols-3 gap-8 md:gap-12">
          <div class="space-y-4 text-center">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm">
              <MindIcon className="w-8 h-8" />
            </div>
            <h3 class="text-xl font-bold">Ambient Awareness</h3>
            <p class="text-gray-600 leading-relaxed">
              Understands your context without constant input. No need to tell it everything—it learns from your patterns.
            </p>
          </div>
          
          <div class="space-y-4 text-center">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm">
              <LightningIcon className="w-8 h-8" />
            </div>
            <h3 class="text-xl font-bold">Proactive Intelligence</h3>
            <p class="text-gray-600 leading-relaxed">
              Anticipates your needs before you ask. Gets ahead of problems instead of just responding to them.
            </p>
          </div>
          
          <div class="space-y-4 text-center">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm">
              <PlannerIcon className="w-8 h-8" />
            </div>
            <h3 class="text-xl font-bold">Human-Centered</h3>
            <p class="text-gray-600 leading-relaxed">
              Designed to feel natural, not intrusive. AI that enhances your life without demanding attention.
            </p>
          </div>
        </div>

        <div class="text-center mt-16">
          <Button>
            <span class="text-base">Join Waitlist</span>
          </Button>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="w-full py-12 flex flex-col items-center gap-6 text-center border-t border-gray-100 mt-auto">
      <div class="font-bold text-xl tracking-tight text-gray-200">XOXO</div>
      <div class="flex flex-wrap justify-center gap-4 text-xs text-gray-400 font-medium">
        <a href="#" class="hover:text-black transition-colors">Waitlist</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Contact</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">X (FKA Twitter)</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Privacy Policy</a>
      </div>
      <div class="text-[10px] text-gray-300">
        Building the future of ambient intelligence
      </div>
    </footer>
  </main>
</div>


