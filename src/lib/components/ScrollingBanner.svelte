<div class="fixed top-0 left-0 w-full h-10 bg-black text-white flex items-center z-50 overflow-hidden">
  <!-- 
    Here's the change:
    We use the arbitrary value syntax to call our keyframes.
    Format: animate-[name_duration_timing-function_iteration-count]
  -->
  <div class="flex-shrink-0 flex items-center animate-[marquee_25s_linear_infinite] whitespace-nowrap">
    <!-- Repeat your text to ensure it fills the screen and loops seamlessly -->
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
  </div>
  <!-- Duplicate the content for a smooth infinite loop -->
  <div class="flex-shrink-0 flex items-center animate-[marquee_25s_linear_infinite] whitespace-nowrap" aria-hidden="true">
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
  </div>
  <div class="flex-shrink-0 flex items-center animate-[marquee_25s_linear_infinite] whitespace-nowrap" aria-hidden="true">
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
  </div>
  <div class="flex-shrink-0 flex items-center animate-[marquee_25s_linear_infinite] whitespace-nowrap" aria-hidden="true">
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
    <span class="mx-4">YOUR REPEATED TEXT • YOUR REPEATED TEXT •</span>
  </div>
</div>