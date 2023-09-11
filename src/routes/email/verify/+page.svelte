<script>
    import { page } from '$app/stores';
    
    const test = $page.url.searchParams.get('test');
</script>

<h1>{test}</h1>