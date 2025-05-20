<script setup>
const cities = [
  { id: 1, name: "Brighton" },
  { id: 2, name: "Bristol" },
  { id: 3, name: "Birgmingham" },
  { id: 4, name: "Bolton" },
  { id: 5, name: "Bradford" },
  { id: 6, name: "Bromley" },
  { id: 7, name: "Crewe" },
  { id: 8, name: "Colchester" },
  { id: 9, name: "Chester" },
  { id: 10, name: "Chelmsford" },
  { id: 11, name: "Cambridge" },
  { id: 12, name: "Portsmouth" },
  { id: 13, name: "Coventry" },
  { id: 14, name: "Croydon" },
  { id: 15, name: "Durham" },
  { id: 16, name: "Derby" },
  { id: 17, name: "Doncaster" },
  { id: 18, name: "Darlington" },
  { id: 19, name: "Dudley" },
  { id: 20, name: "Dartford" },
  { id: 21, name: "Enfield" },
  { id: 22, name: "Guildford" },
  { id: 23, name: "Glouchester" },
  { id: 24, name: "Harrow" },
  { id: 25, name: "Hemel-Hempstead" },
  { id: 26, name: "Huddersfield" },
  { id: 27, name: "Ipswich" },
  { id: 28, name: "Ilford" },
  { id: 29, name: "Kingston-upon-Thames" },
  { id: 30, name: "Leeds" },
  { id: 31, name: "Liverpool" },
  { id: 32, name: "Luton" },
  { id: 33, name: "Leicester" },
  { id: 34, name: "Middlesbrough" },
  { id: 35, name: "Milton-Keynes" },
  { id: 36, name: "Manchester" },
  { id: 37, name: "Nottingham" },
  { id: 38, name: "Northampton" },
  { id: 39, name: "Newcastle" },
  { id: 40, name: "Norwich" },
  { id: 41, name: "Oxford" },
  { id: 42, name: "Oldham" },
  { id: 43, name: "Peterborough" },
  { id: 44, name: "Reading" },
  { id: 45, name: "Redhill" },
  { id: 46, name: "Romford" },
  { id: 47, name: "Stoke-on-Trent" },
  { id: 48, name: "Sheffield" },
  { id: 49, name: "Stevenage" },
  { id: 50, name: "Swindon" },
  { id: 51, name: "Sunderland" },
  { id: 52, name: "Slough" },
  { id: 53, name: "Stockport" },
  { id: 54, name: "StAlbans" },
  { id: 55, name: "Twickenham" },
  { id: 56, name: "Uxbridge" },
  { id: 57, name: "Wigan" },
  { id: 58, name: "Warrington" },
  { id: 59, name: "Wolverhampton" },
  { id: 60, name: "Wakefield" },
  { id: 61, name: "Watford" }
]
</script>

<template>
  <div class="container">
    <div class="row">
      <ul class="col-12">
        <li v-for="city in cities" :key="`city-id-${city.id}`">
          <NuxtLink :to="`/local-emergency-locksmith-services-${city.name}`">{{ city.name }}</NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped lang="scss">
ul {
  padding-left: 1rem;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr; 
  @media screen and (max-width: 700px) {
    grid-template-columns: 1fr 1fr;
  }
  li {
    list-style-type: '✓';
    text-align: left;
    color: #3CB371;
    padding-left: 10px;
    a {
      text-decoration: none;
      color: rgb(44, 44, 44);
    }
  }
}
</style>