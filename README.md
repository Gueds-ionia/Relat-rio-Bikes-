<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BIKES</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }
        .left-column {
            width: 30%;
            background-color: #dd6e00;
            padding: 20px;
        }
        .content {
            flex: 1;
            padding: 20px;
        }
        .hidden {
            display: none;
        }
        .bike-info {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="left-column">
        <h2>SKU</h2>
        <ul>
            <li><a href="#" data-skuid="R-1602">R-1602</a></li>
            <li><a href="#" data-skuid="R-1609">R-1609</a></li>
            <li><a href="#" data-skuid="R-1608">R-1608</a></li>
            <li><a href="#" data-skuid="R-1464">R-1464</a></li>
            <li><a href="#" data-skuid="R-1594">R-1594</a></li>
            <li><a href="#" data-skuid="R-1601">R-1601</a></li>
        </ul>
    </div>
    <div class="content">
        <h1 id="titulo-relatorio">Relatório Bikes 2024</h1>
        <div id="informacoes-R-1602" class="hidden bike-info">
            <p>BICICLETA MOTORIZADA MOSKITO 80CC BIKELETE R-1602</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Tamanho do Aro: 26</p>
            <p>- Garfo com suspensão</p>
            <p>- Banco Selim</p>
            <p>- Bagageiro</p>
            <p>- Escapamento Cromado</p>
            <p>- Baú 28 Litros</p>
            <p>- Freio Dianteiro: A disco</p>
            <p>- Coroa 44 dentes</p>
            <p>- Traseiro: V-Brake</p>
            <img src="imagens/R-1602.png" alt="Imagem da Bicicleta R-1602">
        </div>
        <div id="informacoes-R-1464" class="hidden bike-info">
            <p>BICICLETA MOTORIZADA MOSKITO 80CC BIKELETE R-1464</p>
            <p>- Motor 2 Tempos com Refrigeração a Ar 3,2HP</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Potência Real: 3,2 HP - 5000 RPM</p>
            <p>- Capacidade do Tanque: 2L</p>
            <p>- Tamanho do Aro: 26</p>
            <p>- Garfo com suspensão</p>
            <p>- Raiação de 2mm</p>
            <p>- Farol de LED</p>
            <p>- Banco Selim Super Confortável</p>
            <p>- Escapamento Cromado</p>
            <p>- Freio Dianteiro: A disco</p>
            <p>- Traseiro: V-Brake</p>
            <p>- Material do Quadro: Aço Carbono</p>
            <p>- Ignição: Eletrônica(CDI/Magneto)</p>
            <p>- Velocidade Máxima Recomendada: 45km</p>
            <img src="imagens/1.jpg" alt="Imagem da Bicicleta R-1464">
        </div>
        <div id="informacoes-R-1609" class="hidden bike-info">
            <p>BICICLETA MOTORIZADA MOSKITO 80CC R-1609</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Tamanho do Aro: 26</p>
            <p>- Garfo com suspensão</p>
            <p>- Banco de Mobilete</p>
            <p>- Para-lama de Moby</p>
            <p>- Sistema de freio: Dianteiro a Disco Traseiro V-brake</p>
            <p>- Coroa 44 Dentes</p>
            <img src="imagens/R-1609.jpeg" alt="Imagem da Bicicleta R-1609">
        </div>
        <div id="informacoes-R-1608" class="hidden bike-info">
            <p>Bicicleta Motorizada c/ Motor 80cc Aro 26 Bikelete + Farol R-1608</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Tamanho do Aro: 26</p>
            <p>- Garfo rígido</p>
            <p>- Raiação de 2mm</p>
            <p>- Banco Selim Super Confortável</p>
            <p>- Coroa 44 dentes</p>
            <p>- Escapamento Cromado</p>
            <p>- Sistema de freio: V-brake</p>
            <p>- Ignição: Eletrônica(CDI/Magneto)</p>
            <img src="imagens/R-1608.jpg" alt="Imagem da Bicicleta R-1608">
        </div>
        <div id="informacoes-R-1594" class="hidden bike-info">
            <p>BICICLETA MOTORIZADA MOSKITO 80CC BIKELETE R-1594</p>
            <p>- Motor 2 Tempos com Refrigeração a Ar 3,2HP</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Potência Real: 3,2 HP - 5000 RPM</p>
            <p>- Capacidade do Tanque: 2L</p>
            <p>- Tamanho do Aro: 26</p>
            <p>- Garfo 2 Andar com suspensão</p>
            <p>- Raiação de 2mm</p>
            <p>- Banco de Mobilete</p>
            <p>- Para-lama de Moby</p>
            <p>- Escapamento Cobra</p>
            <p>- Sistema de freio: A tambor (o mesmo de mobilete)</p>
            <p>- Coroa 44 Dentes</p>
            <p>- Material do Quadro: Aço Carbono</p>
            <p>- Ignição: Eletrônica(CDI/Magneto)</p>
            <p>- Velocidade Máxima Recomendada: 45km</p>
            <img src="imagens/R-1594.jpg" alt="Imagem da Bicicleta R-1594">
        </div>
        <div id="informacoes-R-1601" class="hidden bike-info">
            <p>BICICLETA MOTORIZADA MOSKITO 80CC BIKELETE R-1601</p>
            <p>- Cilindrada: 80cc</p>
            <p>- Tamanho do Aro: 24</p>
            <p>- Garfo rígido</p>
            <p>- Banco: Selim</p>
            <p>- Coroa 44 dentes</p>
            <p>- Escapamento: Original</p>
            <p>- Sistema de freio: V-brake</p>
            <img src="imagens/R-1601.jpg" alt="Imagem da Bicicleta R-1601">
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            var links = document.querySelectorAll('.left-column a[data-skuid]');
            var tituloRelatorio = document.getElementById('titulo-relatorio');

            links.forEach(function(link) {
                link.addEventListener('click', function(event) {
                    event.preventDefault();
                    var skuId = this.getAttribute('data-skuid');
                    
                    var allInfoDivs = document.querySelectorAll('.bike-info');
                    allInfoDivs.forEach(function(div) {
                        if (div.id === 'informacoes-' + skuId) {
                            div.classList.remove('hidden');
                        } else {
                            div.classList.add('hidden');
                        }
                    });

                    // Atualiza o título do relatório com o SKU clicado
                    tituloRelatorio.textContent = 'Relatório Bikes 2024 - ' + skuId;
                });
            });
        });
    </script>
</body>
</html>
