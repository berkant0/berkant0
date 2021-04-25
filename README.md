  <img align="center" src="https://github-readme-stats.vercel.app/api?username=berkant0&count_private=true&show_icons=true&theme=radical" />
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=berkant0&layout=compact&layout=compact&count-private=true" />
{
  user(login: "<berkant0>") {
    repositories(ownerAffiliations: OWNER, isFork: false, first: 100) {
      nodes {
        name
        languages(first: 10, orderBy: {field: SIZE, direction: DESC}) {
          edges {
            size
            node {
              color
              name
            }
          }
        }
      }
    }
  }
}
