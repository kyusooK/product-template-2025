<script setup>
import {
  VerticalNavLink,
  VerticalNavSectionTitle,
} from '@layouts'
</script>

<template>
    <ul>
        <VerticalNavSectionTitle :item="{ heading: 'Product' }" />
        <VerticalNavLink
            :item="{
                title: 'Product',
                to: '/products',
            }"
        />
    </ul>
</template>
