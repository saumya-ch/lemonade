<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ description }}</p>
        <video autoplay muted loop id="myVideo">
            <source src="https://www.youtube.com/watch?v=6hf0IbVwrJI" type="video/mp4">
        </video>
        

    </div>
</template>

<script>
export default {
    name: 'information',
    data() {
        return {
            title: 'Logo Lab',
            description: 'Want to learn something new? Let’s explore some interesting topics.'
        }
    },
    methods: {
        // methods
    }
}

</script>