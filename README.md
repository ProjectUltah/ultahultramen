html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;500;700&display=swap" rel="stylesheet" />
        <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
        <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
        <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Sharp" rel="stylesheet" />
        <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.4.4/dist/sweetalert2.all.min.js"></script>

    </head>
    <body>
        <p data-aos="zoom-in">Pencet love nya dehh
            <i onclick="tanya()" class="material-icons-sharp"> favorite </i></p>
      
    </body>
    <script> AOS.init({ once: true, }); </script> <script> if(musik == "") { musik = "https://dekatutorial.github.io/Gellen%20Martadinata%20-%20Selamat%20Ulang%20Tahun.mp3"} var audio = new Audio(musik); audio.loop = true; audio.autoplay = true; function mulai() { audio.play(); document.querySelector(".open").style = "opacity: 0;"; document.querySelector(".body").style = "overflow-y: scroll;"; setTimeout(function () { document.querySelector(".open").style.display = "none"; }, 1000); } function wa(isi) { window.open("Ultah1.html"); } async function tanya() { var { value: kado } = await swal.fire({ title: "siapa orang spesial mu?", input: "text", showCancelButton: false, }); if (kado) { await swal.fire("ada hadiah lagi nihh pencet ok ya sayangg"); wa(kado); } else { await swal.fire("masa kosong, berati nda aku dong di hatimu"); tanya(); } } </script> 
</html>
