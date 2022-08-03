<script>
    import GithubRepoCard from "./GithubRepoCard.svelte";
</script>

<GithubRepoCard />


<!-- 

query MyQuery {
    user(login: "sessionsdev") {
      bio
      repositories(
        first: 10
        privacy: PUBLIC
        orderBy: {field: PUSHED_AT, direction: DESC}
      ) {
        edges {
          node {
            id
            name
            pushedAt
            updatedAt
            url
            description
          }
        }
      }
    }
  }

   -->

<!-- 

   query MyQuery {
    user(login: "sessionsdev") {
      contributionsCollection {
        contributionCalendar {
          weeks {
            contributionDays {
              date
              contributionCount
              color
              weekday
            }
            firstDay
          }
          totalContributions
        }
      }
    }
  }

   -->