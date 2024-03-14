.container {
    max-width: 800px;;
    margin: 0 auto;
    padding: 20px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 10px;
    justify-items: center;
    margin-top: 20px;
}

.cocontainer{
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    
    }
    .imagem-galeria{
    
        font-display: drid;
        grid-template-columns: repeat(auto-fit, minmax (200px, 1fr));
        grid-gap: 10px;
        justify-items: center;
        margin-top: 20px;
    }
    
    
    .imagem-galeria img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s aese ;ntainer img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
}

.container figure::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    opacity: 0;
    transition: opacity 0.3 ease;
}

figcaption {
    color: white;
}

header {
    text-align: center;
    color: rgb(255, 255, 255);

}

body {
    background-color: rgb(0, 0, 0);
}

.conteiner figure:hover::after{
    opacity: 0.5;
}

.conteiner figcaption{
    position: absolute; 
    bottom: -50px;
    left: 0;
    width: 100%;
    padding: 10px;
    background: rgba(0, 0, 0, 0.5);
    color: aliceblue;
}
