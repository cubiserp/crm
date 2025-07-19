<template>
  <SettingsPage
    doctype="ERP CRM Settings"
    :title="__('ERP settings')"
    :successMessage="__('ERP settings updated')"
    class="p-8"
  />
</template>
<script setup>
import SettingsPage from '@/components/Settings/SettingsPage.vue'
</script>