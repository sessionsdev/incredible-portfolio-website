<script context="module">
  
  import { GraphQLClient, gql } from 'graphql-request'

  const endpoint = 'https://api.github.com/graphql'

  const query = gql`
  query($userName:String!) { 
    user(login: $userName){
      contributionsCollection {
        contributionCalendar {
          totalContributions
          weeks {
            contributionDays {
              contributionCount
              weekday
              date
            }
          }
        }
      }
    }
  }
  `

  const variables = {
    userName: 'sessionsdev',
  }

  const requestHeaders = {
    authorization: 'Bearer XXXXX'
  }


  const graphQLClient = new GraphQLClient()
  graphQLClient.setEndpoint(endpoint)
  graphQLClient.setHeaders(requestHeaders)


  export const load = async () => {
    const data = await graphQLClient.request(query, variables)
    console.log(data)
    return data;
  }
</script>
