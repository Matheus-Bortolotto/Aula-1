<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula 1</title>
</head>
<body>
    <ol type="" start="6">
        <li>Empresa</li>
        <li>Produto</li>
        <li>Serviços</li>
        <li>Contato</li>
    </ol>
    <ul> <!--ul>li.lista*10!-->
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
        <li class="lista"></li>
    </!--ul>
    <div>
        <h1>Receita - Bolo de Chocolate</h1>
        <h2>Ingredientes</h2>
        <ul>
            <li>4 ovos</li>
            <li>4 colheres (sopa) de chocolate em pó</li>
            <li>2 colheres (sopa) de manteiga</li>
            <li>3 xícaras (chá) de farinha de trigo</li>
            <li>2 xícaras (chá) de açucar</li>
            <li>2 colheres (sopa) de fermento</li>
            <li>1 xícaras (chá) de leite</li>
        </ul>
        <h2>Modo de preparo</h2>
        <ol>
            <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus ex ad officia! Temporibus voluptatum quasi ex laudantium harum provident debitis illo cumque in aliquid! In fuga corrupti dignissimos velit porro.</li>
            <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Adipisci quaerat laboriosam odio laudantium, dolorem, illum aut rerum, soluta neque cum in sed! Laudantium facere similique commodi, perspiciatis quam dolores accusamus?</li>
            <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ea nam saepe perspiciatis quasi delectus illum voluptates libero ut suscipit, cupiditate optio sed, in harum molestiae nobis maiores dicta non!</li>
        </ol>
    </div>

    <dl>
        <dt>HTML</dt>
        <dd>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sit nemo corrupti quos totam autem magnam possimus, doloremque dolore distinctio repellendus libero magni quasi dolor ipsa aspernatur ipsum quisquam molestiae, officiis sunt natus similique tempora? Sint?
        </dd>
        <dt>Navegador</dt>
        <dd>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Inventore recusandae, tempora optio, totam cumque omnis ipsa harum nisi id reiciendis aspernatur quam placeat quo a labore enim est neque consectetur?
        </dd>
    </dl>
    
    <table border="1">
        <tr><!--início da linha do cabeçalho-->
            <th colspan="3">Cabeçalho 1</th>
            
        </tr>
        <tr>
            <td>Linha 1 -Coluna 1</td>
            <td>Linha 2 -Coluna 2</td>
            <td>Linha 3 -Coluna 3</td>
        </tr>
        <tr>
            <td>Linha 2 - Coluna 1</td>
            <td>Linha 2 - Coluna 2</td>
            <td>Linha 2 - Coluna 3</td>
        </tr>
        <!--colspan="x" vai fazee uma mesclagem de colunas-->
        <!--rowspan="X" vai mesclar linhas-->
    </table>

    <form>
        <fieldset> 
            <legend>tamanho de camiseta</legend>
        <input type="radio" name="genero" value="masculino"/> 
        <span>masculino</span>
        <input type="radio" name="genero" value="feminino"/>
        <span>feminino</span>
        <input type="radio" name="genero" value="outro"/>
        <span>outro</span>
    
        <div>Aceita termos e condições</div>
        <input type="checkbox" name="aceita" value="1">
        <div><select name="tamanhos">
            <option value="G">Grande</option>
            <option value="M">Médio</option>
            <option value="P">Pequenos</option>
        </select>
        </div>
        <label for="nome_sobrenome">Nome:</label>
        <input type="text" name="nome_sobrenome" placeholder="Digite o seu nome" id="">
    </fieldset> 
    </form>

    <form action="">
        <fieldset>
            <legend>Informações Pessoais</legend>
            <label for="genero">Genero:</label>
            <br>
            <input type="radio" name="genero" value="masculino"/> 
        <span>Masculino</span>
        <input type="radio" name="genero" value="feminino"/>
        <span>Feminino</span>
        <input type="radio" name="genero" value="outro"/>
        <span>Outro</span>
        <br>
        <br>
        <label for="nome">Nome:</label>
        <input type="text" name="nome" placeholder="Digite o seu primeiro nome" id="">
        <br>
        <label for="sobrenome">Sobrenome:</label>
        <input type="text" name="sobrenome" placeholder="Digite o seu Sobrenome" id="">
        <br>
        <br>
        <label for="tamanho">Tamanho:</label>
        <select name="Tamanho" id="tamanhos">
        <option value="G">Grande</option>
        <option value="M">Médio</option>
        <option value="P">Pequenos</option>
        </select>
        <br>
        <br>
        <button>Enviar</button>
        </fieldset>
    </form>
</body>
</html>
