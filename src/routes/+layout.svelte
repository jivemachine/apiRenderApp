<!-- +layout.svelte -->
<script lang="ts">
    // header & footer components
    import Footer from './footer.svelte'
    import Header from './header.svelte'

    // open props 
    import 'open-props/style'
    import 'open-props/normalize'
    import 'open-props/buttons'

    // import app.css
    import '../app.css'
</script>

<div class="layout">
    <!-- Header -->
    <Header />

    <main>
        <slot />
    </main>

    <!-- Footer -->
    <Footer />
</div>