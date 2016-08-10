<template>
    <div>
        <Display></Display>
        <Increment></Increment>
    </div>
</template>

<script>

    import Display from './Display.vue'
    import Increment from './Increment.vue'
    import store from '../vuex/store' // import the store we just created

    export default {
        components: {
            Display: Display,
            Increment: Increment
        },
        store: store // make this and all child components aware of the new store
    }
</script>