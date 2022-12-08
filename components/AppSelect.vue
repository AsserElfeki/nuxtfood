<template>
  <div>
    <label :for="select">Choose a {{ select }}:</label>

    <select @change="$emit('change', $event.target.value)" :name="select" :id="select">
      <option value>--Please choose--</option>
      <option v-for="option in selectOptions" :key="option" :value="option">
        {{ option }}
      </option>
    </select>
  </div>
</template>
