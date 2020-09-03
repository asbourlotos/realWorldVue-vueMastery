<template>
    <div class="user">
        <h1>This is {{ username }}'s page</h1>
    </div>
</template>

vue <script>
export default {
    props: ['username']
};
</script>