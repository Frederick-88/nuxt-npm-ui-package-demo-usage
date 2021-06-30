<template>
  <div>
    <SampleButton :disabled="true">Disabled-Sample-Primary-Button</SampleButton>
    <SampleButton :is-primary="true">Sample-Primary-Button</SampleButton>
    <SampleCheckbox :is-checked="true" label="checked-default" />
    <SampleCheckbox :is-checked="true" :is-primary="true" label="primary" />
  </div>
</template>

<script>
export default {};
</script>
