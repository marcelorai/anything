<template>
    <div>
        <head>
            <title>Title of the document</title>
            <link href="style.css" rel="stylesheet">
        </head>

        <body>
            <img id="logo" src="../assets/LOGO.png"/>

            <div id="form_borda">
                <div id="form_icons">
                    <img id="icon" src="../assets/do_utilizador.png"/>
                    <label id="cadastro">Cadastre-se</label>
                </div>

                <form action="cadastro_endereco.html">
                    <label class="l85">nome</label> 
                    <br>
                    <input type="text" v-model="nome" required/>
                    <br>
                    <label class="l85">e-mail</label>
                    <br>
                    <input type="email" v-model="email" required/>
                    <br>
                    <label class="l85">CPF</label>
                    <br>
                    <input type="text" v-model="cpf" required/>
                    <br>
                    <label class="l85">sexo</label>
                    <br>
                    <div class="radio">
                        <input type="radio" name="genero" value="Masculino" v-model="sexo" required/>
                        <label>Masculino</label>
                        <input type="radio" name="genero" value="Feminino" v-model="sexo" required/>
                        <label>Feminino</label>
                    </div>
                    <br>
                    <label class="l55">data de nascimento</label>
                    <br>
                    <input type="date" v-model="nascimento" required/>
                    <br>
                    <label class="l84">telefone</label>
                    <br>
                    <input type="text" v-model="telefone" required/>
                    <br>
                    <label class="l84">senha</label>
                    <br>
                    <input type="password" required/>
                    <br>
                    <label class="l55">confirme sua senha</label>
                    <br>
                    <input type="password" required/>
                    <br>
                    <br>
                    <input class="submit" type="submit" value="Criar um cadastro"/>
                    <h6>fique tranquilo, nosso site é seguro
                    <br>
                    já tem um cadastro? <a href="login.html">entrar</a>
                    </h6>
                </form>
            </div>
        </body>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>