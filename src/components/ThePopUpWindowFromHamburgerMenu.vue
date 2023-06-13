<script setup>
const props = defineProps(['isOpen'])
console.log(props.isOpen)
</script>

<template>
  <div
    class="box bg-darkViolet font-poppins absolute left-0 right-0 top-12 z-10 ml-auto mr-auto max-w-xs flex-col gap-4 rounded-lg pb-10 pl-4 pr-4 pt-10 text-lg text-white"
    :class="props.isOpen ? 'flex' : 'hidden'"
  >
    <button>Features</button><button>Pricing</button><button>Resources</button>
    <div class="bg-grayishViolet h-px w-full" />
    <button>Login</button><button class="ml-4 mr-4 rounded-3xl bg-cyan pb-2 pt-2">
      Sign Up
    </button>
  </div>
</template>
