<div id="parallax-test" class="hero is-fullheight" >
Test
</div>

<style>
    #parallax-test {
        background-image: url('/img/main-background.png');
        background-size: cover;
    }
</style>

<script>
    import { onMount } from 'svelte';

    onMount(() => {
        document.onmousemove = function(){
        var x = event.offsetX;
        var y = event.offsetY;    
        document.getElementById("parallax-test").style.backgroundPositionX = -x + "px";
        document.getElementById("parallax-test").style.backgroundPositionY = -y + "px";        
}
    })
</script>