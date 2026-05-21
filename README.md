# 🛡️ CyberJump — A Saga do Hacker Branco

Um platformer estilo Super Mario Bros com temática de **cibersegurança**: você controla o *Pentester Pixel*, um hacker ético de capuz, que precisa atravessar a internet corrompida pra derrotar o vilão final, **Lord Ransomware**, e libertar todos os dados sequestrados do mundo.

> 🎮 **[Jogar agora](https://SEU_USUARIO.github.io/cyberjump/)** *(troque pelo seu link do GitHub Pages)*

![badge](https://img.shields.io/badge/vanilla-JS-yellow) ![badge](https://img.shields.io/badge/canvas-API-blue) ![badge](https://img.shields.io/badge/zero-deps-green)

---

## ✨ Diferencial

Em vez de só pular nos inimigos, ao encostar em qualquer um deles abre um **quiz real de segurança da informação** com 10 segundos pra responder. Acertou? O inimigo é neutralizado. Errou? Perde uma vida. **30 perguntas reais** cobrindo OWASP Top 10, CIA Triad, vulnerabilidades famosas (Heartbleed, Log4Shell, EternalBlue), tipos de ataque (phishing, SQL injection, XSS, MITM, brute force) e ferramentas (firewall, IDS/IPS, VPN, SIEM).

---

## 🎯 Como jogar

### Desktop
| Tecla | Ação |
|-------|------|
| `← →` ou `A D` | Mover |
| `Espaço` / `W` / `↑` | Pular (duplo com Auth Token) |
| `X` | Atirar firewall shield |
| `C` | Decryption Beam (boss fight, com 3 chaves) |
| `1` – `4` | Atalho pras alternativas do quiz |
| `Enter` | Confirmar |
| `M` | Mudo |

### Mobile
Controles touch responsivos aparecem automaticamente — D-pad na esquerda, JUMP/FIRE/DECRYPT na direita. Toque nas opções do menu e nas alternativas do quiz diretamente.

---

## 🗺️ Conteúdo

- **3 fases progressivas** com paletas e estética próprias:
  1. *A Rede Local* — fundo matrix verde, plataformas de circuito
  2. *O Servidor Profundo* — racks de servidor em azul escuro
  3. *A Dark Web* — neon roxo/magenta com glitch
- **6 inimigos** com sprites pixelados e comportamentos próprios:
  - Trojan Horse (porta secreta abre soltando "soldados")
  - Phishing Phantom (envelope com anzol)
  - DDoS Bot (drone com 4 hélices)
  - Keylogger Kraken (polvo com teclas QWERTY)
  - Zero-Day Dragon (chefe voador da fase 3)
  - **Lord Ransomware** (boss final, 3 fases, mecânicas únicas)
- **Power-ups**: Auth Token (pulo duplo), Firewall Shield (absorve 1 hit), Encryption Cloak (invisível 5s), Backup Heart (+1 vida), Patches de Segurança (pontuação)
- **Boss fight** com 3 mecânicas éticas que dão poder:
  - 🟡 Resgate de arquivos reféns → **Decryption Key** (3 chaves = Decryption Beam)
  - 🔵 Ativação dupla de **Backup Terminals** → cura + dano massivo
  - 🟡 Coleta do **Patch Zero** (fase 3) → 5s de invencibilidade + tiro triplo

---

## 🎨 Polimento

- Parallax scrolling em 3 camadas por fase
- Partículas em tudo (pulo, ataque, coleta, hit, explosão)
- Screen shake nos impactos
- Trilha sonora chiptune sintetizada via **Web Audio API** (sem MP3, gerada em runtime)
- SFX sintetizados (pulo, coleta, hit, acerto, erro)
- Telas animadas: menu pulsante, intro estilo terminal hacker, "DECRYPTING NEXT LEVEL", Game Over com glitch, vitória estilo créditos rolando
- Pixel art desenhada via Canvas API (sem assets externos)
- HUD completo com HDs como vidas, barra de XP, ícones de power-ups ativos
- High score persistido no `localStorage`

---

## 🛠️ Stack

- **HTML5 + Canvas API** (pixel-art renderizado em runtime)
- **JavaScript vanilla** (zero dependências, zero build)
- **Web Audio API** (música e SFX sintetizados)
- **CSS responsivo** com `clamp()` e `matchMedia` pra controles touch

Tudo em **um único arquivo `.html`**, ~120KB, roda em qualquer navegador moderno.

---

## 🚀 Como rodar localmente

Basta abrir `index.html` num navegador — é só duplo-clique. Não precisa servidor, npm, build, nada.

---

## 📜 Licença

MIT — use, modifique e compartilhe à vontade.

---

## 👤 Créditos

Desenvolvido por **Andréa Barbosa Araújo**.
