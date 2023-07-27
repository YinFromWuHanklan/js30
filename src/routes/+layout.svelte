<script>
    import { base } from '$app/paths';

    export const prerender = true;
</script>

<nav>
    <a href="{base}/">home</a>
    <a href="{base}/about">about</a>
</nav>

<!-- the page content will be rendered here -->
<slot />