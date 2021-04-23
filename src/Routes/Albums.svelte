<script>
    import { Collection } from 'sveltefire'
</script>

<h1>Albums</h1>

<Collection path="/albums" let:data={albums}>
    <ul>
        {#each albums as album}
            <li>
            <a href="/albums/{album.id}">{album.title}</a>
            </li>
        {/each}
    </ul>
</Collection>