# Nemo

**Notas adesivas gratuitas para a área de trabalho do Windows. As notas são salvas na hora neste PC e, ao entrar na sua conta, você usa as mesmas notas em vários PCs e na web.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%207%20%2F%208%20%2F%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/nemo?lang=pt)

![Tela do Nemo](images/nemo-en.png)

## Visão geral

O Nemo permite anotar uma ideia numa nota e grudá-la na área de trabalho. Cada nota tem um título e um corpo, e se salva sozinha quando você para de digitar. Você pode dar a cada nota a sua própria cor e fixá-la acima das outras janelas; posição, tamanho e fixação voltam exatamente como estavam na próxima vez que você abrir o Nemo.

As notas são **salvas primeiro neste PC**, então você pode usar o Nemo sem entrar numa conta e até sem internet. Entre com uma conta Kilho.net e suas notas são sincronizadas com o servidor, para você ver e editar as mesmas notas no Nemo dos seus outros PCs e no [Web Memo](https://webmemo.kilho.net).

## Recursos

- **Notas na área de trabalho** — as janelas de nota não ocupam espaço na barra de tarefas nem no Alt+Tab, e continuam na área de trabalho quando você fecha a janela da lista.
- **Salvamento automático** — a nota é salva 3 segundos depois que você para de digitar, ou quando clica em outro lugar. Não existe botão Salvar.
- **Lembra onde você deixou** — posição, tamanho, fixação e quais notas estavam abertas são lembrados e restaurados na próxima abertura.
- **6 cores** — Padrão · Amarelo · Verde · Azul · Roxo · Rosa. Na lista, cada linha aparece na cor da sua nota, para distinguir de relance.
- **Sempre visível** — uma nota fixada nunca fica escondida atrás de outras janelas.
- **Pesquisa de notas** — a lupa da janela da lista pesquisa títulos e corpos.
- **Atalho de nova nota** — pressione **Ctrl+Shift+N** em qualquer programa para abrir uma nota nova. A tecla pode ser trocada.
- **Funciona sem servidor** — entrar numa conta é opcional. Ao sair, as notas deste PC continuam.
- **Sincronização entre PCs e a web** — com a conta conectada, o Nemo sincroniza com o servidor 2 segundos depois de salvar, a cada 10 minutos ou quando você clica em **Sincronizar**. Se a mesma nota foi editada em dois lugares, nenhuma edição é descartada: as duas ficam, uma como **cópia de conflito**.
- **Login seguro pelo navegador** — você nunca digita sua senha no Nemo. O login com a conta Kilho.net é feito no navegador que você já usa (OAuth 2.0 + PKCE).
- **Emoji** — coloque emoji nos títulos e corpos.
- **22 idiomas** — segue o idioma de exibição do Windows, ou escolha um nas Configurações.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/nemo?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/nemo?lang=pt&nosetup) |

Na primeira instalação, o instalador ativa **Iniciar com o Windows**. Na versão portátil, descompacte o ZIP e execute `Nemo.exe`. A versão portátil guarda suas notas na mesma pasta do programa, então mover a pasta leva as notas junto.

## Uso

### Primeiros passos

1. Abra o Nemo. A janela da lista abre e um ícone do Nemo aparece na área de notificação (bandeja).
2. Clique com o botão direito num espaço vazio da lista ou no ícone da bandeja e escolha **Nova nota**. (Você também pode pressionar **Ctrl+Shift+N** em qualquer lugar.)
3. A nota nova abre com o campo de título pronto. Digite um título e pressione **Enter** para ir ao corpo.
4. Digite o corpo. Quando você para de digitar, a nota é salva 3 segundos depois e aparece na lista.
5. Deixe a nota em qualquer lugar da área de trabalho. Arraste a barra de título para movê-la e uma borda para redimensioná-la.
6. Quando terminar, clique no **✕** da nota. Ela é salva e fechada. Para abri-la de novo, dê um clique duplo nela na lista.

### Layout da tela

**Janela da lista**

| Elemento | Descrição |
|---|---|
| Lupa (barra de título) | Pesquisar notas. Procura nos títulos e corpos; **ESC** fecha |
| Engrenagem (barra de título) | Configurações |
| ✕ (barra de título) | Esconde a janela da lista na bandeja. O Nemo continua aberto |
| Lista de notas | Mostrada na ordem em que as notas foram criadas, cada linha na cor da sua nota. Clique duplo para abrir a nota |
| Barra de status, esquerda | **Notas: n** |
| Barra de status, direita — ícone de nuvem | Conexão com o servidor. Passe o mouse para ver **Salvo apenas neste PC** · **Conectado ao servidor (conta)** · **Última sincronização**; clique para abrir a página **Servidor** das Configurações |

