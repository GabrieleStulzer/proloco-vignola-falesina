<script>
	import PremiList from "../components/PremiList.svelte";

</script>
<svelte:head>
    <title>Home | Pro Loco Vignola Falesina</title>
</svelte:head>

<div class="bg-white rounded-2xl p-2 shadow-xl">
    <h1 class="text-3xl">Lotteria Sagra di Sant'Antonio</h1>

    <h2>Lotteria</h2>
    <p>Estrazione avveunta il 16 Giugno 2024</p>

    <h3>Premi</h3>
    <PremiList />

    <div class="">
        <h3>Informazioni</h3>
        <p>Per ritirare i premi inviare una mail a lotteria@prolocovignolafalesina.it oppure telefonare al numero +39 348 237 9237</p>
        <p>Il ritiro dei premi va effettuato entro 30 giorni dall'estrazione</p>
    </div>
</div>


<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
    }

    h2 {
        font-size: theme(fontSize.2xl);
        font-weight: theme(fontWeight.bold);
        padding-top: theme(spacing.2);
    }

    h3 {
        font-size: theme(fontSize.xl);
        font-weight: theme(fontWeight.bold);
        padding-top: theme(spacing.1);
    }
</style>
