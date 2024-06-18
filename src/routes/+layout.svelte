<script>
    import "../app.css";
</script>

<header class="p-4 flex justify-center align-middle">
    <img src="/LogoProloco.png" alt="VVF" class="h-32 m-2"/>
</header>
<div class="flex justify-center mb-10">
    <div class="p-2 max-w-2xl w-full">
        <slot />
    </div>
</div>

<div>
    <footer class="p-4 bg-gray-200 text-center">
        <p>Pro Loco Vignola Falesina</p>
        <p>Frazione Falesina, 1 - Vignola Falesina Trento</p>
    </footer>
</div>