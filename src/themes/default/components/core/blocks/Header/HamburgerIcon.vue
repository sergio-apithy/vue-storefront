<template>
  <button
    type="button"
    class="bg-cl-transparent brdr-none inline-flex"
    @click="openSidebarMenu"
    :aria-label="$t('Open menu')"
    data-testid="menuButton"
  >
    <i class="material-icons">dehaze</i>
  </button>
</template>

<script>
import HamburgerIcon from 'core/components/blocks/Header/HamburgerIcon'

export default {
  mixins: [HamburgerIcon]
}
</script>
