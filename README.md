<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FIM GOOGLE FONTES -->
    <!-- BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <!-- FIM BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="style.css">

    <script src="menu.js" defer></script>

    <title>Olympus Suplementos</title>
</head>

<body>

    <header>
        <div class="interface">
            <div class="logo">
                <a href="index.html">
                    <img src="images/logo.png" alt="Logo da Olympus Suplementos">
                </a>
            </div><!--logo-->

            <nav class="menu-desktop">
                <ul>
                    <li><a href="index.html">Início</a></li>
                    <li><a href="especialidades.html">Especialidades</a></li>
                    <li><a href="sobre.html">Sobre</a></li>
                    <li><a href="projetos.html">Projetos</a></li>
                </ul>
            </nav>

            <div class="btn-contato">
                <a href="contato.html">
                    <button>Contato</button>
                </a>
            </div><!--btn-contato-->

            <div class="btn-abrir-menu" id="btn-menu">
                <i class="bi bi-list"></i>
            </div>

            <div class="menu-mobile" id="menu-mobile">
                <div class="btn-fechar">
                    <i class="bi bi-x-lg"></i>
                </div>

                <nav>
                    <ul>
                        <li><a href="index.html">Início</a></li>
                        <li><a href="especialidades.html">Especialidades</a></li>
                        <li><a href="sobre.html">Sobre</a></li>
                        <li><a href="projetos.html">Projetos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>

            </div><!--menu-mobile-->
            <div class="overlay-menu" id="overlay-menu"></div>
        </div><!--interface-->
    </header>

    <main>
        <!-- Formulário de Login -->
        <section class="container-login">
            <div class="interface">
                <h2>Login</h2>
                <form>
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>

                    <label for="password">Senha</label>
                    <input type="password" id="password" name="password" required>

                    <button type="submit">Entrar</button>
                </form>
            </div>
        </section>
        <!-- Fim Formulário de Login -->

        <section class="container-sobre">
            <div class="interface">
                <div class="flex">
                    <div class="logo-sobre">
                        <img src="images/logo.png" alt="Logo da Olympus Suplementos">
                    </div>
                    <div class="explicacao-sobre">
                        <h2>Sobre a Olympus Suplementos</h2>
                        <p>A Olympus Suplementos é uma empresa dedicada a fornecer os melhores produtos para o seu bem-estar e saúde. Nosso compromisso é oferecer qualidade e eficiência em cada suplemento que comercializamos.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="container-especialidades">
            <div class="interface">
                <h2>Nossas Especialidades</h2>
                <div class="flex">
                    <div class="especialidade">
                        <a href="produto1.html">
                            <i class="bi bi-heart-fill"></i>
                            <h3>Produtos de Qualidade</h3>
                            <p>Nossos produtos são cuidadosamente selecionados para garantir a melhor qualidade e eficácia para nossos clientes.</p>
                        </a>
                    </div>
                    <div class="especialidade">
                        <a href="produto2.html">
                            <i class="bi bi-shop"></i>
                            <h3>Loja Online</h3>
                            <p>Facilidade e comodidade na compra dos nossos produtos através da nossa loja online.</p>
                        </a>
                    </div>
                    <div class="especialidade">
                        <a href="produto3.html">
                            <i class="bi bi-journal-richtext"></i>
                            <h3>Blog e Redes Sociais</h3>
                            <p>Fique por dentro de novidades, dicas de saúde e promoções através do nosso blog e redes sociais.</p>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <section class="container-contato">
            <div class="interface">
                <h2>Entre em Contato</h2>
                <ul>
                    <li><i class="bi bi-telephone"></i> (11) 1234-5678</li>
                    <li><i class="bi bi-geo-alt"></i> Av. Principal, 1234 - São Paulo/SP</li>
                    <li><i class="bi bi-envelope"></i> <a href="mailto:contato@olympussuplementos.com">contato@olympussuplementos.com</a></li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="interface">
            <div class="line-footer">
                <div class="flex">
                    <div class="logo-footer">
                        <img src="images/logo.png" alt="Logo da Olympus Suplementos">
                    </div><!--logo-footer-->
                    <div class="btn-social">
                        <a href="#"><button><i class="bi bi-instagram"></i></button></a>
                        <a href="#"><button><i class="bi bi-youtube"></i></button></a>
                        <a href="#"><button><i class="bi bi-linkedin"></i></button></a>
                    </div><!--btn-social-->
                </div>
            </div><!--line-footer-->

            <div class="line-footer borda">
                <p><i class="bi bi-envelope-fill"></i> <a href="mailto:contato@olympussuplementos.com">contato@olympussuplementos.com</a></p>
            </div><!--line-footer-->
        </div><!--interface-->
    </footer>

    <!-- SCRIPTS -->
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="menu.js"></script>
</body>

</html>
