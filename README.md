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





