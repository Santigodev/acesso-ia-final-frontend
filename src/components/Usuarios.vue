<template>
    <div>
        <h2 class="mb-3">Gerenciamento de Usuários</h2>

        <!-- Botão para criar novo -->
        <div class="mb-3">
            <router-link to="/usuario/cadastrar" class="btn btn-success">
                <i class="fa fa-plus"></i> Adicionar novo
            </router-link>
        </div>

        <!-- Tabela de listagem -->
         <table class="table table-striped">
            <thead class="thead-dark">
                <tr>
                    <th>Id</th>
                    <th>Nome</th>
                    <th>Email</th>
                    <th>CPF</th>
                    <th>Status</th>
                    <th>Opções</th>
                </tr>
            </thead>
            <tbody>
                <td>5</td>
                <td>aluno</td>
                <td>alu@gmail.com</td>
                <td>1213131</td>
                <td>Ativo</td>
                <td>
                    <button class="btn btn-primary btn-sm"> 
                    <i class="fa fa-edit"></i> Editar
                    </button>

                    <button class="btn btn-danger btn-sm ml-2"> 
                    <i class="fa fa-trash"></i> Excluir
                    </button>
                </td>
            </tbody>
         </table>

    </div>
</template>
<script>
import axios from 'axios';
export default {
    data() {
        return {
            usuarios: []
        };
    },
    methods: {
        
    }
}
</script>