**Janela da nota**

| Elemento | Descrição |
|---|---|
| Barra de título | Arraste para mover a nota. Clique duas vezes no título ou dê um clique duplo para renomear. Botão direito abre o menu da nota |
| Alfinete | Liga ou desliga **Sempre visível**. Desligado aparece como um alfinete riscado |
| ✕ | Salvar e fechar |
| Corpo | O texto da nota. Uma barra de rolagem aparece quando o mouse está sobre ela |
| Bordas | Arraste para redimensionar |

**Menu do botão direito**

| Menu | Onde | O que faz |
|---|---|---|
| **Nova nota** | Lista · Bandeja | Abre uma nota em branco |
| **Lista** | Bandeja (quando a janela da lista está escondida) | Mostra a janela da lista de novo |
| **Editar** | Lista (sobre uma nota) · Barra de título da nota | Abre a nota / renomeia |
| **Excluir** | Lista (sobre uma nota) · Barra de título da nota | Pergunta uma vez e exclui |
| **Cor ▸** | Lista (sobre uma nota) · Barra de título da nota | Escolha uma das 6 cores. Salvo na hora |
| **Configurações** | Lista · Bandeja | Abre as Configurações |
| **Kilho.net** | Lista · Bandeja | Página de apresentação do Nemo |
| **Sair** | Lista · Bandeja | Pergunta uma vez e fecha o Nemo. As notas abertas voltam na próxima abertura |

### Dicas para situações comuns

**Quando uma ideia surge no meio do trabalho**
Mesmo usando outro programa, pressione **Ctrl+Shift+N** e uma nota nova aparece na frente. Digite um título, pressione Enter, digite o corpo e deixe — ela se salva sozinha.

**Quando você quer uma nota sempre à vista**
Clique no alfinete da nota para ligar **Sempre visível**; outras janelas não vão cobri-la. Clique de novo para desligar. A fixação também volta na próxima abertura.

**Quando suas notas ficam escondidas atrás de outras janelas**
Clique com o botão esquerdo no ícone do Nemo na bandeja para trazer todas as notas abertas para a frente. A janela da lista fica onde está. Se precisar da janela da lista, clique com o botão direito no ícone da bandeja e escolha **Lista**.

**Quando você quer separar as notas por tipo**
Combine as cores — amarelo para tarefas, azul para trabalho, e assim por diante. Clique com o botão direito na barra de título de uma nota ou numa nota da lista → **Cor ▸**, e a nota e a linha dela na lista mudam de cor na hora.

**Quando há notas demais para achar uma**
Clique na lupa da barra de título da janela da lista e digite o que procura. Ficam só as notas com esse texto no título ou no corpo. Pressione **ESC** para fechar a pesquisa e ver a lista inteira de novo.

**Quando você só quer renomear uma nota**
Clique no título da nota e, um instante depois, clique de novo (como ao renomear um arquivo no Explorador de Arquivos), dê um clique duplo ou clique com o botão direito na barra de título → **Editar**. **Enter** confirma, **Esc** volta ao título anterior. Clicar em outro lugar também mantém o que você digitou.

**Quando você quer tirar a lista do caminho, mas manter as notas**
Clique no **✕** da janela da lista; ela vai para a bandeja e suas notas continuam na área de trabalho. Para fechar o Nemo de vez, escolha **Sair** no menu da bandeja.

**As notas voltam exatamente onde você deixou**
Mesmo que você desligue o Windows ou saia do Nemo com notas abertas, elas reaparecem no mesmo lugar e tamanho na próxima vez que você abrir o Nemo. Se uma nota fosse parar fora da tela porque a configuração de monitores mudou, ela é trazida de volta para dentro da tela.

**Quando você quer ver suas notas toda vez que o PC liga**
Ative **Iniciar com o Windows** em Configurações → **Geral** (com o instalador já vem ativado). Quando o Windows inicia, o Nemo abre discretamente na bandeja, sem a janela da lista, e só as notas que você deixou abertas aparecem na área de trabalho.

