<template>
    <div class="container mt-4">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <h2 class="text-center mb-4"> 
                    Cadastrar Novo Usuário</h2>

            <!-- Corpo do Formulário -->
             <form>
                <div class="form-group mb-4">
                    <label for="nome">Nome</label>
                    <input type="text" class="form-control"
                    required placeholder="Informe o nome">
                </div>

                <div class="form-group mb-4">
                    <label for="email">Email</label>
                    <input type="text" class="form-control"
                    required placeholder="Informe o email">
                </div>

                <div class="form-group mb-4">
                    <label for="email">Cpf</label>
                    <input type="text" class="form-control"
                    required placeholder="Informe o cpf">
                </div>

                <div class="form-group mb-4">
                    <label for="status">Status</label>
                    <select class="form-control" required>
                    <option value="ativo">Ativo</option>    
                    <option value="inativo">Inativo</option> 
                    </select>
                </div>

                <div class="text-center">
                    <button type="submit" class="btn btn-success">
                        <i class="fa fa-save"></i> Salvar
                    </button>
                </div>


             </form>

            </div>
        </div>

    </div>
</template>