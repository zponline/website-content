---
# Course title, summary, and position.
title: Programação
linktitle: Programação
summary: Aulas de lógica de programação, Golang, Python e estrutura de dados.
weight: 1

# Page metadata.
title: Programação
draft: false  # Is this a draft? true/false
toc: false  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
# {{< rawhtml >}}
#      <div id="magicLinkTeacher">Professor: Girafales</div>
#  {{< /rawhtml >}}
#
menu:
  Programação:
    name: Programação
    weight: 1
---



## Introdução

Bem-vindo à página de Programação. Esta é uma aula prática. Aqui você encontrárá:

* **Material Didático**
* **Dicas**
* **Exercícios**
* **Código Fonte**

Para assistir às aulas, é necessário fazer o setup do seu computador. O setup será feito passo-a-passo na primeira aula que você participar.

{{< rawhtml >}}
    <div id="result-error-msg-holder">
        <p id="result-error-msg">Não foi possível realizar o agendamento, <span id="result-msg-second-line">contate um administrador.</span></p>
    </div>
    <div id="result-success-msg-holder">
        <p id="result-success-msg">Classe <span id="result-success-second-line">agendada!</span></p>
    </div>   
    <h2>Próximas Classes:</h2>
    <table id="magicLinkNextClass" class="table table-borderless table-light" >
        <tbody>
            <div id="magicLinkNoClass">Não há novas aulas agendadas para esta classe. Confira no <a href="/calendario/">seu calendário</a> as classes que você já se registrou. Assim que o professor agendar uma nova aula para esta classe, volte aqui e garanta seu assento.</div>
        </tbody>
    </table>
{{< /rawhtml >}}


{{< rawhtml >}}
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/flatpickr/dist/flatpickr.min.css">
    <script src="https://cdn.jsdelivr.net/npm/flatpickr"></script>
    <table id="magicLinkSubscribe" class="table table-borderless table-light" >
        <tbody>
        </tbody>
    </table>
    </div>
    <script src="/js/class.js"></script>
    <script language="javascript">
        window.addEventListener('load', () => getClassLinks(), false)
        window.addEventListener('load', () => getBookingLinks(), false)
    </script>
{{< /rawhtml >}}
