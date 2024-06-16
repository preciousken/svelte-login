<!-- src/routes/+page.svelte -->
<script>
    import Header from "../components/Header.svelte";
    import LoginCard from "../components/LoginCard.svelte";
    import Footer from "../components/Footer.svelte";
</script>

<Header title="Welcome to SvelteKit" />
<main class="p-4 flex justify-center items-center min-h-[80vh] ">
    <LoginCard />
</main>
<!-- <Footer /> -->
