<script setup lang="ts">
defineProps<{
    title?: string;
}>();
</script>
<template>
    <section class="section bg-white dark:bg-gray-900">
        <div class="container px-6 py-10 mx-auto">
            <div class="lg:flex lg:items-center">
                <div class="w-full space-y-12 lg:w-1/2 ">
                    <SectionUnderlinedTitle v-if="title" :title="title" />
                    <div v-bind="$attrs">
                        <slot />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

  
<script lang="ts">
// Don't inherit the attributes from the parent component
// since we only put them on the slot
export default {
    inheritAttrs: false,
};
</script>
  
<style>
.section:nth-of-type(even) {
    @apply bg-blue-500 text-white;
}
</style>