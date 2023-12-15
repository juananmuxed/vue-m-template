<template>
  <QCard class="q-ma-xl">
    <QCardSection>
      <h3>⚔️ {{ $t("common.titles.webTitle") }} ⚔️</h3>
      <h5>🎱 {{ $t("common.titles.welcome") }}</h5>
      <p>{{ $t('common.texts.welcome01') }}</p>
      <p>{{ $t('common.texts.welcome02') }}</p>
      <h5>📰 {{ $t("common.titles.news") }}</h5>
      <ul>
        <li>{{ $t('common.texts.news01') }}</li>
      </ul>
      <p>
        {{ $t('common.texts.listAllChanges', {
          url: 'https://github.com/juananmuxed/clash-of-spears-admin/blob/main/CHANGELOG.md',
        }) }}
      </p>
    </QCardSection>
  </QCard>
</template>

<script setup lang="ts">

</script>
