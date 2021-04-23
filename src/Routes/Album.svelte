<script>
    import { Doc } from 'sveltefire'

    export let id
</script>

<Doc path="/albums/{id}" let:data={album}>
    <h1>{album.title}</h1>
    <p>{album.artist}</p>
    <ol>
    {#each album.tracks as track}
        <li>{track.title}</li>
    {/each}
    </ol>
</Doc>
