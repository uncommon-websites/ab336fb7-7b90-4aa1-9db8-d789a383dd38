<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="relative rounded-3xl overflow-hidden h-[500px]">
      <img 
        src="/generated/image-church-worship-team-leading-service-on-s-1765790403116-4.webp" 
        alt="Church congregation worshiping together" 
        class="absolute inset-0 w-full h-full object-cover"
      />
      <div class="absolute inset-0 bg-black/40"></div>
      
      <div class="absolute inset-0 flex flex-col justify-center px-8 md:px-16 max-w-3xl">
        <h2 class="text-4xl md:text-5xl font-bold text-white mb-8 leading-tight">
          Make your worship services accessible to everyone. Start today.
        </h2>
        <div class="flex flex-col sm:flex-row gap-4">
          <Button variant="primary" size="lg" class="rounded-full px-8">Start free trial</Button>
          <Button variant="outline" size="lg" class="rounded-full px-8 bg-white text-gray-900 border-none hover:bg-gray-100">Schedule demo</Button>
        </div>
      </div>
    </div>
  </div>
</section>
