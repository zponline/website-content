---
# Course title, summary, and position.
title: Matemática
linktitle: Matemática
summary: Aulas de Matemática, Álgebra, Geometria e até Cálculo Integral.
weight: 1

# Page metadata.
title: Matemática
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
  Matemática:
    name: Matemática
    weight: 1
---



## Introdução

Aqui você encontrárá:

* **Material Didático**
* **Dicas**
* **Exercícios**

Aqui você também verá conteúdo específico para as aulas que os professores criarão.

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
