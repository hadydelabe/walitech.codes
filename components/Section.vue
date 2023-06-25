<script setup lang="ts">
defineProps<{
    title?: string;
}>();
</script>
<template>
    <section class="section bg-white dark:bg-gray-900">
        <div class="container px-6 py-10 mx-auto">
            <SectionUnderlinedTitle :class="{ 'space-t-12': title != null }" v-if="title" :title="title" />
            <div v-bind="$attrs">
                <slot />
            </div>
        </div>
    </section>
</template>

  
<script lang="ts">
// Don't inherit the attributes from the parent component
// since we only put them on the slot
export default {
    //inheritAttrs: false,
};
</script>
  
<style>
.section:nth-of-type(odd) {
    background-color: #efefef;
}
</style>