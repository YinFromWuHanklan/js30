<script>
    import { base } from '$app/paths';
</script>

<nav>
    <a href="{base}/">home</a>
    <a href="{base}/about">about</a>
</nav>

<!-- here the page content will be rendered -->
<slot />