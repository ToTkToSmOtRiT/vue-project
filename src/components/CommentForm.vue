<template>
    <form action="adding">
        <input id="username" type="text" placeholder="Write name...">
        <input id="comment" type="text" placeholder="Write comment...">
        <div class="capthca">
            <button id="confirm" type="submit">I'm not a robot!</button>
        </div>
        <button id="add" type="submit">Send comment</button>
    </form>
</template>


<script>
export default {
    name: 'CommentForm',
    data(){
        return{
            comment: ''
        }
    }
}
</script>


<style>

</style>