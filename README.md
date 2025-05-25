# 🚔 Cidade Real — Base Unity Clean para FiveM

Base desenvolvida para contribuir com a comunidade FiveM, oferecendo um ponto de partida limpo, funcional e otimizado para servidores **RP**. Ideal para quem deseja construir seu próprio projeto com performance e organização.

🔄 Atualizações de correções serão postadas neste repositório. Para **conteúdos adicionais**, acesse o nosso [Discord](https://discord.gg/pbT5wVp8e9).

---

## 🧱 Tecnologias Utilizadas

* Framework: [Unity vRPex](https://docs.fivem.net/natives/)
* Banco de dados: [oxmysql](https://github.com/overextended/oxmysql)

---

## 📁 Estrutura do Projeto

```
Base-Unity-Clean/
├── README.md
└── UnityVrpex/
    ├── LEIA.txt
    ├── artifacts/
    ├── Base/
        ├── Banco de Dados.sql
        ├── cache/
        ├── citizen/
        ├── config/
        ├── logo.png
        ├── resources/
        │   ├── [Core]/
        │   ├── [Smartphone]/
        │   ├── [System]/
        │   ├── [vRP]/
        │   ├── oxmysql/
        │   └── vrp_oxmysql/
        └── start.bat
```

---

## ⚙️ Requisitos

* [FiveM Server Artifacts](https://runtime.fivem.net/artifacts/fivem/)
* [MySQL Server](https://www.mysql.com/)
* [oxmysql](https://github.com/overextended/oxmysql)
* [Node.js](https://nodejs.org/) (caso necessário para scripts)
* Git

---

## 🚀 Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/BrunoHoinacki/CidadeReal.git
   ```

2. Importe o banco `Banco de Dados.sql` no seu MySQL.

3. Edite o `config/server.cfg` com suas configurações (porta, DB, nome do servidor, etc).

4. Inicie o servidor com:

   ```bash
   start.bat
   ```

---

## 🧪 Vídeo Tutorial

Assista ao [vídeo tutorial no YouTube](https://youtu.be/A8k84Tor5jg) para aprender como colocar a base online.

### Links mencionados:

* [XAMPP](https://www.apachefriends.org/pt_br/index.html)
* [HeidiSQL](https://www.heidisql.com/)
* [Artifacts (versão recomendada)](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master)
* [FiveM Key](https://keymaster.fivem.net/login)
* [Steam Web API Key](https://steamcommunity.com/dev/apikey)

---

## 👥 Como desativar NPCs?

No `start.bat`, adicione após a linha `+set sv_enforceGameBuild 2612`:

```bash
+set onesync_population false
```

---

## 🖼️ Imagens dos Itens

Faça download das imagens e extraia na pasta `C:\xampp\htdocs`:

📦 [Download das Imagens](https://drive.google.com/file/d/1AOrzhV2ytcg-tNu8QsdwRL7fPTKnK_AT/view?usp=sharing)

---

## 📂 Organização dos Recursos

Os scripts estão organizados em:

* `[Core]`: Núcleo do servidor
* `[vRP]`: Framework e dependências
* `[Smartphone]`: Sistema de celular
* `[System]`: Scripts e sistemas diversos
* `oxmysql` e `vrp_oxmysql`: Conexões com banco

---

## 📌 Observações Importantes

* Leia o arquivo `LEIA.txt` antes de iniciar o servidor.
* Configure corretamente o acesso ao banco no `server.cfg` e nos scripts que utilizam `oxmysql`.
* Esta base visa facilitar customizações futuras e minimizar conflitos entre scripts.

---

## 🤝 Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/77410497?s=400&u=fa685e95f61bdc3f90e07ebc3122d78dc3f7c071&v=4" width="100px;" alt="Foto do Tio Dan"/><br>
        <sub><b>DaniloRds</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 👨‍💻 Autor

Organizado por [Bruno Hoinacki](https://github.com/BrunoHoinacki)

---

## 📜 Licença

Uso livre para aprendizado e desenvolvimento. Para uso comercial, revise as licenças dos scripts incluídos.

---