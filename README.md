# i3wm Config — Custom Setup

Configuração personalizada do i3wm focada em produtividade, minimalismo e estética com transparência.

---

## Base do Ambiente

* Window Manager: i3
* Terminal: kitty
* Launcher: rofi
* Compositor: picom
* Status Bar: i3status
* Lockscreen: i3lock + script custom
* Gerenciador de Wallpaper: nitrogen

---

## Keybindings Principais

### Geral

* `Mod + Enter` → abrir terminal (kitty)
* `Mod + d` → abrir launcher (rofi)
* `Mod + q` → fechar janela
* `Mod + f` → fullscreen
* `Mod + Shift + space` → alternar floating

### Navegação

* `Mod + j/k/l/ç` → mover foco
* `Mod + Shift + j/k/l/ç` → mover janela

### Workspaces

* `Mod + [1-0]` → trocar workspace
* `Mod + Shift + [1-0]` → mover janela

### Extras

* `Mod + x` → lockscreen
* `Mod + o` → abrir Obsidian
* `Mod + Shift + x` → abrir Firefox
* `Mod + p` → Flameshot
* `Mod + Shift + y` → desligar

---

## Layout e Aparência

* Bordas ativadas (`default_border normal`)
* Gaps internos e externos: `3px`
* Transparência via picom
* Barra custom com fonte `ChicagoFLF`

### Cores

* Fundo escuro com transparência
* Workspaces destacados com contraste claro
* Bordas:

  * Foco: cinza claro
  * Inativo: cinza médio
  * Urgente: vermelho

---

## Mouse e Touchpad

* Focus segue o mouse (`focus_follows_mouse yes`)
* Scroll natural ativado
* Tap-to-click ativado

---

## Autostart

* dex (apps XDG)
* nm-applet (rede)
* picom (compositor)
* nitrogen (wallpaper)
* numlockx
* configurações de input (xinput)

---

## Regras Inteligentes

Aplicações automaticamente organizadas:

* Firefox → Workspace 1
* Krita → Workspace 2
* VS Code → Workspace 3
* Steam → Workspace 4
* Obsidian → Workspace 6

---

## Customizações Diferentes

* Título das janelas sobrescrito:

  ```
  
## Observações

* Algumas configs usam IDs fixos de dispositivos (xinput), pode quebrar em outro sistema
* Caminhos absolutos (`/home/jc/...`) precisam ser ajustados
* Duas execuções do picom (redundante, pode remover uma)

---


## Filosofia do Setup

Simples, rápido, meio caótico, mas funcional.
Feito pra quem prefere controle total ao invés de conforto automático.
