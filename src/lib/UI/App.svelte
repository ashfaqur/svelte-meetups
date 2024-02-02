<script>
    import Header from "$lib/UI/Header.svelte";
    import MeetupsItem from "$lib/Meetups/MeetupsItem.svelte";
    const meetups = [
        {
            id: "m1",
            title: "coding bootcamp",
            subtitle: "Learn to code in 2 hours",
            description: "Hi Hello Bye",
            address: 12345,
            contactEmail: "tarin@gamil.com",
        },
        {
            id: "m2",
            title: "cook together",
            subtitle: "Learn to cook in 2 hours",
            description: "Hi Hello Bye",
            address: 12345,
            contactEmail: "tarin@gamil.com",
        },
    ];
</script>

<Header></Header>
{#each meetups as meetup}
    <MeetupsItem />
{/each}
