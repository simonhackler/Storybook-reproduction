<script module>
  import { defineMeta } from '@storybook/addon-svelte-csf';
  import Page from '../routes/+page.svelte';

  const { Story } = defineMeta({
    title: 'Example/Page',
    component: Page,
    parameters: {
      layout: 'fullscreen',
    },
  });
</script>

<Story name="Basic"  />
