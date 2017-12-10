<template lang="html">
    <div>
        <p>{{ message.message }}</p>
        <small>{{ message.user.name }}</small>
    </div>
</template>

<script>
    export default {
        props: ['message'] // ChatLogのv-bind:messageでプロパティを受け取る
    }
</script>

<style lang="css">
    .chat-message {
        padding: 1rem;
    }

    .chat-message > p {
        mergin-bottom: .5rem;
    }
</style>