<template>
    <v-app-bar>
        <v-app-bar-nav-icon variant="text" @click.stop="drawer = !drawer" />
        <v-app-bar-title>Meu app</v-app-bar-title>

        <template #append>
            <v-btn icon class="mr-2">
                <v-badge dot color="info">
                    <v-icon icon="mdi-bell-outline"></v-icon>
                </v-badge>
            </v-btn>
            <Dropdown />
        </template>
    </v-app-bar>
    
    <v-navigation-drawer v-model="drawer" location="left" temporary>
        <v-list>
            <v-list-subheader>Menu</v-list-subheader>
            <v-list-group prepend-icon="mdi-folder-outline">
                <template #activator="{ props }">
                    <v-list-item v-bind="props" title="Opções" />
                </template>

                <v-list-item >
                    <v-btn flat>Opção 1</v-btn>
                </v-list-item>

                <v-list-item>
                    <v-btn flat>Opção 2</v-btn>
                </v-list-item>
            </v-list-group>
            <v-list-item prepend-icon="mdi-folder-outline">
                    <v-btn flat>Opção 3</v-btn>
                </v-list-item>
        </v-list>
    </v-navigation-drawer>
</template>

<script setup>
// vue
import { ref } from 'vue'
// variaveis reativas
const drawer = ref(false)
</script>