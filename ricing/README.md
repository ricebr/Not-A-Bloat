## Tópicos

- [Por que foi criado este guia?](https://github.com/Valeyard1/Not-A-Bloat/blob/master/ricing/README.md#por-que-foi-criado-este-guia)
- [O que é ricing?](https://github.com/Valeyard1/Not-A-Bloat/blob/master/ricing/README.md#o-que-%C3%A9-ricing)
- [Por onde começar?](https://github.com/Valeyard1/Not-A-Bloat/blob/master/ricing/README.md#por-onde-come%C3%A7ar)

---

### Por que foi criado este guia?

Para os amantes de ricing, a busca por tais conhecimentos nunca foi fácil, pois este conteúdo sempre foi limitado e espalhado. Os iniciantes que se fascinam por esse mundo ficam perdidos por não saberem por onde começar e onde encontrar guias para estudar, pois dos poucos que se encontram, são em inglês.
Este guia tem o objetivo de mostrar que o ricing é algo simples, e que qualquer interessado pode facilmente deixar sua distribuição da maneira que quiser.

### O que é ricing?

De acordo com a wiki do [r/unixporn](https://www.reddit.com/r/unixporn/):
"Rice" é uma palavra que é comumente usada para referir a melhorias visuais e personalizações na área de trabalho. Ela foi herdada da prática de customizar carros de importação asiáticos baratos para fazê-los parecer mais rápidos do que realmente eram - o que também era conhecido como "ricing". Atualmente, a palavra se refere a uma área de trabalho visualmente atraente e modificada além do padrão.
<br/>
<br/>

# Por onde começar?

## _Window Manager_
Primeiro de tudo é necessário escolher um Window Manager. Este [link](https://wiki.archlinux.org/index.php/Window_manager_%28Portugu%C3%AAs%29#Lista_de_gerenciadores_de_janela) contém uma lista de Window Managers (incluindo os que são Tiling, Floating e dinâmicos) para escolher. Cada uma tem uma característica e um jeito diferente de usar/configurar.

- **i3/i3-gaps**:
    Boa WM pra começar, é a que mais tem material sobre como usar, customizar, etc. Mas há alternativas mais mínimas e melhores.

- **bspwm**:
    Uma das WMs mais fáceis de configurar, leve, não gasta muita memória RAM. É necessário um programa externo para configurar os atalhos, o [sxhkd](https://github.com/baskerville/sxhkd), também fácil de configurar.
    _Obs_: Não esqueça de instalar o `sxhkd` e o `dmenu`. Veja este [link](https://mashn.github.io/artigos/instalando-e-configurando-o-bspwm.html) sobre como instalar o bspwm.

- **2bwm**: Uma WM para usuários avançados, extremamente leve (342 KB de uso de ram). Sua configuração é feita diretamente no código fonte, tendo que recompilar a cada mudança, sendo que as cores e as bordas podem ser configuradas no `~/.Xresources`.

## Dúvidas Frequentes
1. Qual a diferença entre um _Window Manager_ e um _Desktop Environment_ (Gnome, KDE, etc.)?
**Re:** Um gerenciador de janelas tem uma única função: gerenciar as janelas. Um DE, além de gerenciar as janelas, apresenta uma gama de pacotes que vem junto com ele, pra facilitar o uso. Por exemplo, ao instalar o XFCE, é instalado o xfwm (gerenciador de janelas do XFCE) e, além dele, é instalado também o xfce4-panel, xfce4-session, xfce4-terminal, etc.

---

**Lista de links úteis:** [awesome-ricing](awesome-ricing.md)
