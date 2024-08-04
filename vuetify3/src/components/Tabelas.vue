<template>
    <v-card flat class="border mb-4">
        <div class="d-flex justify-space-between">
            <v-card-title> Ultimos usuários</v-card-title>
            <NovoUsuario />
        </div>
        <v-table density="compact">
            <thead>
                <tr>
                    <th>Nome </th>
                    <th>Email </th>
                    <th>Cargo</th>
                    <th>Ações</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Nome 1</td>
                    <td>Email 1</td>
                    <td><v-chip color="success" variant="outlined" size="small">Admin</v-chip></td>
                    <td> <v-btn variant="tonal" color="primary" density="compact">Editar</v-btn></td>
                </tr>
                <tr>
                    <td>Nome 2</td>
                    <td>Email 2</td>
                    <td><v-chip color="primary" variant="outlined" size="small">Gerente</v-chip></td>
                    <td> <v-btn variant="tonal" color="primary" density="compact">Editar</v-btn></td>
                </tr>
            </tbody>
        </v-table>
    </v-card>
</template>

<script setup>
</script>  