# Padrão de código

## Para manter o padrão visual é só manter em containers separados em section´s os capítulos e seus páragrafos em listas com a devida clase:

</br>
<code>

    <section>
        <h2>CAPÍTULO II – Dos Cooperados</h2>
        <ul>
            <li class="conteinerArtigo">
                <h3>Art XXº<h3>

                <p>LoremIpsum<p>
            </li>
        <ul>
    </section>

</code>

<hr></hr>

## Caso Algum destes páragrafos ou sub páragrafos tenham filhos, deve-se colocar em um container os elementos do paragrafo e abrir uma nova lista com sua classe na mesma tag < li >:

</br>
<code>

    <section>
        <h2>CAPÍTULO II – Dos Cooperados</h2>
        <ul>
            <li>
                <div class="conteinerArtigo">
                    <h3>Art XXº<h3>

                    <p>LoremIpsum<p>
                </div>

                <ul  class="conteinerSubArtigo">
                    <li class="conteinerArtigo">
                        <h3>Paragrafo XX<h3>

                        <p>LoremIpsum<p>
                    </li>
                <ul>
            </li>
        <ul>
    </section>

</code>

### Este processo de filhos dentro de filhos pode se repetir, assim manterá o aspecto visual de formato júridico
