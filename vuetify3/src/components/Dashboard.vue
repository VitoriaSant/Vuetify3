<template>

    <v-container>
        <h1>Dashboard</h1>
        <Tabelas />
        <v-row>
            <v-col cols="12" sm="6" md="4">
                <v-card>
                    <v-img class="align-end text-center"
                        src="https://images.pexels.com/photos/724669/pexels-photo-724669.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">
                        <v-card-title class="text-white">Top 10 Receitas Saudáveis</v-card-title>
                    </v-img>
                    <v-card-subtitle class="pt-2">Receitas</v-card-subtitle>
                    <v-card-text>
                        <div>
                            Uma dieta saudável é uma dieta que ajuda a manter ou melhorar a saúde.
                        </div>
                    </v-card-text>
                    <v-card-actions>
                        <v-btn prepend-icon="mdi-check">Ver mais</v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="12" sm="6" md="4">
                <v-card>
                    <v-img class="align-end text-center"
                        src="https://images.pexels.com/photos/724669/pexels-photo-724669.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">
                        <v-card-title class="text-white">Top 10 Receitas Saudáveis</v-card-title>
                    </v-img>
                    <v-card-subtitle class="pt-2">Receitas</v-card-subtitle>
                    <v-card-text>
                        <div>
                            Uma dieta saudável é uma dieta que ajuda a manter ou melhorar a saúde.
                        </div>
                    </v-card-text>
                    <v-card-actions>
                        <v-btn prepend-icon="mdi-check" color="black">Ver mais</v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="12" sm="6" md="4">
                <v-card>
                    <v-img class="align-end text-center"
                        src="https://images.pexels.com/photos/724669/pexels-photo-724669.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">
                        <v-card-title class="text-white">Top 10 Receitas Saudáveis</v-card-title>
                    </v-img>
                    <v-card-subtitle class="pt-2">Receitas</v-card-subtitle>
                    <v-card-text>
                        <div>
                            Uma dieta saudável é uma dieta que ajuda a manter ou melhorar a saúde.
                        </div>
                    </v-card-text>
                    <v-card-actions>
                        <v-btn prepend-icon="mdi-check">Ver mais</v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name: 'Dashboard',
}
</script>
