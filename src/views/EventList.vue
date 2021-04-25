<template>
  <h1>Events For Good</h1>
  <div class="events">
    <EventCard v-for="event in events" :key="event.id" :event="event" />
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from "@/components/EventCard.vue";

export default {
  name: "EventList",
  components: {
    EventCard,
  },
  data() {
    return {
      events: [
        {
          id: 5928101,
          category: "animal welfare",
          title: "Dog Adoption Day",
          description: "Lorem",
          localtion: "Cali",
          date: "January 28,2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Andres Rincon",
        },
        {
          id: 5928101,
          category: "animal welfare",
          title: "Dog Adoption Day",
          description: "Lorem",
          localtion: "Cali",
          date: "January 28,2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Andres Rincon",
        },
        {
          id: 5928101,
          category: "animal welfare",
          title: "Dog Adoption Day",
          description: "Lorem",
          localtion: "Cali",
          date: "January 28,2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Andres Rincon",
        },
      ],
    };
  },
};
</script>

<style scoped>
.events {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>