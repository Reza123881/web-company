<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kedai Kopi Warcup - Selamat Datang</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Kedai Kopi Warcup</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="tentang.html">Tentang Kami</a></li>
                <li><a href="alamat.html">Alamat</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            
            <button type="submit">Login</button>
        </form>
         <img src="warcup.jpg"alt="Warcup.">
    </main>

    <main>
        <section id="welcome">
            <h2>Selamat Datang di Kedai Kopi Warcup</h2>
        </section>
        <section id="menu">
            <h2>Menu Kami</h2>
            <p>Temukan berbagai macam kopi dan makanan ringan yang kami tawarkan.</p>
            <!-- Tambahkan daftar menu di sini -->
        </section>
         <img src="mennu.jpg"alt="menu">
    </main>
/* Mengatur gaya umum untuk halaman */
body {
    font-family: 'Poppins', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #ece4d0; /* Warna latar belakang lembut */
    color: #3d3d3d; /* Warna teks yang sedikit lebih gelap untuk kontras */
}

/* Gaya untuk header dan navigasi */
header {
    background: url('header-bg.jpg') no-repeat center center/cover; /* Gambar latar header */
    color: #6b6b6b; /* Warna putih lembut untuk teks header */
    padding: 40px 20px;
    text-align: center;
}


header h1 {
    font-size: 3em;
    margin: 0;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);
    animation: fadeIn 1.5s ease-in-out;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

nav ul li a {
    color: #000000;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 15px;
    border: 2px solid transparent;
    border-radius: 5px;
    transition: all 0.3s;
}

nav ul li a:hover {
    background-color: rgba(255, 255, 255, 0.15); /* Efek hover dengan warna transparan */
    border: 2px solid #f4f4f4;
    transform: scale(1.1);
}

/* Gaya untuk konten utama */
main {
    padding: 20px;
    max-width: 1000px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
}

/* Gaya untuk label dan elemen dengan tema coklat susu */
.label {
    background-color: #d7b899; /* Warna coklat susu */
    color: #3d3d3d; /* Warna teks yang kontras */
    padding: 10px 20px;
    border-radius: 8px;
    display: inline-block;
    font-weight: bold;
    font-size: 1.2em;
    text-align: center;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
    transition: transform 0.3s, background-color 0.3s;
}

.label:hover {
    background-color: #c5a77c; /* Warna sedikit lebih gelap saat hover */
    transform: scale(1.05);
}

/* Gaya untuk header judul Kedai Kopi */
header h1 {
    background-color: #d7b899; /* Warna coklat susu */
    padding: 10px;
    border-radius: 8px;
    display: inline-block;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
}

/* Gaya untuk navigasi */
nav ul li a {
    background-color: #d7b899; /* Warna coklat susu */
    color: #3d3d3d; /* Warna teks yang gelap untuk kontras */
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
    text-decoration: none;
    transition: background-color 0.3s, transform 0.3s;
}

nav ul li a:hover {
    background-color: #fff; /* Warna sedikit lebih gelap saat hover */
    transform: scale(1.1);
}

/* Gaya untuk section konten seperti Beranda, Tentang Kami, Alamat */
section {
    background-color: #f3e5d0; /* Warna coklat susu terang */
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

/* Gaya untuk tombol di form login */
form button {
    background-color: #d7b899; /* Warna coklat susu */
    color: #3d3d3d;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s, transform 0.2s;
}

form button:hover {
    background-color: #c5a77c; /* Warna sedikit lebih gelap saat hover */
    transform: scale(1.05);
}


/* Gaya untuk form login */
form {
    background-color: #ffffff; /* Warna latar form yang netral */
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
    animation: slideIn 1s ease-out;
}

form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #5a3a2b; /* Warna cokelat lembut untuk teks label */
}

form input {
    width: calc(100% - 20px);
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
    box-shadow: inset 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: border-color 0.3s;
}

form input:focus {
    border-color: #5a3a2b; /* Fokus border pada input */
}

form button {
    background-color: #5a3a2b; /* Warna coklat yang lebih kalem */
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s, transform 0.2s;
}

form button:hover {
    background-color: #4b2e1d; /* Warna sedikit lebih gelap saat hover */
    transform: scale(1.05);
}

/* Gaya untuk bagian sambutan dan menu */
section#menu, section#welcome {
    margin-bottom: 30px;
    background-color: #ffffff; /* Latar belakang putih yang lembut */
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
    animation: fadeInUp 1s ease-in-out;
}

#welcome {
    display: flex;
    align-items: center;
    background-image: url(".jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
    
}

#menu {
    background: url("") no-repeat center center/cover;
    color: #5a3a2b; /* Teks berwarna  */
    padding: 40px;
    border: none;
    text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.4);
}

h2 {
    color: #5a5a5a; /* Warna cokelat lembut untuk judul */
    margin-bottom: 10px;
    font-size: 2em;
    text-align: center;
}

p {
    line-height: 1.6;
    font-size: 1.1em;
    color: #5a3a2b; /* Warna teks yang netral dan nyaman di mata */
}


/* Animasi */
@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

@keyframes slideIn {
    from {
        transform: translateX(-100%);
        opacity: 0;
    }
    to {
        transform: translateX(0);
        opacity: 1;
    }
}

@keyframes fadeInUp {
    from {
        transform: translateY(20px);
        opacity: 0;
    }
    to {
        transform: translateY(0);
        opacity: 1;
    }
}

    
</body>
</html>
