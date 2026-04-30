# 04 — Cronômetro / Pomodoro
 
> Timer com start, pause e reset. Com ciclo pomodoro (25min foco, 5min pausa) e barra de progresso.
 
---
 
## Checklist de desenvolvimento
 
### Estrutura do projeto
- [ ] Criar pasta com `index.html`, `style.css` e `script.js`
- [ ] Definir os dois modos: foco (25min) e pausa (5min)
### HTML semântico
- [ ] Usar `<main>` como container
- [ ] Display do tempo em `<time>` ou `<p>` com id claro
- [ ] Botões com `<button>` e texto descritivo (Start, Pause, Reset)
- [ ] Barra de progresso com `<progress>` ou `<div>` estilizado
- [ ] Indicador do modo atual (Foco / Pausa)
### JavaScript
- [ ] Variáveis com `const` e `let`
- [ ] JS em arquivo separado
- [ ] Timer usando `setInterval` e `clearInterval`
- [ ] Função separada para formatar o tempo (`02:00` e não `2:0`)
- [ ] Start: inicia o intervalo
- [ ] Pause: para o intervalo sem zerar o tempo
- [ ] Reset: zera o tempo e para o intervalo
- [ ] Ao chegar em 00:00, trocar automaticamente entre foco e pausa
- [ ] Atualizar a barra de progresso a cada segundo
### CSS
- [ ] Variáveis no `:root` com cor diferente pra cada modo (foco vs pausa)
- [ ] Cor da página/barra muda quando o modo troca
- [ ] Transição suave na troca de modo
- [ ] Display do tempo em fonte grande e legível
- [ ] Botões com estados visuais claros (start ativo vs pausado)
- [ ] Responsivo para mobile
### Qualidade
- [ ] Timer não quebra se clicar em start várias vezes seguidas
- [ ] Pause e retomar funciona sem perder o tempo
- [ ] Testado em todos os estados: foco → pausa → foco
- [ ] README com print do projeto
---
 
## Resultado esperado
Timer funcional que cicla automaticamente entre foco e pausa, com feedback visual claro do estado atual. `setInterval` e `clearInterval` dominados.
