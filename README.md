
@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:wght@400;600&display=swap');

:root {
    --cor-primaria: #000000;
    --cor-secundaria: #F6F6F6;
    --cor-terciaria: #22D4FD;
    --cor-vovetor:#272727;
    --fonte-primaria: 'Krona One', sans-serif;
    --font-secundaria: 'Montserrat', sans-serif;
}

* {
    margin: 0;
    padding: 0;
}




body {
    box-sizing: border-box;
    background-color: var(--cor-primaria);
    color: var(--cor-secundaria);
}
.cabecalho{
    padding: 2% 0% 0% 15%;
}
.cabecalho_men {
    display: flex;
    gap: 80px;
}
.cabecalho_men_link{
    font-family: var(--font-secundaria);
    font-size: 1.5rem;
    font-weight: 600;
    color: var(--cor-terciaria);
    text-decoration: none;
}
.titulo-destaque {
    color: var(--cor-terciaria);
}
.apresentacao {
    padding: 5% 15%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 82px;
}
.apresentacao_cont {
    width: 50%;
    display: flex;
    flex-direction: column;
    gap: 40px;
}
.apresentacao_cont_titulo {
    font-size: 2.25rem;
    font-family: var(--fonte-primaria);
}
.apresentacao_cont_texto {
    font-size: 1.5rem;
    font-family: var(--font-secundaria);
}
.apresentacao_cont_sub{
    font-family: var(--fonte-primaria);
    font-weight: 400;
    font-size: 1.5rem;
}
.apresentacao_link {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 32px;

}
.apresentacao_link_link {
    justify-content: center;
    gap: 16px;
    display: flex;
    border: 2px solid var(--cor-terciaria);
    width: 50%;
    text-align: center;
    border-radius: 8px;
    font-size: 1.5rem;
    font-weight: 600;
    padding: 21.5px 0;
    text-decoration: none;
    color: var(--cor-secundaria);
    font-family: var(--font-secundaria);
}
.apresentacao_link_link:hover {
    background-color: var(--cor-vovetor);
}

.apresentacao_imag{
    width: 50%;

}



.rodape {
    padding: 24px;
    color: var(--cor-primaria);
    background-color: var(--cor-terciaria);
    text-align: center;
    font-family: var(--font-secundaria);
    font-size: 1.5rem;
    font-weight: 400;

}
@media (max-width: 1200px) {
    .cabecalho {
        padding: 6%;
    }
    .cabecalho_men {
        justify-content: center;
    }
    .apresentacao {
        flex-direction: column-reverse;
        padding: 5%;
    }
    .apresentacao_cont {
        width: auto;
    }
}
