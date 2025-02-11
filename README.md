# **Primeiro projeto: Agencia de Viagens**
![image](https://github.com/user-attachments/assets/b308985b-0d9c-4537-ad97-b28ff822e2c6)

Protótipo de alta fidelidade feito no figma <br>
https://www.figma.com/design/1iT0qyhGe5864ny1dce9FZ/Untitled?node-id=0-1&p=f&t=FlE08bpGNdniVNTt-0

```HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Agencia de Viagens</title>
</head>
<body>
    <!-- Tag semantica para cabeçalho -->
    <header>
        <h1 id="inicio">Agencia de Viagens</h1>
        <nav>
            <a href="#Inicio">Inicio</a>
            <a href="#Destinos">Destinos</a>
            <a href="#Pacote">Pacote</a>
            <a href="#Contato">Contato</a>
        </nav>
    </header>
    
    
    <div class="container">
<!-- Tag semantica para Lareral -->
 <!-- Destinos Populares -->
        <aside class="sidebar">
            <h2 class="destinos">Destinos populares</h2>
            <ul>
                <l1><img src="img/paris.jpg" alt="Paris">Paris, FR</l1>
                <l1><img src="img/ny.jpg" alt="Ny">Ney York, US</l1>
                <l1><img src="img/riojaneiro.jpg" alt="riodejaneiro">Rio de Janeiro</l1>
                <l1><img src="img/roma.jpg" alt="roma">Roma, IT</l1>
                <l1><img src="img/tokio.jpg" alt="Tokio">Tokio, JP</l1>
            </ul>
        </aside>

 <!--  Tag semantica para outras sessões  -->
        <section class="main-content">
            <h2 class="subtittle">Encontre o seu Destino</h2>
            <form action="">
                <input type="text" placeholder="Digite seu destino" required>
                <input type="date" required>
                <button type="submit">Procurar</button>
            </form>
        </section>

        <aside class="secondary-content">
            <h2 id="pacotes">Pacotes em Promoções</h2>
            <ul>
                <li><img src="img/cancun.jpg" alt="Cancun"><b>Praias Paradisiacas!</b>
                <br>Pacote para Cancun - 5 dias por 3x R$2.500
                </li>
                <li><img src="img/londres.jpg" alt="Londre"><b>Intercambio britâmico</b>
                <br>Pacote para Londres - 7 dias por 2x de R$4.000
                </li>
                <li><img src="img/noronha.jpg" alt="Fernando de Noronha"><b>Super Oportunidade!</b>
                <br>Pacote para Fernando de Noronha - 4 dias por R$3.200</li>
            </ul>
        </aside>
<!--  -->
    </div>
    <footer>
        <p id="contatos">&copy; 2025 Agencia de Viagens - contato: contato@agenciaviagens.com"></p>
    </footer>
</body>
</html>
```

```CSS
@import url('https://fonts.googleapis.com/css2?family=Poiret+One&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
/* Reset das configurações */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poiret One", serif;
    list-style: none;
}

body { 
    display: flex; 
    flex-direction: column; 
    min-height: 100vh; 
} 
    
header { 
    background: #007766; 
    color: white; 
    padding: 15px; 
    text-align: center; 
} 
    
h1{ 
    font-family: "Dancing Script", serif; 
    font-size: 2.5rem; 
} 
    
nav { 
    display: flex; 
    justify-content: center; 
    gap: 20px; 
    margin-top: 10px; 
} 
    
    
nav a { 
    color: white; 
    text-decoration: none; 
    font-weight: bold; 
} 

.container { 
    display: flex; 
    flex: 1; 
    padding: 20px; 
    gap: 20px; 
    flex-wrap: wrap; 
    background: url(img/london.jpg) no-repeat center fixed; 
    background-size: cover; 
} 
        
.sidebar { 
    flex: 1; 
    min-width: 200px; 
    background:#f1f1f1; 
    padding: 15px; 
    border-radius: 8px; 
} 
        
.main-content { 
    flex: 2; 
    min-width: 300px; 
    padding: 15px; 
} 
        
.subtittle{ 
    color: #f1f1f1; 
    font-size: 2.5rem; 
} 
        
.secondary-content { 
    flex: 1; 
    min-width: 200px; 
    background: #f9f9f9; 
    padding: 15px; 
    border-radius: 8px; 
} 


li{ 
    padding: 9px; 
}

        
footer { 
    background: #007766; 
    olor: white; 
    text-align: center; 
    padding: 10px; 
    margin-top: auto; 
} 
            
form { 
    display: flex; 
    flex-direction: column; 
    gap: 10px; 
} 
    
input, button { 
    padding: 10px; 
    border: 1px solid #ccc; 
    border-radius: 5px; 
} 

button { 
    background: #007766; 
    color: white; 
    cursor: pointer; 
    font-weight: bold; 
    font-size: 1rem; 
} 
            
button:hover { 
        background: #005f8a; 
} 

img { 
    width: 100%; 
    border-radius: 5px; 
} 

 @media (max-width: 768px) { 
.container { 
    flex-direction: column; 
    }
}
```

# **Segundo projeto: Evento de Arrancada**
![image](https://github.com/user-attachments/assets/5c629ff5-17f2-4408-bba7-af33e3529383)
![image](https://github.com/user-attachments/assets/a0701a65-f23a-4c80-a952-504b7e461771)
![image](https://github.com/user-attachments/assets/eab954de-12f3-46a9-b9c4-ac7dcf234d99)
![image](https://github.com/user-attachments/assets/bea42037-1b98-4240-9a15-6c79e0096cb9)
![image](https://github.com/user-attachments/assets/32e4e57f-002e-4257-b6b9-b720d4537858)

Protótipo de alta fidelidade feito no figma <br>
https://www.figma.com/design/k8Rfq7ni07iPnXDrljkIcr/Untitled?node-id=0-1&p=f&t=G6SMKtNVHndVlTCQ-0

Codigo: <br>
HTML
```HTML
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MegaRacing</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="shortcut icon" href="img/icon.png" type="image/x-icon">
</head>

<body>

    <!-- HEADER -->
    <header id="event-subscription">
        <div id="disclaimer">
            <h2>MegaRacing</h2>
            <p class="about-event">Um evento para acelerar seu coração</p>
            <p>Data do evento:</p>
            <p class="event-date">Domingo, 12 de Setembro, a partir das 10h</p>
        </div>
        <div id="subscription-form">
            <p>Preencha o formulário para receber os detalhes do evento</p>
            <form>
                <div class="form-group">
                    <label for="name">Nome</label>
                    <input type="text" id="name" placeholder="Digite seu nome" />
                </div>
                <div class="form-group">
                    <label for="email">E-mail</label>
                    <input type="email" id="email" placeholder="Digite seu melhor e-mail" />
                </div>
                <div class="form-group">
                    <label for="phone">Telefone</label>
                    <input type="text" id="phone" placeholder="Número de Whatsapp" />
                </div>
                <div class="form-group">
                    <label for="interest">Principal interesse</label>
                    <select name="interest" id="interest">
                        <option value="" disabled selected>Selecione</option>
                        <option value="apartment">Novos modelos</option>
                        <option value="house">Peças</option>
                        <option value="garden">Acessórios</option>
                        <option value="other">Outro</option>
                    </select>
                </div>
                <input type="submit" class="btn" value="Quero me inscrever" />
            </form>
        </div>
    </header>

    <!-- SECTION -->
    <section id="key-benefits">
        <h2>Explore a linha de Automoveis:</h2>
        <div class="benefits">
            <div class="benefit">
                <div id="benefit-1" class="benefit-img"></div>
                <p>Os melhores Projetos!</p>
            </div>
            <div class="benefit">
                <div id="benefit-2" class="benefit-img"></div>
                <p>Os mais velozes!</p>
            </div>
            <div class="benefit">
                <div id="benefit-3" class="benefit-img"></div>
                <p>Mais INSANOS!</p>
            </div>
        </div>
    </section>

    <!-- SECTION -->
     <section id="location">
       <div class="fundo">
        <img src="img/img7.jpeg" alt="carro 7">
       </div>
    </section>

    <!-- SECTION -->
    <section id="details">
        <div class="detail" id="detail-1">
            <img src="img/img9.jpg" alt="carro 1" />
            <div class="detail-description">
                <h3>Velocidades INSANAS!</h3>
            </div>
        </div>
        <div class="detail" id="detail-2">
            <div class="detail-description">
                <h3>Varios Veiculos:</h3>
                <ul>
                    <li>Opala</li>
                    <li>Caravan</li>
                    <li>Maverick</li>
                    <li>Gol</li>
                    <li>E muito mais...</li>
                </ul>
            </div>
            <img src="img/img3.jpg" alt="Carro2" />
        </div>
        <div class="detail" id="detail-3">
            <img src="img/img8.jpg" alt="carro 3" />
            <div class="detail-description">
                <h3>Experiências</h3>
                <ul>
                    <li>Acesso aos boxes</li>
                    <li>Área dos pilotos</li>
                    <li>Arquibancada exclusiva</li>
                    <li>Exposição de carros</li>
                    <li>Muita adrenalina</li>
                    <li>E muito mais...</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- SECTION -->
    <section id="cta">
        <h3>Gostou? Então se inscreva:</h3>
        <button class="btn">Solicitar Inscrição</button>
    </section>

    <!-- FOOTER -->
    <footer id="footer">
        <h3>MegaRacing</h3>
        <p>Evento de Prova de Arrancada</p>
        <p><span>Entre em contato:</span> contact@megaracing.com.br</p>
        <p><span>Ou pelo telefone:</span> (19)99990-9999</p>
    </footer>

</body>

</html>
```
CSS
```CSS
/* Font importada do Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

/* Variáveis */
:root {
    --primary: #CC0F0F;
    --secondary: #000000;
    --fundo: #F2F2F2;
    --text-color: #fff;
    --text-secondary: #000;
    --text-tertiary: #5d5d5d;
}

/* ** Resets gerais ** */
* {
    font-family: "Montserrat", serif;
    margin: 0;
    padding: 0;
}

/* *** Event form *** */
#event-subscription {
    background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
        url("img/img1.png");
    background-position: center;
    background-size: cover;
    height: 85vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: var(--text-color);
}

#disclaimer h2,
#disclaimer .event-date {
    color: var(--primary);
}

#disclaimer h2 {
    font-size: 3em;
    margin-bottom: 1em;
}

#disclaimer .about-event {
    font-size: 2em;
    text-transform: uppercase;
    max-width: 350px;
    font-weight: bold;
    margin-bottom: 1em;
}

#disclaimer p {
    font-size: 1.2em;
    margin-bottom: 0.3em;
}

#disclaimer .event-date {
    font-weight: bold;
}

#subscription-form {
    background-color: var(--fundo);
    padding: 2em;
    max-width: 22%;
}

#subscription-form p {
    font-size: 1.5em;
    color: var(--text-secondary);
    margin-bottom: 1em;
}

.form-group {
    display: flex;
    flex-direction: column;
    margin-bottom: 0.8em;
}

.form-group label {
    color: var(--text-tertiary);
    margin-bottom: 0.3em;
    font-weight: bold;
}

.form-group input,
.form-group select {
    padding: 6px 8px;
    border-radius: 5px;
    border: none;
    outline: none;
}

.btn {
    background-color: var(--primary);
    color: var(--text-color);
    text-transform: uppercase;
    width: 100%;
    padding: 12px;
    border: none;
    cursor: pointer;
    opacity: 0.8;
}

.btn:hover {
    opacity: 1;
}

/* ************ */

/* Benefits section */
#key-benefits h2 {
    background-color:#CC0F0F;
    color: #FFFFFF;
    text-align: center;
    padding: 1em;
    font-weight: 500;
}

.benefits {
    display: flex;
    justify-content: space-around;
    padding: 4em;
    width: 80%;
    margin: 0 auto;
}

.benefit {
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 20%;
    color: var(--text-tertiary);
}

.benefit .benefit-img {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background-size: cover;
    background-position: center;
    margin-bottom: 1em;
}

#benefit-1 {
    background-image: url("img/img2.jpg");
}

#benefit-2 {
    background-image: url("img/img4.jpg");
}

#benefit-3 {
    background-image: url("img/img6.jpg");
}

/* ****************** */

/* Event location */
#location .fundo img{
    height: 700px;
    width: 100%;
    
}



/* **************** */

/* Event details container */
#details {
    width: 80%;
    margin: 0 auto;
}

.detail {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 5%;
    margin-bottom: 4em;
}

.detail img {
    width: 50%;
}

.detail h3 {
    margin-bottom: 1em;
    font-size: 2em;
    font-weight: 500;
}

#detail-1 h3 {
    font-size: 3em;
    font-weight: 700;
}

.detail-description {
    width: 100%;
    padding-left: 2em;
}

#detail-3 .detail-description {
    justify-self: flex-start;
}

.detail-description ul {
    list-style-position: inside;
}

.detail-description ul li {
    margin-bottom: 0.4em;
}

.detail-description ul li:last-child {
    font-weight: bold;
}

/* **************** */

/* Call to Action Section */
#cta {
    height: 300px;
    background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
        url("img/img5.png");
    background-position: center;
    background-size: cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    color: var(--text-color);
}

#cta h3 {
    margin-bottom: 1.2em;
    font-size: 2.5em;
    font-weight: 500;
}

#cta .btn {
    width: 30%;
    margin: 0 auto;
    font-weight: 600;
    font-size: 1.2em;
}

/* **************** */

/* Footer */
#footer {
    text-align: center;
    color: var(--secondary);
    height: 250px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

#footer h3 {
    font-size: 1.8em;
    margin-bottom: 0.5em;
}

#footer p:nth-child(2) {
    margin-bottom: 1em;
    font-size: 1.2em;
}

#footer span {
    font-weight: bold;
}

/* **************** */
/* Mobile */
@media (max-width: 450px) {

    /* Event form */
    #event-subscription {
        flex-direction: column;
        height: auto;
    }

    #disclaimer {
        padding: 2em;
    }

    #disclaimer h2 {
        margin-bottom: 0.5em;
    }

    #subscription-form {
        max-width: 70%;
        margin-bottom: 2em;
    }

    /* Benefits section */
    .benefits {
        flex-direction: column;
        align-items: center;
        width: auto;
        padding: 2em;
    }

    .benefit {
        max-width: 100%;
        margin-bottom: 2em;
    }

    /* Event location */
    #location {
        flex-direction: column;
        height: auto;
        text-align: center;
        padding: 2em 0;
    }

    #address {
        order: 2;
        flex-direction: column;
        max-width: 100%;
    }

    #address i {
        margin: 0.3em 0;
    }

    #about-location {
        order: 1;
        max-width: 100%;
    }

    #about-location h3 {
        margin-bottom: 0;
    }

    #about-location p {
        display: none;
    }

    /* Event details container */
    .detail {
        flex-direction: column;
        margin-bottom: 0.5em;
        gap: 0;
    }

    .detail img {
        width: 100%;
        margin: 2em 0;
    }

    #detail-1 img {
        display: none;
    }

    .detail-description {
        padding: 0;
    }

    #detail-3 img {
        order: 2;
    }

    #detail-3 .detail-description {
        order: 1;
    }

    /* Call to Action Section */
    #cta .btn {
        width: 80%;
    }
}
```







