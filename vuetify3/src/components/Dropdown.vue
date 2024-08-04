<template>
    <v-menu>
        <template #activator="{ props}">
            <v-avatar v-bind="props">
                <v-img
                    cover
                    src="https://www.psicologo.com.br/wp-content/uploads/sou-uma-pessoa-boa-ou-nao-1024x538.jpg"
                ></v-img>
            </v-avatar>
        </template>

        <v-card min-width="200px">
            <v-list :lines="false" density="compact" nav>
                <v-list-item prepend-icon="mdi-account-outline">
                    <v-list-item-title> Meu perfil </v-list-item-title>
                </v-list-item>
                <v-list-item prepend-icon="mdi-heart-outline">
                    <v-list-item-title> Favoritos </v-list-item-title>
                </v-list-item>
            </v-list>
        </v-card>
    </v-menu>
</template>

<script>
</script>
