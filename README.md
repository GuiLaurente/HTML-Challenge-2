  <h1>Cadastro</h1>
  
  <label for="Nome">Nome:</label>
  <br>
  <input name="Nome" id="Nome" placeholder="Ex:Guilherme Laurente" required autofocus>
  <br>
  <br>

  <label for="Email">Email:</label>
  <br>
  <input type="email" name="Email" id="Email" placeholder="Ex:guilherme@gmail.com" required>
  <br>
  <br>

  <label for="Idade">Idade:</label>
  <br>
  <input type="number"  name="Idade" id="Idade" min="12" step="1" placeholder="Ex:14" required>
  <br>
  <br>

  <label for="Data">Data:</label>
  <br>
  <input type="date" name="Data" id="Data">
  <br>
  <br>

  <label>Onde você possui conta:
    <br>
    <input type="checkbox" name="Insta" id="Insta"><label for="Insta">Instagram</label>
    <input type="checkbox" name="Face" id="Face"><label for="Face">Facebook</label>
    <input type="checkbox" name="YT" id="YT"><label for="YT">YouTube</label>
  </label>
  <br>
  <br>

  <label>Sexo:
    <br>
    <input type="radio" id="Masc" name="Sexo" value="Masc"checked><label for="Masc">Masculino</label>
    <input type="radio" id="Fem" name="Sexo" value="Fem"><label for="Fem">Feminino</label>
    <input type="radio" id="PND" name="Sexo" value="PND"><label for="PND">Prefiro não dizer</label>
  </label>
  <br>
  <br>

  <label for="Cor">Cor dos Olhos:</label>
  <input type="color" id="Cor" name="Cor">
  <br>
  <br>

  <label for="Biografia">Biografia:</label>
  <br>
  <textarea id="Biografia" name="Biografia" rows="7" cols="40" required placeholder="Ex:Oi, meu nome é Guilherme Laurente e estudo programação[...]"></textarea>
  <br>
  <br>

  <label for="foto">Foto de Perfil:</label>
  <br>
  <input type="file" accept="images/*" id="foto" name="foto" required>
  <br>
  <br>

  <label for="Telefone">Telefone:</label>
  <br>
  <input type="tel" inputmode="numeric" id="Telefone" name="Telefone" required placeholder="Ex:+55 11 93344-5566">
  <br>
  <br>

  <label for="Link">Link do perfil de YouTube, Instagram ou Facebook:</label>
  <br>
  <input type="url" id="Link" name="Link">
  <br>
  <br>

  <label for="Senha">Senha:</label>
  <br>
  <input type="password" minlength="8" maxlength="16" id="Senha" name="Senha" required>
  <br>
  <br>

  <button type="reset" name="butaum">Limpar</button>
  <button type="submit" name="otro-butaum">Enviar Dados</button>
