<script>
    export let image;
    export let description;
    export let location;
</script>

<a href={location}>
<img src={image} alt="Thumbnail">
<p>{description}</p>
</a>
<!--  -->
<style>
    a {
        display: flex;
        flex-flow: row nowrap;
        align-items: center;

        width: 50rem;
        border-radius: 1.5rem;
        padding: 0.5rem;
        margin: 0.5rem;

        transition-delay: 100ms;
        transition-duration: 250ms;

        &:hover{

        border-style: groove;
        border-color: #1F1717;


        }



    }
</style>