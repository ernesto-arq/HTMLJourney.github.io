SRC (source, ou fonte) é frequentemente utilizado para ccriação de tags em HTML e para especificar o caminho de recursos externos que devem ser carregados exibindo a página:

1. Imagens (incluindo em http ou https), é o caminho relativo do diretório onde o arquivo HTML localiza as imagens por exemplo <img src ="images/logo.png" alt="Logo da Empresa">

2. É utizado para o caminho de JavaScript externos, que permite que scripts maiores sejam mantidos e separados, facilitando a manutenção eo carregamento de páginas, por exemplo <script src="js/app.js"></script>

3. Para vídeos, o src também pode ser utilizado para carregar ou reter um video especifico. Por exemplo: <video controls>
    <source src="videos/movie.mp4" type="video/mp4">
    Seu navegador não suporta vídeos.
</video>

4. Em iframes é utilizado para especificar a página da web que deve ser embutida dentro do iframe.  <iframe src="https://www.example.com"></iframe>


5. Áudio, pode conter elementos de áudio para ser tocado, como por exemplo:

<audio controls>
    <source src="audio/song.mp3" type="audio/mpeg">
    Seu navegador não suporta elemento de áudio.
</audio>

6. Utilizado para elementos de vídeo e áudio onde se especificam as legendas.
<video controls>
    <source src="movie.mp4" type="video/mp4">
    <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
</video>

7. Utilizado para incorporar dados como Flash, PDF's, ou outros tipos de mídera definindo o recurso que será carregado.
<object data="files/document.pdf" type="application/pdf">
    <a href="files/document.pdf">Download PDF</a>
</object>