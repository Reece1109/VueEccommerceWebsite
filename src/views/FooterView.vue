<template>
    <div class="footer">
        <footer>Copyright @ Done by Reece Simon</footer>
    </div>
</template>

<script>
export default {
methods: {
    greet: function(event) {
        //event is the native DOM event
        alert(event.target.tagName);
    }
}
};
</script>
<style>

footer{
    font-size: 1rem;
    background-color:grey;

}

</style>