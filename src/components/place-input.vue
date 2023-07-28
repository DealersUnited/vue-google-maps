<template>
    <label>
        <span v-text="label"></span>
        <input type="text" :placeholder="placeholder" :class="className"
          ref="input"/>
    </label>
</template>

<script>
import placeWindow from '../components-implementation/place-input.js'
export default placeWindow
</script>
