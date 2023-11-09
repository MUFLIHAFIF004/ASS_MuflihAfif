## Website Profile
saya membuat website ini untuk mengenalkan profil chanel youtube saya dengan berbentuk web.
untuk sistem matis yang saya gunakan ada beberpa hal:

## NavBar
``` js
<body class="bg-no-repeat bg-center bg-cover min-h-screen" style="background-image: url('image/background.jpg');">
    <header>
        <nav class="relative p-3 mx-auto bg-gray-950 bg-opacity-80 shadow-2xl shadow-blue-300">
            <div class="relative max-w-screen-xl flex flex-wrap items-center justify-between mx-auto">       
                <h1 class="text-white text-3xl font-bold"><span class="text-blue-500">ZAKA</span>RUNA</h1>

                <ul class="flex items-center gap-5">
                    <li class="list-none inline-block px-5 text-[20px] font-bold ">
                        <a href="index.html" class="text-blue-500 md:text-blue-500 hover:text-blue-300">Beranda</a>
                    </li>

                    <li class="list-none inline-block px-5 text-[20px] font-bold ">
                        <a href="Topik.html" class="text-white px-2 hover:text-blue-900">Topik</a>
                    </li>

                    <li class="list-none inline-block px-5 text-[20px] font-bold ">
                        <a href="profil.html" class="text-white px-2 hover:text-blue-900">Profil</a>
                    </li>

                    <li class="list-none inline-block px-5 text-[20px] font-bold ">
                        <a href="https://www.instagram.com/apip_zakaruna/" class="text-white px-2 hover:text-blue-900">Kontak</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
```
Navar ini menggunakan Tailwind CSS
## Hasil
![Screenshot 2023-11-09 111008](https://github.com/MUFLIHAFIF004/ASS_MuflihAfif/assets/147011338/4e815827-0268-4d0f-bb2c-869c1ee9b3e3)

## Konten 1
``` js
<div>
        <div class=" max-w-screen-xl bg-blue-300 bg-opacity-80 mx-auto flex text-white mt-20 ml-10 
        rounded-full border-4 border-gray-500">

        <img src="image/logo_zakaruna.png" alt="" class="h-72 w-80 ">

    <div class="mt-10 ml-4">
    <h1 class="text-5xl font-semibold font-mono text-center">Selamat Datang!!</h1>
    <br>
    <p class="font-semibold mt-2 text-center text-lg"> 
        website ini menjelaskan tentang bagaimana channel zakaruna berkembang,
        <br>dalam website ini juga menjelaskan tips agar menarik perhatian
        penonton 
        <br>atau audienc, dan melihat perkembangan channel ini, serta membritahu
        topik 
        <br>channel yang sudah dibuat di dalam YouTube.
    
    </p>
</div>
<img src="image/zakaruna.png" alt="textnya zakaruna" class=" h-40 mt-16 ml-6">
</div>
```
Konten 1 ini menggunakan Tailwind CSS
## Hasil
![Screenshot 2023-11-09 111208](https://github.com/MUFLIHAFIF004/ASS_MuflihAfif/assets/147011338/3639475a-db05-4895-8ce6-e7ff0755ca72)

## Konten 2
``` js
<div>
    <div class="mx-auto flex mt-20 py-36">
        <img id="gambar" src="image/zakaruna_icon2.png" alt="" class="ml-16 h-72 w-70">
        <div id="teks-container" class=" border-2 mr-52 bg-opacity-70 bg-gray-600 px-1 rounded">
            <p id="teks" class=" mt-14 text-white text-center font-bold text-3xl">
                ZAKARUNA nama yang diambil, dari ide saya.Ide ini muncul pada saat memikirkan, bagaimana orang tertarik dengan nama channel kita.
            </p>
            <div class="flex justify-center">
                <button onclick="gantiElemen()" class="flex text-white">>>>>></button>
            </div>
        </div>
    </div>
    
    <script>
    let gambarIndex = 1; // Indeks gambar saat ini
    const gambarArray = ["image/zakaruna_icon2.png", "image/zakaruna_icon1.png"]; // Daftar gambar yang akan diubah
    let teksIndex = 1; // Indeks teks saat ini
    const teksArray = [('ZAKARUNA nama yang diambil, dari ide saya.Ide ini muncul pada saat memikirkan, bagaimana orang tertarik dengan nama channel kita.'), 
                        "Kesimpulannya Nama channel itu penting bagi kita sebagai pemula untuk dikenal pada khalayak. dan plagiat"]; // Daftar teks yang akan diubah
    
    function gantiElemen() {
        // Ganti gambar
        gambarIndex = (gambarIndex + 1) % gambarArray.length;
        const gambar = document.getElementById("gambar");
        gambar.src = gambarArray[gambarIndex];
    
        // Ganti teks
        teksIndex = (teksIndex + 1) % teksArray.length;
        const teks = document.getElementById("teks");
        teks.textContent = teksArray[teksIndex];
        console.log (gambarIndex)
    }
    </script>
```
Dalam pengerjaan konten 2 ini menggunakan Tailwind CSS Dana JavaScript
## Hasil
![Screenshot 2023-11-09 111321](https://github.com/MUFLIHAFIF004/ASS_MuflihAfif/assets/147011338/45874624-ae84-4ed2-9e2d-603ce945288f)
![Screenshot 2023-11-09 111307](https://github.com/MUFLIHAFIF004/ASS_MuflihAfif/assets/147011338/2c1f4ea4-f200-4c48-904a-7bac1ca99681)

## Footer
``` js
    <footer class="bg-gray-100">
        <p class="text-center font-semibold">@Copyright2023 Hak Cipta Dilindungi</p>
    </footer>
```
Dalam pengerjaan footer ini hanay menggunakn TailWind CSS
## Hasil
![Screenshot 2023-11-09 111556](https://github.com/MUFLIHAFIF004/ASS_MuflihAfif/assets/147011338/1237a342-4938-40ba-a935-e6cc37077a6e)
