<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Karir Customer Service Officer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
       @import url('https://fonts.googleapis.com/css2?family=Funnel+Display:wght@300..800&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
        }
        
        .card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
        }
        
        .icon-circle {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(45deg, #4facfe 0%, #00f2fe 100%);
            margin: 0 auto;
            color: white;
            font-size: 24px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        
        .highlight {
            position: relative;
            display: inline-block;
        }
        
        .highlight::after {
            content: '';
            position: absolute;
            bottom: 5px;
            left: 0;
            width: 100%;
            height: 8px;
            background: linear-gradient(90deg, rgba(79,172,254,0.3) 0%, rgba(0,242,254,0.3) 100%);
            z-index: -1;
            border-radius: 4px;
        }
        
        .skill-item {
            transition: all 0.3s ease;
        }
        
        .skill-item:hover {
            transform: scale(1.05);
        }
        
        .fade-in {
            animation: fadeIn 0.8s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .blob {
            position: absolute;
            z-index: -1;
            filter: blur(40px);
            opacity: 0.5;
        }
        
        .blob-1 {
            width: 300px;
            height: 300px;
            background: #4facfe;
            top: 10%;
            left: 10%;
            border-radius: 50%;
        }
        
        .blob-2 {
            width: 250px;
            height: 250px;
            background: #00f2fe;
            bottom: 10%;
            right: 10%;
            border-radius: 50%;
        }
    </style>
</head>
<body class="p-4 md:p-8 lg:p-12 relative overflow-hidden">
    <div class="blob blob-1"></div>
    <div class="blob blob-2"></div>
    
    <div class="max-w-4xl mx-auto">
        <header class="text-center mb-12 fade-in">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">Data Diri Mahasiswa</h1>
            <h2 p class="text-xl text-gray-600 max-w-2xl mx-auto">Universitas Pamulang <span class="highlight"></span></h2>
            </p>Teknik Informatika</span></p>
        </header>
        
        <main class="space-y-8">
            <section class="card p-6 md:p-8 fade-in" style="animation-delay: 0.2s;">
                <div class="flex flex-col md:flex-row gap-6">
                    <div class="foto profil">
                        <div class>
                            <img src="https://media.licdn.com/dms/image/v2/D5603AQEDIkwFbmtaIg/profile-displayphoto-shrink_100_100/B56Zeaz.itHUAc-/0/1750649006933?e=1756339200&v=beta&t=ajcPm5UUgcIGY8ccRu7rdt-j-tiwoMjKv_6ffwM_y1M" alt="Logo Universitas Pamulang">
                        </div>
                        <h2 class="text-2xl font-semibold text-gray-800 mb-2">Mohamad Hilmi Sabitul Azmi</h2>
                        <h3 p class="text-xl font-medium text-gray-800 mb-2">231011450131</h3>

                        <div class="h-2 w-26 bg-gradient-to-r from-blue-400 to-cyan-400 mx-auto mb-4 rounded-full"></div>
                    </div>
                    <div class="md:w-2/3">
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            <span class="font-medium text-blue-500">Deskripsi<br> </span> Saya Mohamad Hilmi Sabitul Azmi, mahasiswa semester 3 Teknik Informatika di Universitas Pamulang, berdomisili di Depok. Fokus, haus tantangan, dan berorientasi hasil—siap tumbuh jadi problem solver digital yang memberi dampak nyata lewat teknologi
                        </p>
                        <p class="text-gray-700 leading-relaxed">
                           <span class="font-medium text-blue-500">Harapan kedepannya</span> harapan saya dapat terus mengembangkan keahlian teknis dan soft skill, berkontribusi dalam proyek inovatif, serta menjadi profesional yang mampu menciptakan solusi digital berdampak bagi masyarakat dan dunia industri.
                        </p>
                    </div>
                </div>
            </section>
            
            
        </main>
        
        <footer class="text-center mt-12 text-gray-500 text-sm fade-in" style="animation-delay: 1s;">
            <p>© 2025 Universitas Pamulang.</p>
            <p class="mt-1">"Universitas Pamulang, Berbagi untuk Negeri,."</p>
        </footer>
    </div>

    <script>
        // Simple animation trigger on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const fadeElements = document.querySelectorAll('.fade-in');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = 1;
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.1 });
            
            fadeElements.forEach(el => {
                el.style.opacity = 0;
                observer.observe(el);
            });
            
            // Interactive skill items
            const skillItems = document.querySelectorAll('.skill-item');
            skillItems.forEach(item => {
                item.addEventListener('mouseenter', function() {
                    this.style.boxShadow = '0 10px 15px -3px rgba(0, 0, 0, 0.1)';
                });
                item.addEventListener('mouseleave', function() {
                    this.style.boxShadow = 'none';
                });
            });
        });
    </script>
</body>
</html>
