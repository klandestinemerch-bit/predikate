<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Planing Web - Terhubung Firebase</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; padding: 40px; text-align: center; background-color: #f4f7f6; color: #333; }
        .container { max-width: 500px; margin: auto; background: white; padding: 30px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        h1 { color: #039be5; font-size: 24px; margin-bottom: 10px; }
        p { color: #666; font-size: 14px; margin-bottom: 25px; }
        button { padding: 12px 24px; font-size: 16px; font-weight: bold; cursor: pointer; background: #039be5; color: white; border: none; border-radius: 25px; transition: 0.3s; box-shadow: 0 4px 6px rgba(3, 155, 229, 0.2); }
        button:hover { background: #0288d1; transform: translateY(-2px); }
        button:disabled { background: #ccc; cursor: not-allowed; box-shadow: none; transform: none; }
        .status { margin-top: 20px; font-weight: bold; color: #2e7d32; display: none; }
    </style>
</head>
<body>

    <div class="container">
        <h1>Situs Web Statis Terhubung!</h1>
        <p>Halaman ini sudah otomatis terintegrasi dengan Firebase Firestore proyek PREDIKATE Anda.</p>
        
        <!-- Tombol Utama -->
        <button id="btnSimpan">Klik untuk Tes Koneksi Database</button>
        
        <!-- Tulisan Status Sukses -->
        <div id="teksStatus" class="status">✅ Sukses! Data berhasil masuk ke Firestore.</div>
    </div>

    <!-- SCRIPT INTEGRASI OTOMATIS -->
    <script type="module">
        import { initializeApp } from "https://gstatic.com";
        import { getFirestore, collection, addDoc } from "https://gstatic.com";

        // Konfigurasi otomatis dari aplikasi 'my planing web' milik Anda
        const firebaseConfig = {
            apiKey: "AIzaSyAI7AghqaRRAu3apIX4lycUnCowFqUElEk",
            authDomain: "predikate-2ba52.firebaseapp.com",
            projectId: "predikate-2ba52",
            storageBucket: "predikate-2ba52.firebasestorage.app",
            messagingSenderId: "914840717233",
            appId: "1:914840717233:web:5b4ed8007785a27dad1f90",
            measurementId: "G-BERQCPQK0B"
        };

        // Inisialisasi koneksi
        const app = initializeApp(firebaseConfig);
        const db = getFirestore(app);

        // Ambil elemen HTML
        const tombol = document.getElementById("btnSimpan");
        const statusEksekusi = document.getElementById("teksStatus");
        
        // Logika klik tombol
        tombol.addEventListener("click", async () => {
            tombol.innerText = "Sedang Mengirim...";
            tombol.disabled = true;
            statusEksekusi.style.display = "none";

            try {
                // Menyimpan data ke tabel/koleksi bernama 'laporan_koneksi'
                await addDoc(collection(db, "laporan_koneksi"), {
                    nama_aplikasi: "my planing web",
                    koneksi: "Aktif dan Berhasil",
                    dikirim_pada: new Date()
                });
                
                // Menampilkan efek sukses jika berhasil
                statusEksekusi.style.display = "block";
            } catch (error) {
                alert("Gagal terhubung. Pastikan Rules Firestore Anda sudah diset ke 'Test Mode'.");
                console.error(error);
            } finally {
                tombol.innerText = "Klik untuk Tes Koneksi Database";
                tombol.disabled = false;
            }
        });
    </script>
</body>
</html>
