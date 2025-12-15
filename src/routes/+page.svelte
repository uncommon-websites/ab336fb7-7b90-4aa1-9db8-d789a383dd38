<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Stats from "$lib/components/Stats.svelte";
  import Steps from "$lib/components/Steps.svelte";
  import FeatureSection from "$lib/components/FeatureSection.svelte";
  import CaseStudies from "$lib/components/CaseStudies.svelte";
  import Integrations from "$lib/components/Integrations.svelte";
  import Resources from "$lib/components/Resources.svelte";
  import BottomCTA from "$lib/components/BottomCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
  <title>CaptionKit - Multilingual Church Accessibility with Real-Time Translation</title>
  <meta name="description" content="Make worship accessible in 60+ languages with CaptionKit's real-time speech recognition and instant translation. Affordable captioning for churches starting at $99/month." />
  <meta name="keywords" content="church captions, multilingual church, real-time translation, church accessibility, worship captioning, ADA compliance" />
</svelte:head>

<Header />

<main>
  <Hero />
  <Stats />
  <Steps />
  
  <!-- Feature 1: Real-time Speech Recognition -->
  <FeatureSection 
    title="Real-time speech recognition that understands worship context"
    subtitle="ACCURATE CAPTIONS FOR EVERY WORD"
    linkText="Learn about our technology"
    bullets={[
      "Trained on religious terminology and worship vocabulary",
      "Handles music, prayers, and sermons with high accuracy",
      "Automatic punctuation and formatting",
      "Works with any audio quality or accent"
    ]}
  >
    <div slot="description">
      <p>Our AI-powered speech recognition is specifically trained for worship services, ensuring accurate captions for sermons, prayers, and announcements.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
      <!-- Caption Display Mockup -->
      <div class="bg-white rounded-xl shadow-lg p-6 w-[90%] max-w-lg relative">
        <div class="flex items-center gap-2 mb-4 pb-3 border-b border-gray-100">
          <div class="w-3 h-3 rounded-full bg-green-500 animate-pulse"></div>
          <div class="text-xs font-semibold text-gray-500">LIVE</div>
        </div>
        <div class="space-y-4">
          <div class="p-3 bg-gray-50 rounded-lg">
             <div class="text-sm text-gray-900 leading-relaxed">Today we gather to celebrate and worship together as one community.</div>
          </div>
          <div class="p-3 bg-primary-50 rounded-lg border border-primary-100">
             <div class="text-sm text-gray-900 leading-relaxed font-medium">Let us open our hearts to the message of hope and love.</div>
          </div>
          <div class="p-3 bg-gray-50/50 rounded-lg opacity-60">
             <div class="text-sm text-gray-600 leading-relaxed">Please turn to page 127 in your hymnal...</div>
          </div>
        </div>
      </div>
    </div>
  </FeatureSection>

  <!-- Feature 2: Instant Translation -->
  <FeatureSection 
    title="Instant translation across 60+ languages"
    subtitle="BREAK DOWN LANGUAGE BARRIERS"
    linkText="View all languages"
    reversed={true}
    bullets={[
      "Support for Spanish, Mandarin, Korean, Arabic, and 56+ more",
      "Real-time translation with less than 1-second delay",
      "Culturally appropriate translations for religious content",
      "Easy language switching for multilingual services"
    ]}
  >
    <div slot="description">
      <p>Reach every member of your congregation in their native language with instant, accurate translations powered by advanced AI.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Language Grid -->
       <div class="grid grid-cols-2 gap-4 w-full max-w-md">
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center gap-3">
            <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 font-bold text-lg">EN</div>
            <div class="text-sm">
               <div class="font-semibold">English</div>
               <div class="text-xs text-gray-500">Primary</div>
            </div>
         </div>
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center gap-3">
            <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 font-bold text-lg">ES</div>
            <div class="text-sm">
               <div class="font-semibold">Español</div>
               <div class="text-xs text-gray-500">Active</div>
            </div>
         </div>
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center gap-3">
            <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 font-bold text-lg">中</div>
            <div class="text-sm">
               <div class="font-semibold">中文</div>
               <div class="text-xs text-gray-500">Active</div>
            </div>
         </div>
         <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center gap-3">
            <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 font-bold text-lg">한</div>
            <div class="text-sm">
               <div class="font-semibold">한국어</div>
               <div class="text-xs text-gray-500">Active</div>
            </div>
         </div>
         <div class="col-span-2 bg-gray-50 p-3 rounded-lg text-center">
            <div class="text-xs text-gray-500">+ 56 more languages available</div>
         </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 3: Easy Setup -->
  <FeatureSection 
    title="Setup in minutes, not hours"
    subtitle="DESIGNED FOR CHURCH TECH DIRECTORS"
    linkText="View setup guide"
    bullets={[
      "No technical expertise required",
      "Works with existing audio systems",
      "Mobile app for quick setup and testing",
      "Free 4-hour trial to test before committing"
    ]}
  >
    <div slot="description">
      <p>We understand church tech directors are busy. That's why CaptionKit is designed for quick, hassle-free setup with step-by-step guidance.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Setup Steps UI -->
       <div class="bg-white rounded-2xl shadow-lg p-6 w-80 space-y-4">
          <div class="flex items-center gap-3 p-3 bg-green-50 rounded-lg border border-green-200">
             <div class="w-8 h-8 bg-green-500 rounded-full flex items-center justify-center text-white text-sm font-bold">✓</div>
             <div>
                <div class="text-xs font-bold text-gray-900">Connect audio</div>
                <div class="text-[10px] text-gray-500">Completed in 3 min</div>
             </div>
          </div>
          <div class="flex items-center gap-3 p-3 bg-green-50 rounded-lg border border-green-200">
             <div class="w-8 h-8 bg-green-500 rounded-full flex items-center justify-center text-white text-sm font-bold">✓</div>
             <div>
                <div class="text-xs font-bold text-gray-900">Select languages</div>
                <div class="text-[10px] text-gray-500">Completed in 1 min</div>
             </div>
          </div>
          <div class="flex items-center gap-3 p-3 bg-primary-50 rounded-lg border border-primary-200">
             <div class="w-8 h-8 bg-primary-600 rounded-full flex items-center justify-center text-white text-sm font-bold">3</div>
             <div>
                <div class="text-xs font-bold text-gray-900">Test captions</div>
                <div class="text-[10px] text-gray-500">In progress...</div>
             </div>
          </div>
          <div class="mt-4 p-3 bg-gray-50 rounded-lg text-center">
             <div class="text-xs text-gray-500">Estimated time remaining: 2 minutes</div>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 4: Affordable Pricing -->
  <FeatureSection 
    title="Affordable pricing designed for churches"
    subtitle="ACCESSIBLE TO EVERY CONGREGATION"
    linkText="View pricing plans"
    reversed={true}
    bullets={[
      "Fraction of the cost of traditional captioning services",
      "No per-hour fees or hidden charges",
      "Flexible plans that scale with your congregation size",
      "Free 4-hour trial with no credit card required"
    ]}
  >
    <div slot="description">
      <p>We believe every church should be able to afford accessibility. Our pricing is transparent and designed to fit church budgets of all sizes.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Pricing Comparison -->
       <div class="w-full max-w-md space-y-4">
          <div class="bg-white rounded-xl shadow-sm p-6 border border-gray-200">
             <div class="flex justify-between items-start mb-3">
                <div>
                   <div class="text-xs text-gray-500 mb-1">Traditional Services</div>
                   <div class="text-2xl font-bold text-gray-900">$150+</div>
                </div>
                <div class="text-xs text-gray-500">per hour</div>
             </div>
             <div class="text-xs text-gray-500">Requires advance booking, limited languages</div>
          </div>
          <div class="bg-primary-600 rounded-xl shadow-lg p-6 border-2 border-primary-700 relative">
             <div class="absolute -top-3 right-4 bg-white px-3 py-1 rounded-full text-xs font-bold text-primary-600">BEST VALUE</div>
             <div class="flex justify-between items-start mb-3">
                <div>
                   <div class="text-xs text-primary-100 mb-1">CaptionKit</div>
                   <div class="text-2xl font-bold text-white">$99</div>
                </div>
                <div class="text-xs text-primary-100">per month</div>
             </div>
             <div class="text-xs text-primary-100">Unlimited hours, 60+ languages, instant setup</div>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 5: Accessibility Compliance -->
  <FeatureSection 
    title="Meet accessibility standards and serve everyone"
    subtitle="ADA & WCAG COMPLIANT"
    linkText="Learn about accessibility"
    bullets={[
      "Compliant with ADA accessibility requirements",
      "WCAG 2.1 Level AA standards for digital accessibility",
      "Customizable text size, colors, and display options",
      "Screen reader compatible for visually impaired users"
    ]}
  >
    <div slot="description">
      <p>Ensure your worship services are accessible to all members of your community, including those with hearing impairments or language barriers.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center px-8">
       <!-- Accessibility Features Grid -->
       <div class="grid grid-cols-2 gap-6 w-full max-w-md">
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200 text-center">
             <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 mx-auto mb-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"></path><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"></path></svg>
             </div>
             <div class="text-xs font-semibold text-gray-900 mb-1">ADA</div>
             <div class="text-xs text-gray-500">Compliant</div>
          </div>
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200 text-center">
             <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 mx-auto mb-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>
             </div>
             <div class="text-xs font-semibold text-gray-900 mb-1">WCAG 2.1</div>
             <div class="text-xs text-gray-500">Level AA</div>
          </div>
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200 text-center">
             <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 mx-auto mb-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path><circle cx="12" cy="12" r="3"></circle></svg>
             </div>
             <div class="text-xs font-semibold text-gray-900 mb-1">Customizable</div>
             <div class="text-xs text-gray-500">Display</div>
          </div>
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200 text-center">
             <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center text-primary-600 mx-auto mb-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="15" rx="2" ry="2"></rect><polyline points="17 2 12 7 7 2"></polyline></svg>
             </div>
             <div class="text-xs font-semibold text-gray-900 mb-1">Screen Reader</div>
             <div class="text-xs text-gray-500">Compatible</div>
          </div>
       </div>
    </div>
  </FeatureSection>

  <!-- Feature 6: Worship Software Integration -->
  <FeatureSection 
    title="Integrates with your existing worship software"
    subtitle="SEAMLESS INTEGRATION"
    linkText="View all integrations"
    reversed={true}
    bullets={[
      "Works with Planning Center, ProPresenter, and more",
      "Sync with your service schedule automatically",
      "Display captions alongside lyrics and announcements",
      "API access for custom integrations"
    ]}
  >
    <div slot="description">
      <p>CaptionKit works seamlessly with the worship software you already use, making it easy to add captions without changing your workflow.</p>
    </div>
    <div slot="visual" class="w-full h-full flex items-center justify-center">
       <!-- Integration Logos Grid -->
       <div class="grid grid-cols-2 gap-6 w-full max-w-sm">
          <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-200 flex items-center justify-center">
             <span class="font-bold text-lg text-gray-700">Planning Center</span>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-200 flex items-center justify-center">
             <span class="font-bold text-lg text-gray-700">ProPresenter</span>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-200 flex items-center justify-center">
             <span class="font-bold text-lg text-gray-700">EasyWorship</span>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-200 flex items-center justify-center">
             <span class="font-bold text-lg text-gray-700">MediaShout</span>
          </div>
          <div class="col-span-2 bg-primary-50 p-4 rounded-lg border border-primary-100 text-center">
             <span class="text-sm font-medium text-primary-700">+ Custom API Integration</span>
          </div>
       </div>
    </div>
  </FeatureSection>

  <CaseStudies />
  <Integrations />
  <Resources />
  <BottomCTA />
</main>

<Footer />

