# cute-mint-tutorial

## Conhecimentos Básicos

O Linux Mint é uma distro baseada no Ubuntu.
A guideline do time que mantém o Mint é manter as partes
boas do Ubuntu, como o gerenciador de drivers, e remover as coisas "ruins",
como funcionalidades de telemetria que existem no Ubuntu.

A escadinha do Linux Mint é algo como:

```
Debian > Ubuntu > Linux Mint
```

Isso significa que as fundações sobre as quais o Mint
é construído são bem estáveis.
Caso queira um sistema com funcionalidades mais bleeding edge,
talvez seja interessante usar outras distros quando se sentir
mais confortável com o ambiente Linux.

**Cinnamon**, é o Desktop Environment utilizado na versão do Mint que eu
recomendo e uso. Existem outros "sabores" oferecidos pelo Mint, como Mate
e XFCE, além de outros *DEs* que podem ser instalados e configurados, por
exemplos o Gnome, DE padrão do Ubuntu.

**GTK**, é a tecnologia sobre a qual o Cinnamon é feito.
Se quiser customizar a interface do sistema, um bom começo é pesquisar
como customizar GTK, ou pesquisar temas GTK.

**APT**, é o package manager herdado do Debian.
É possível instalar pacotes/software usando ele, mas tenha em mente que
ele oferece versões estáveis e consequentemente mais antigas de pacotes
que podem estar mais atualizados em outras sources.

**Gnome Terminal**, é o nome do terminal padrão do Mint.
É bom saber o nome caso queira pesquisar como customizá-lo.
Existem sim outras opções de terminais que você pode instalar,
mas costumo usar o padrão.
Algumas menções de terminais alternativos são o Kitty e Ghostty.

**Software Store**, é o instalador de Software com interface.
Nem sempre ele vai ser a melhor opção para instalar as coisas.
Steam e VSCode, por exemplo podem ser baixados por seus respectivos
websites, a partir de um **.deb**.

**.DEB**, é a extensão utilizada para instaladores de pacotes Debian.
É esse tipo de arquivo que você quer baixar quando precisar baixar
algum software pelo navegador.

## Comandos de Terminal

A primeira vez utilizando um sistema Unix pode assustar um pouco
por exigir que você tenha que interagir com um Terminal.
Na maior parte do tempo comandos de navegação e interação com arquivos
já são o suficiente.

```bash
# Neofetch
neofetch

# Listar conteúdo do Diretório atual
ls

# Listar conteúdo do Diretório atual (permissões e arquivos invisíveis também)
ll

# Visualizar estrutura do Diretório atual e seus filhos
# Não recomendo executar isso em um diretório que tenha muitos filhos
tree .

# Navegação (cd)
cd ./.config # Acessar pasta .config na pasta atual

cd .. # Subir para Diretório acima

cd ~  # Home do Usuário

cd /  # Root do Sistema

# Copiar arquivo (cp arquivo destino)
cp ~/Desktop/resumo.txt ~/Documents/

# Mover arquivo (mv arquivo destino)
mv ~/Desktop/resumo.txt ~/Documents/

# Renomear arquivo (mv arquivo novo_arquivo)
# "move" o arquivo source para um arquivo novo
mv ~/Desktop/resumo.txt ~/Desktop/not-resumo.txt
```

## Customização do Sistema

Pessoalmente eu utilizo ou temas do [Dracula](https://draculatheme.com/) ou do
[Catppuccin](https://catppuccin.com/) para tudo.
Se quiser adicionar o Dracula como tema para o GTK, por exemplo, basta pesquisar
no website deles por GTK e seguir as instruções.
Normalmente é algo como: baixar arquivos, mover para root do sistema e relogar.

O ato de customizar o sistema extensivamente é conhecido como **ricing** e não,
não faço ideia da Lore.
Se quiser ver alguns bem legais ou só quiser ver gente com background de anime
eu recomendo o [r/unixporn](https://www.reddit.com/r/unixporn/)
