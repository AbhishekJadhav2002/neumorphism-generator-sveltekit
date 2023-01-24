<script>
    import '../styles/global.css'
    import Navbar from '../lib/navbar.svelte'
    import Footer from '../lib/footer.svelte'
</script>

<svelte:head>
  <title>Neumorphism Generator</title>
</svelte:head>

<div class='page'>
    <header>
        <Navbar />
    </header>
    <main>
        <slot></slot>
    </main>
    <footer>
        <Footer />
    </footer>
</div>