**Quando você quer as mesmas notas no trabalho e em casa**
Nos dois PCs, clique em **Entrar** em Configurações → **Servidor**. O navegador abre; entre com sua conta Kilho.net e, quando aparecer a página "Login realizado", feche-a e volte ao Nemo. A partir daí as notas se sincronizam sozinhas 2 segundos depois de salvar e a cada 10 minutos. Para sincronizar agora, clique em **Sincronizar**.

**Quando você está longe do seu PC**
Entre no [Web Memo](https://webmemo.kilho.net) com a conta que você usa no Nemo para ver e editar as mesmas notas. As mudanças feitas na web chegam às notas do Nemo na próxima sincronização.

**Quando a mesma nota foi editada em dois PCs**
Nada é sobrescrito. Uma versão fica como a nota original e a outra vira uma nota nova com **(cópia de conflito)** no fim do título. Compare as duas, junte o que precisar numa só e exclua a outra.

**Quando você já tem notas de antes de entrar na conta**
Ao entrar, as notas deste PC sobem para essa conta e as notas do servidor descem para este PC, tudo numa só lista. Se o PC já foi usado com outra conta, o Nemo pergunta antes "Você entrou com outra conta. Mesclar as notas deste PC nesta conta?" — escolha **Não** e o Nemo não entra na conta.

**Quando você quer parar de sincronizar e manter as notas só neste PC**
Clique em **Sair** em Configurações → **Servidor**. As notas deste PC continuam, e a barra de status muda para **Salvo apenas neste PC**. As notas do servidor e dos seus outros PCs não são alteradas.

**Quando você está sem internet**
As notas são sempre salvas primeiro neste PC, então continue usando o Nemo normalmente. Quando a conexão voltar, elas sobem para o servidor na próxima sincronização.

**Quando você quer outro atalho de nova nota**
Clique na caixa **Atalho (nova nota)** em Configurações → **Geral**; ela muda para "Pressione uma tecla". Pressione a combinação desejada (por exemplo Ctrl+Alt+M) e ela vale na hora. Se outro programa já usa essa tecla, o Nemo avisa, então escolha outra.

**Quando você quer levar o Nemo num pen drive**
Descompacte a versão portátil no pen drive e execute-a de lá. As notas ficam na mesma pasta, então as mesmas notas abrem em qualquer PC em que você o conectar.

**Quando você desinstala e reinstala o Nemo**
Desinstalar a versão do instalador não apaga suas notas. Instale de novo e suas notas continuam lá.

**Quando você desliga o Windows**
O Nemo nunca atrasa o desligamento. Ele salva as notas que você estava escrevendo e fecha junto com o Windows.

**Quando você abre o Nemo de novo e não vê nenhuma janela**
Só uma cópia do Nemo roda por vez. Se você abri-lo quando ele já está rodando, a janela da lista sai da bandeja para a frente.

## Configuração

Abra pela engrenagem da janela da lista ou por **Configurações** no menu do botão direito. As mudanças valem na hora; não há botão OK.

| Página | Item | Padrão |
|---|---|---|
| Geral | Iniciar com o Windows | Ligado no instalador, desligado na versão portátil |
| Geral | Atalho (nova nota) | Ctrl+Shift+N |
| Geral | Idioma | Sistema (idioma de exibição do Windows) |
| Servidor | Conta — Entrar / Sair | Sem login |
| Servidor | Sincronização — hora da última sincronização, Sincronizar | Aparece só com a conta conectada |
| Sobre | Versão · Autor · Site · Licenças | — |

Com **Sistema**, o idioma segue o idioma de exibição do Windows; escolha um na lista e ele troca na hora. O árabe é exibido da direita para a esquerda.

## Requisitos

- Windows 7 · 8 · 8.1 · 10 · 11 (32 bits · 64 bits)
- Não precisa de runtime adicional.
- Conexão com a internet e conta Kilho.net são necessárias só para a sincronização com o servidor.

## Atualizações

O Nemo **não** se atualiza sozinho. Ao iniciar, verifica se há uma versão nova e mostra um aviso; ao pressionar **Sim**, a página de download é aberta e o programa é encerrado. As novas versões são publicadas manualmente após verificação interna e anunciadas na [página do Nemo](https://kilho.net/nemo). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

## Licença

O Nemo é **freeware**. Você pode usá-lo de graça em qualquer lugar — no escritório, em casa, em órgãos públicos ou na escola — e redistribuí-lo livremente.

## Links

- Site: <https://kilho.net/nemo>
- Página do Nemo: <https://nemo.kilho.net>
- Web Memo: <https://webmemo.kilho.net>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
