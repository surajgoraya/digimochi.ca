<script>
    import { page } from '$app/stores';
</script>

<svelte:head>
    <title>DigiMochi ✦ Not Found.</title>
</svelte:head>
<div class="container">
    <div class="row centred">
        <h1 class="heading m-0">{$page.status}</h1>
        <h2 class="light">{$page.error?.message}</h2>
    </div>
</div>