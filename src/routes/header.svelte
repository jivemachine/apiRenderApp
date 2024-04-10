<script lang="ts">
    // default config settings
    import * as config from '$lib/config'
</script>

<!-- navbar -->
<nav>
    <!-- Title -->
    <a href="/" class="title">
        <b>{config.title}</b>
    </a>

    <!-- actual nav -->
    <ul class="links">
        <li>
            <a href="/about">About</a>
        </li>
        <li>
            <a href="/contact">Contact</a>
        </li>
        <li>
            <a href="/blog">Start Learning</a>
        </li>
    </ul>

    <!-- Theme -->
    <button>Toggle</button>
</nav>