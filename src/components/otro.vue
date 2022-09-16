<script setup>
    import { ref } from 'vue'
    
    const awesome = ref(true)
    const itIs = ref()
    
    function toggle() {
      // ...
      awesome.value = !awesome.value
      
      if(awesome.value){
        itIs.value="isawesome"
      }
      else{
        itIs.value="isnot"
      }
    }
    </script>
    
    <template>
      <button @click="toggle">toggle</button>
      <h1 v-if="awesome" :class="itIs">Vue is awesome!</h1>
      <h1 v-else :class="itIs">Oh no 😢</h1>
    </template>
    
    <style scope>
      .isawesome{
        color:green;
      }
      
      .isnot{
        color:red;
      }
    
    </style>