<script>
    import userData from '$lib/data/mockUserGitHubContributions.json';
    import { onMount } from 'svelte';

    onMount(() => {
        console.log(userData.user.contributionsCollection.contributionCalendar.weeks)
    })
</script>
