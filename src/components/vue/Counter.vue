<script setup>
    import { ref } from "vue";
    
    const count = ref(0);
    </script>
    
    <template>
      <div class="p-6 border rounded-lg text-center shadow-lg w-64 mx-auto">
        <p class="text-xl font-bold mb-2">Counter: {{ count }}</p>
        <button @click="count++" class="px-4 py-2 bg-blue-500 text-white rounded">
          Increment
        </button>
      </div>
    </template>
    