# Spotify Clone - Sidebar e Biblioteca

Este projeto implementa uma barra lateral e uma seção de navegação da biblioteca inspiradas no layout do Spotify. O objetivo é treinar o uso de HTML, CSS e integração com ícones do FontAwesome.

## Estrutura do Código

### HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Styles/reset.css">
    <link rel="stylesheet" href="Styles/styles.css">

    <!-- Links para trazer os ícones via CDN -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/solid.css"/>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/fontawesome.css"/>
    <title>Spotify</title>
</head>

<body>
    <div class="sidebar">
        <nav class="sidebar__navigation">
            <div class="logo">
                <a href="">
                    <img src="assets-20250127T200024Z-001/assets/icons/logo-spotify.png" alt="Logo Spotify">
                </a>
            </div>
            <div>
                <ul>
                    <li>
                        <a href="">
                            <i class="fas fa-home"></i>
                            <span>Início</span>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <i class="fas fa-search"></i>
                            <span>Pesquisar</span>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>

    <div class="sidebar-2">
        <nav class="sidebar-2__navigation">
            <div class="biblioteca">
                <ul>
                    <li>
                        <a href="">
                            <i class="fas fa-book"></i>
                            <span>Sua Biblioteca</span>
                        </a>
                        <a class="plus" href="">
                            <i class="fas fa-plus"></i>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</body>
</html>

