name: 🐛 Bug Report
description: Reporta un problema o comportamiento inesperado
title: "[BUG] "
labels: ["bug"]
assignees: []

body:
  - type: input
    id: title
    attributes:
      label: "Título"
      placeholder: "Describe el problema en una frase"
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: "👟 Pasos para reproducir"
      description: "¿Cómo reproducimos este bug? Explica paso por paso."
      placeholder: |
        1. Ir a '...'
        2. Hacer click en '...'
        3. Observar error
      render: markdown
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: "👍 Comportamiento esperado"
      placeholder: "Lo que debería haber pasado..."
      render: markdown
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: "👎 Comportamiento actual"
      placeholder: "Lo que realmente pasó (puedes incluir capturas)"
      render: markdown
    validations:
      required: true

  - type: input
    id: version
    attributes:
      label: "🧠 Versión del módulo afectado"
      placeholder: "p.ej.: preproc v0.1.2"
    validations:
      required: true

  - type: dropdown
    id: os
    attributes:
      label: "💻 Sistema operativo"
      options:
        - "Windows"
        - "macOS"
        - "Linux"
        - "Otro"
    validations:
      required: true

  - type: textarea
    id: env
    attributes:
      label: "🧱 Entorno"
      description: "Versión de Python, librerías, hardware, etc."
      placeholder: "Python 3.10, CUDA 12.2, etc."
      render: markdown

  - type: checkboxes
    id: duplicates
    attributes:
      label: "👀 ¿Buscaste un issue similar?"
      options:
        - label: "Sí, revisé y no encontré duplicados"
          required: true

  - type: checkboxes
    id: code_of_conduct
    attributes:
      label: "🏢 ¿Leíste el Código de Conducta?"
      options:
        - label: "Sí, he leído el Código de Conducta"
          required: true
