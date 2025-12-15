<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<footer class="bg-white pt-24 pb-12 border-t border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 mb-16">
      <!-- Column 1 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Product</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Features</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Pricing</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Languages</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Integrations</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">API</a>
      </div>

      <!-- Column 2 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Solutions</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Multilingual Churches</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Accessibility</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Online Services</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Hybrid Worship</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Special Events</a>
      </div>

      <!-- Column 3 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Resources</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Setup Guide</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Help Center</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Blog</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Case Studies</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Webinars</a>
      </div>

      <!-- Column 4 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Company</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">About Us</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Contact</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Careers</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Press Kit</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Partners</a>
      </div>

       <!-- Column 5 -->
      <div class="flex flex-col gap-4">
        <h4 class="font-semibold text-gray-900 text-sm">Support</h4>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Get Started</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Documentation</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Community Forum</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">System Status</a>
        <a href="#" class="text-sm text-gray-500 hover:text-gray-900">Contact Support</a>
      </div>

       <!-- Column 6 (Newsletter) -->
      <div class="flex flex-col gap-4 lg:col-span-1">
        <h4 class="font-semibold text-gray-900 text-sm">Newsletter</h4>
        <p class="text-sm text-gray-500">Get church tech tips and accessibility insights delivered to your inbox.</p>
        <div class="flex flex-col gap-2">
           <Button variant="secondary" size="sm" class="w-full !bg-black !text-white !rounded-lg">Sign up</Button>
        </div>
      </div>
    </div>

    <!-- Bottom -->
    <div class="pt-8 border-t border-gray-100 flex flex-col md:flex-row justify-between items-center gap-4">
      <div class="flex items-center gap-2">
         <div class="w-6 h-6 text-primary-600">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M15.7321 18.4096C15.464 19.0054 15.1307 19.5889 14.7312 20.0937C18.0462 18.9764 20.4865 15.9576 20.7551 12.3344H19.5751C18.135 12.3344 16.9782 13.4839 16.7442 14.9048C16.5284 16.2146 16.1832 17.4073 15.7321 18.4096Z"
                fill="currentColor"
              />
              <path
                d="M13.122 12.3344C14.6297 12.3344 15.8632 13.5922 15.5862 15.0743C14.9847 18.2935 13.5564 20.5574 11.8901 20.5574C9.78166 20.5574 8.05421 16.9326 7.90082 12.3344H13.122Z"
                fill="currentColor"
              />
              <path
                d="M16.7748 8.62303C16.9953 10.0573 18.1574 11.2232 19.6085 11.2232H20.7689C20.5856 7.50155 18.1137 4.38174 14.7312 3.24164C15.1307 3.74646 15.464 4.32993 15.7321 4.9257C16.2052 5.97693 16.5618 7.23753 16.7748 8.62303Z"
                fill="currentColor"
              />
              <path
                d="M15.6307 8.5099C15.8829 9.98453 14.6549 11.2232 13.1588 11.2232H7.89462C7.99881 6.52003 9.74782 2.77795 11.8901 2.77795C13.599 2.77795 15.0576 5.15916 15.6307 8.5099Z"
                fill="currentColor"
              />
              <path
                d="M6.78316 11.2232C6.83365 8.81927 7.29225 6.60525 8.04807 4.9257C8.31614 4.32993 8.64941 3.74646 9.04901 3.24164C5.66642 4.38174 3.19455 7.50155 3.01129 11.2232H6.78316Z"
                fill="currentColor"
              />
              <path
                d="M3.02502 12.3344C3.29367 15.9576 5.73401 18.9764 9.04903 20.0937C8.64944 19.5889 8.31616 19.0054 8.0481 18.4096C7.31563 16.7819 6.86229 14.6523 6.78903 12.3344H3.02502Z"
                fill="currentColor"
              />
            </svg>
         </div>
         <span class="text-sm text-gray-500">© 2025 CaptionKit</span>
      </div>

      <div class="flex flex-col md:flex-row items-center gap-4 text-xs text-gray-500 text-center md:text-right">
        <p class="max-w-md">
           By clicking "Accept", you agree to the use of cookies on your device or browser to enhance site navigation, analyze site usage, and assist in our marketing efforts.
        </p>
        <div class="flex gap-4">
           <Button variant="primary" size="sm" class="!text-xs !py-1 !h-8">Accept all cookies</Button>
           <Button variant="outline" size="sm" class="!text-xs !py-1 !h-8">Cookie settings</Button>
        </div>
      </div>
    </div>
    
    <div class="mt-4 flex justify-end gap-6 text-xs text-gray-500">
       <a href="#" class="hover:text-gray-900">Privacy Statement</a>
       <a href="#" class="hover:text-gray-900">Terms of Service</a>
    </div>
  </div>
</footer>
