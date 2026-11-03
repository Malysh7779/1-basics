<script setup>
  const currDate = new Date().toISOString().split('T')[0];
  const [year, month, day] = currDate.split('-');
  const dateRU = `${day}.${month}.${year}`;

</script>

<template>
  <div class="date-box">
    {{ dateRU }}
  </div>
</template>

<style scope>
.date-box {
  border: 1px solid blue;
  border-radius: 10px;
  padding: 10px;
  margin: 10px;
}
</style>