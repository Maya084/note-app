<script lang="ts">
    import Note from "@/components/Note.svelte";
</script>

<div class="note-card" on:click >
    <Note
    id={1234}
    title={"Some Note"}
    content={"This note is about this and that"}
    tags={["test", "text"]}
    date={"20210806120000"}
    isFavorite={false}
    />
</div>
