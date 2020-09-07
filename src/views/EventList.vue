<template>
  <div>
    <h1>Events Listing</h1>
    <EventCard />
    <BaseIcon name="activity" width="48" height="48" />
  </div>
</template>
<script>
import EventCard from '@/components/EventCard.vue'
export default {
  components: {
    EventCard
  }
}
</script>
