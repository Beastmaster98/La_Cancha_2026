# La_Cancha_2026 - accesos
RUTA DENTRO DE UBUNTU/LUNIS WSL
cd /home/aportal/Proyecto-La-Cancha-2026/la-cancha-node

\\wsl.localhost\Ubuntu\home\aportal --> otra ruta pero no la utilizo tanto
pwd --> ver donde estamos ubicados en la terminal

Para entrar a base de datos sqlite3
aportal@MarceloPR:/mnt/c/Users/porta/OneDrive/BDLaCancha2026

mañana revisar BD fue copiado al escritorio




nvim ----- Macbook
ruta:
nvim ~/.config/nvim/lua/plugins/colors.lua

colorscheme macbook
return {
  {
    "rebelot/kanagawa.nvim",
    lazy = false,
    priority = 1000,
    opts = {
      compile = true,             -- Lo hace ultra rápido
      undercurl = true,           -- Subrayados elegantes para errores
      commentStyle = { italic = true },
      keywordStyle = { italic = true },
      statementStyle = { bold = true },
      theme = "wave",             -- Opciones: "wave" (oscuro pro), "dragon" (más oscuro), o "lotus" (claro)
    },
  },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "kanagawa",
    },
  },
}
