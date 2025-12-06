<template>
  <div class="p-8">
    <!-- Page Title -->
    <h2 class="text-3xl font-bold text-gray-800 mb-6">Contact Us</h2>
    
    <!-- Contact Description -->
    <p class="text-gray-700 mb-6">
      We'd love to hear from you! Please fill out the form below to get in touch with us.
    </p>

    <!-- Contact Form -->
    <form class="max-w-lg mx-auto bg-white p-8 shadow-lg rounded-lg">
      <div class="mb-4">
        <label for="name" class="block text-lg font-medium text-gray-700">Name</label>
        <input 
          type="text" 
          id="name" 
          class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" 
          placeholder="Your Name"
        />
      </div>

      <div class="mb-4">
        <label for="email" class="block text-lg font-medium text-gray-700">Email</label>
        <input 
          type="email" 
          id="email" 
          class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" 
          placeholder="Your Email"
        />
      </div>

      <div class="mb-4">
        <label for="message" class="block text-lg font-medium text-gray-700">Message</label>
        <textarea 
          id="message" 
          rows="4" 
          class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" 
          placeholder="Your Message"
        ></textarea>
      </div>

      <!-- Submit Button -->
      <button 
        type="submit" 
        class="w-full py-3 mt-4 bg-blue-600 text-white rounded-lg hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300"
      >
        Send Message
      </button>
    </form>

    <!-- Example Tailwind Features Section -->
    <div class="mt-12 p-8 bg-gray-100 rounded-lg shadow-lg">
      <h3 class="text-2xl font-semibold text-gray-800 mb-4">Tailwind CSS Features</h3>
      <p class="text-gray-700 mb-4">Here are some features you can use with Tailwind CSS:</p>
      <ul class="list-disc pl-5 text-gray-700">
        <li>Utility-first classes for rapid styling</li>
        <li>Customizable design with configuration files</li>
        <li>Responsive design out of the box</li>
        <li>Fast build process and easy to integrate</li>
      </ul>
    </div>
  </div>
</template>

<script setup>
// Optional: Add JS here if needed
</script>

<style scoped>
/* Optional: Page-specific styles */
</style>
