<script>
  import Top from './Top.svelte'
  import Main from './Main.svelte'
  import Missing from './Missing.svelte'
  import FilterList from './FilterList.svelte'
  import Theme from './Theme.svelte'

  import { theme } from '../stores.js'

  export let data

  const pageComponent = {
    'page': { component: Main, level: './' },
    'missing': { component: Missing, level: '../' },
    'servant': { component: FilterList, level: '../' },
    'ce': { component: FilterList, level: '../' }
  }
</script>

<Theme level={pageComponent[data.attribute.type].level} />

<svelte:component this={pageComponent[data.attribute.type].component} {data} level={pageComponent[data.attribute.type].level} />
