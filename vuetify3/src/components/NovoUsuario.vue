<template>
        <v-card-title>
            <v-dialog width="600px">
                <template #activator="{ props }">
                    <v-btn v-bind="props" variant="tonal" size="small">
                        Adicionar Usuário
                    </v-btn>
                </template>

                <v-card>
                    <v-card-text>
                        <v-row>
                            <v-col>
                                <v-text-field label="Nome" variant="outlined"></v-text-field>
                                <v-text-field label="Email" variant="outlined" :rules="emailRules"></v-text-field>
                            </v-col>
                        </v-row>
                        <v-select label="Cargo" variant="outlined"
                            :items="['Diretor', 'Gerente', 'Analista']">
                        </v-select>
                        <v-btn @click="salvar">Salvar</v-btn>
                    </v-card-text>
                </v-card>
            </v-dialog>
        </v-card-title>
</template>

<script>  
const emailRules = [
    value => {
        if (value) {
            return true
        };
        return 'O email é obrigatório';
    }
]

</script>