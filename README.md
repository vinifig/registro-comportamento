# Registro de Comportamento

App web simples para preencher e acompanhar o **registro de auto-observação** (tríplice contingência / ABC):
**Data · Contexto · Comportamento · Consequência · Intensidade (1–5)**.

👉 https://vinifig.github.io/registro-comportamento/

- **Armazenamento só local**: os registros ficam no `localStorage` do navegador. Nada é enviado a servidor.
- Busca e filtros por intensidade e marcadores.
- Aba **Padrões**: turnos, dias da semana, intensidade média por marcador e palavras recorrentes.
- Impressão no formato da folha original (A4 paisagem).
- Backup/restauração em JSON e exportação CSV (abre no Excel/Sheets).
- Funciona offline e pode ser instalado na tela inicial (PWA).

Arquivo único (`index.html`), sem dependências nem build.
