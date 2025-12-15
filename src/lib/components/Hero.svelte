<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="pt-32 pb-16 overflow-hidden">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="max-w-4xl mx-auto text-center mb-16">
      <h1 class="text-5xl md:text-6xl font-semibold tracking-tight text-gray-900 mb-6 leading-[1.1]">
        Make every worship service accessible in 60+ languages
      </h1>
      <p class="text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
        CaptionKit delivers real-time speech recognition and instant translation for multilingual churches, making worship accessible to everyone in your congregation.
      </p>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <Button variant="primary" size="lg" class="rounded-full px-8">Start free trial</Button>
        <Button variant="outline" size="lg" class="rounded-full px-8">Watch demo</Button>
      </div>
    </div>

    <!-- Logos Strip -->
    <div class="mb-12">
      <p class="text-xs font-semibold text-gray-500 uppercase tracking-wider mb-6 text-center">Trusted by churches worldwide</p>
      <div class="flex flex-wrap items-center justify-center gap-8 opacity-60 grayscale px-4">
        <span class="text-xl font-bold font-sans tracking-tight">First Baptist</span>
        <span class="text-xl font-bold font-sans tracking-tight">Grace Community</span>
        <span class="text-xl font-bold font-sans tracking-tight">New Life Church</span>
        <span class="text-xl font-bold font-sans tracking-tight">Hillside Chapel</span>
        <span class="text-xl font-bold font-sans tracking-tight">City Church</span>
      </div>
    </div>

    <!-- Hero Image -->
    <div class="relative rounded-2xl overflow-hidden shadow-2xl bg-gray-100">
      <img 
        src="/generated/image-diverse-congregation-in-a-modern-church--1765790391986-0.webp" 
        alt="Church worship service with diverse congregation" 
        class="w-full h-[600px] object-cover object-center"
      />
      
      <!-- Floating UI Elements -->
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 flex flex-col gap-4">
        <!-- Caption 1 -->
        <div class="bg-white/90 backdrop-blur-sm p-4 rounded-xl shadow-lg flex items-start gap-4 animate-in fade-in slide-in-from-bottom-4 duration-700 max-w-md">
          <div class="w-10 h-10 bg-primary-600 rounded-lg flex items-center justify-center text-white shrink-0">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
          </div>
          <div>
            <div class="text-xs text-gray-500 mb-1">English</div>
            <div class="text-sm font-medium text-gray-900">Welcome to our service today</div>
          </div>
        </div>

        <!-- Caption 2 -->
        <div class="bg-white/90 backdrop-blur-sm p-4 rounded-xl shadow-lg flex items-start gap-4 ml-12 animate-in fade-in slide-in-from-bottom-4 duration-1000 delay-300 max-w-md">
          <div class="w-10 h-10 bg-primary-600 rounded-lg flex items-center justify-center text-white shrink-0">
             <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>
          </div>
          <div>
            <div class="text-xs text-gray-500 mb-1">Español</div>
            <div class="text-sm font-medium text-gray-900">Bienvenidos a nuestro servicio hoy</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
