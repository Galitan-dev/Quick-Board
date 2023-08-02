<script lang="ts">
    import '../app.less';
    import Header from './Header.svelte';
</script>

<svelte:head>
    <title>Quick-Board</title>
    <meta name="description" content="Share, Cast, Connect: Quick-Board for Instant Visuals!" />
</svelte:head>

<Header />

<slot />
