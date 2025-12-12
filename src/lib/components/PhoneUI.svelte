<div class="relative bg-black rounded-[3rem] p-3 w-full h-full shadow-2xl ring-1 ring-gray-900/5">
  <!-- Power Button -->
  <div class="absolute -right-[2px] top-24 w-[2px] h-12 bg-gray-800 rounded-r-md"></div>
  <!-- Volume Buttons -->
  <div class="absolute -left-[2px] top-24 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>
  <div class="absolute -left-[2px] top-36 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>

  <!-- Screen -->
  <div class="bg-white w-full h-full rounded-[2.5rem] overflow-hidden relative flex flex-col">
    <!-- Status Bar / Notch Area -->
    <div class="h-12 w-full flex justify-center items-start pt-2 absolute top-0 left-0 z-20">
      <div class="w-28 h-7 bg-black rounded-full flex items-center justify-center gap-2 px-3">
        <!-- Dynamic Island Content Simulation -->
        <div class="w-full h-full flex items-center justify-between opacity-0">
           <!-- Hidden content just to keep size -->
        </div>
      </div>
    </div>

    <!-- App Content -->
    <div class="flex-1 overflow-y-auto pt-12 px-6 pb-6 text-xs font-medium select-none scrollbar-hide">
      <!-- Header -->
      <div class="flex justify-between items-center mb-8 mt-2">
        <h2 class="text-2xl font-bold tracking-tight">XOXO</h2>
        <div class="text-gray-400 text-[10px] uppercase tracking-wide text-right leading-tight font-semibold">
          9:42 AM
        </div>
      </div>

      <!-- AI Insights -->
      <div class="space-y-4 mb-8">
        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex items-center gap-2 mb-2">
            <div class="w-2 h-2 rounded-full bg-blue-500"></div>
            <span class="text-[10px] text-gray-500 uppercase tracking-wide font-semibold">Context</span>
          </div>
          <p class="text-sm leading-relaxed text-gray-900">
            You have a meeting in 15 minutes. Traffic is light, but you should leave now.
          </p>
        </div>

        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex items-center gap-2 mb-2">
            <div class="w-2 h-2 rounded-full bg-purple-500"></div>
            <span class="text-[10px] text-gray-500 uppercase tracking-wide font-semibold">Proactive</span>
          </div>
          <p class="text-sm leading-relaxed text-gray-900">
            Sarah's birthday is tomorrow. Would you like me to suggest a gift?
          </p>
        </div>
      </div>

      <!-- Quick Actions -->
      <div class="mb-6">
        <h3 class="text-[10px] text-gray-400 uppercase tracking-wide font-semibold mb-3">Suggested Actions</h3>
        <div class="space-y-2">
          <div class="bg-white border border-gray-200 rounded-xl px-4 py-3 flex items-center justify-between">
            <span class="text-sm font-medium">Start navigation</span>
            <span class="text-gray-400">→</span>
          </div>
          <div class="bg-white border border-gray-200 rounded-xl px-4 py-3 flex items-center justify-between">
            <span class="text-sm font-medium">Review prep notes</span>
            <span class="text-gray-400">→</span>
          </div>
        </div>
      </div>

      <!-- Ambient Status -->
      <div class="space-y-3">
        <h3 class="text-[10px] text-gray-400 uppercase tracking-wide font-semibold">Ambient Awareness</h3>
        <div class="flex items-center gap-3 text-gray-500">
          <div class="w-6 h-6 rounded-full bg-green-100 flex items-center justify-center">
            <span class="text-green-600 text-xs">✓</span>
          </div>
          <span class="text-sm">Calendar synced</span>
        </div>
        <div class="flex items-center gap-3 text-gray-500">
          <div class="w-6 h-6 rounded-full bg-blue-100 flex items-center justify-center">
            <span class="text-blue-600 text-xs">◉</span>
          </div>
          <span class="text-sm">Location aware</span>
        </div>
        <div class="flex items-center gap-3 text-gray-500">
          <div class="w-6 h-6 rounded-full bg-purple-100 flex items-center justify-center">
            <span class="text-purple-600 text-xs">⚡</span>
          </div>
          <span class="text-sm">Learning preferences</span>
        </div>
      </div>
    </div>
    
    <!-- Home Indicator -->
    <div class="absolute bottom-1 left-1/2 -translate-x-1/2 w-32 h-1 bg-black rounded-full opacity-20"></div>
  </div>
</div>

