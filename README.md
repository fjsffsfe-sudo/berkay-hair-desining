[gemini-code-1794162608854.html](https://github.com/user-attachments/files/34551108/gemini-code-1794162608854.html)
# berkay-hair-desining
[gemini-code-1794162608854.html](https://github.com/user-attachments/files/34551112/gemini-code-1794162608854.html)
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BERKAY HAIR DESIGN | Her Zaman 1 Adım Önde</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@400;600;800;900&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #050505;
      color: #f4f4f5;
    }
    .red-script {
      font-family: 'Great Vibes', cursive;
      color: #ef4444;
      text-shadow: 0 0 15px rgba(239, 68, 68, 0.4);
    }
    .neon-border {
      border: 1px solid rgba(239, 68, 68, 0.3);
      box-shadow: 0 0 20px rgba(239, 68, 68, 0.1);
    }
    .neon-border:hover {
      border-color: #ef4444;
      box-shadow: 0 0 25px rgba(239, 68, 68, 0.3);
    }
  </style>
</head>
<body class="min-h-screen flex flex-col justify-between selection:bg-red-600 selection:text-white">

  <!-- Header -->
  <header class="border-b border-zinc-800/80 bg-zinc-950/80 backdrop-blur sticky top-0 z-50 px-6 py-4">
    <div class="max-w-5xl mx-auto flex justify-between items-center">
      <div class="flex items-center gap-3 cursor-pointer" onclick="showPage('home')">
        <i class="fa-solid fa-scissors text-red-500 text-2xl"></i>
        <span class="red-script text-3xl md:text-4xl font-bold tracking-wide">Berkay Hair Design</span>
      </div>
      <div class="flex items-center gap-4">
        <button onclick="showPage('home')" class="text-zinc-300 hover:text-white text-xs md:text-sm font-bold uppercase tracking-wider">Ana Sayfa</button>
        <button onclick="showPage('gallery')" class="text-zinc-300 hover:text-white text-xs md:text-sm font-bold uppercase tracking-wider">Galeri / Modeller</button>
        <button onclick="openAdminModal()" class="text-zinc-500 hover:text-red-400 text-xs font-bold uppercase tracking-wider">Admin Girişi</button>
      </div>
    </div>
  </header>

  <!-- 1. SAYFA: ANA SAYFA -->
  <main id="home-page">
    <!-- Hero Section -->
    <section class="relative py-20 px-6 text-center bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-zinc-900 via-zinc-950 to-black">
      <div class="max-w-3xl mx-auto">
        <span class="inline-block border border-red-500/40 bg-red-500/10 text-red-400 text-xs font-semibold px-4 py-1.5 rounded-full uppercase tracking-widest mb-6">
          Efsane Dizayn İşlemleri
        </span>
        <h1 class="red-script text-6xl md:text-8xl my-2 leading-tight">
          Berkay Hair Design
        </h1>
        <p class="text-xl md:text-2xl font-black text-zinc-300 tracking-wider uppercase mt-4 mb-2">
          HER ZAMAN 1 ADIM ÖNDE
        </p>
        <p class="text-zinc-400 max-w-lg mx-auto text-sm md:text-base mb-8">
          Kafa yapınıza özel anatomik kesim teknikleri ve profesyonel ekipmanlarla VIP saç & sakal tasarımı.
        </p>
        
        <div class="inline-flex items-center gap-3 bg-zinc-900/90 border border-zinc-800 px-6 py-3 rounded-2xl mb-8">
          <i class="fa-regular fa-calendar-check text-red-500 text-xl"></i>
          <div class="text-left">
            <div class="text-xs text-zinc-400 uppercase font-bold">Çalışma Günleri</div>
            <div class="text-sm font-extrabold text-white" id="work-days-display">Cumartesi - Pazar</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Özellikler -->
    <section class="max-w-5xl mx-auto px-6 py-12">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-zinc-900/60 p-6 rounded-2xl neon-border transition-all">
          <div class="w-12 h-12 bg-red-500/10 rounded-xl flex items-center justify-center text-red-500 text-2xl mb-4">
            <i class="fa-solid fa-ruler-combined"></i>
          </div>
          <h3 class="font-bold text-lg text-white mb-2">Kafa Yapısına Özel Kesim</h3>
          <p class="text-zinc-400 text-sm">Yüz hatlarınıza ve kafa kemik yapınıza en uygun özel tasarım saç kesimi.</p>
        </div>

        <div class="bg-zinc-900/60 p-6 rounded-2xl neon-border transition-all">
          <div class="w-12 h-12 bg-red-500/10 rounded-xl flex items-center justify-center text-red-500 text-2xl mb-4">
            <i class="fa-solid fa-bolt"></i>
          </div>
          <h3 class="font-bold text-lg text-white mb-2">Profesyonel Makineler</h3>
          <p class="text-zinc-400 text-sm">En son teknoloji, yüksek performanslı ve hassas kesim sağlayan profesyonel ekipmanlar.</p>
        </div>

        <div class="bg-zinc-900/60 p-6 rounded-2xl neon-border transition-all">
          <div class="w-12 h-12 bg-red-500/10 rounded-xl flex items-center justify-center text-red-500 text-2xl mb-4">
            <i class="fa-solid fa-wand-magic-sparkles"></i>
          </div>
          <h3 class="font-bold text-lg text-white mb-2">Efsane Dizayn İşlemleri</h3>
          <p class="text-zinc-400 text-sm">Sadece kesim değil; kişiye özel sakal şekillendirme ve çizikli tasarım işlemleri.</p>
        </div>
      </div>
    </section>

    <!-- Fiyat Listesi -->
    <section class="max-w-4xl mx-auto px-6 py-12 w-full">
      <h2 class="text-center text-3xl font-extrabold mb-2 text-white">FİYAT LİSTESİ</h2>
      <p class="red-script text-center text-2xl mb-8">Kalite & Profesyonellik</p>

      <div class="bg-zinc-900/80 border border-zinc-800 rounded-3xl p-6 md:p-8 space-y-4 shadow-2xl">
        <div class="flex justify-between items-center border-b border-zinc-800/80 pb-4">
          <div>
            <h4 class="font-bold text-white text-base md:text-lg">Kafa Yapısına Özel Saç Kesimi</h4>
            <p class="text-xs text-zinc-400">Yıkama + Özel Şekillendirme Dahil</p>
          </div>
          <span class="text-red-500 font-extrabold text-xl">300 TL</span>
        </div>

        <div class="flex justify-between items-center border-b border-zinc-800/80 pb-4">
          <div>
            <h4 class="font-bold text-white text-base md:text-lg">Taper Fade / Low Fade Kesim</h4>
            <p class="text-xs text-zinc-400">Özel Geçişli Traş Modeli</p>
          </div>
          <span class="text-red-500 font-extrabold text-xl">350 TL</span>
        </div>

        <div class="flex justify-between items-center border-b border-zinc-800/80 pb-4">
          <div>
            <h4 class="font-bold text-white text-base md:text-lg">Sakal Tıraşı & Çizikli Dizayn</h4>
            <p class="text-xs text-zinc-400">Sıcak Havlu Bakımı & Hat Çizimi</p>
          </div>
          <span class="text-red-500 font-extrabold text-xl">200 TL</span>
        </div>

        <div class="flex justify-between items-center pt-2">
          <div>
            <h4 class="font-bold text-white text-base md:text-lg">VIP Efsane Dizayn Paketi</h4>
            <p class="text-xs text-zinc-400">Saç + Sakal + Çizikli Dizayn + Cilt Bakımı</p>
          </div>
          <span class="text-red-500 font-extrabold text-xl">500 TL</span>
        </div>
      </div>
    </section>

    <!-- Randevu Formu -->
    <section id="randevu" class="max-w-xl mx-auto px-6 py-12 w-full">
      <div class="bg-zinc-900 border border-red-500/30 p-8 rounded-3xl text-center relative overflow-hidden shadow-2xl">
        <h3 class="red-script text-4xl mb-2">Randevu Oluştur</h3>
        <p class="text-zinc-400 text-xs md:text-sm uppercase tracking-wider mb-6 font-semibold">Cumartesi ve Pazar Günleri Hizmet Vermekteyiz</p>
        
        <form onsubmit="handleAppointment(event)" class="space-y-4 text-left">
          <div>
            <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">Ad Soyad</label>
            <input id="client-name" type="text" required placeholder="Adınız Soyadınız" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm focus:outline-none focus:border-red-500 text-white">
          </div>
          <div>
            <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">Telefon</label>
            <input id="client-phone" type="tel" required placeholder="05XX XXX XX XX" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm focus:outline-none focus:border-red-500 text-white">
          </div>
          <div>
            <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">Hizmet / Model Seçin</label>
            <select id="client-service" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm focus:outline-none focus:border-red-500 text-white">
              <option value="Kafa Yapısına Özel Kesim">Kafa Yapısına Özel Kesim (300 TL)</option>
              <option value="Taper Fade">Taper Fade (350 TL)</option>
              <option value="Low Fade">Low Fade (350 TL)</option>
              <option value="Dizayn & Çizikli Traş">Dizayn & Çizikli Traş (350 TL)</option>
              <option value="Sakal Tıraşı & Hat Çizimi">Sakal Tıraşı & Hat Çizimi (200 TL)</option>
              <option value="VIP Efsane Dizayn Paketi">VIP Efsane Dizayn Paketi (500 TL)</option>
            </select>
          </div>
          <div class="grid grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">Gün Seçin</label>
              <select id="client-day" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm focus:outline-none focus:border-red-500 text-white">
                <option>Cumartesi</option>
                <option>Pazar</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">Saat</label>
              <select id="client-time" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm focus:outline-none focus:border-red-500 text-white">
                <option>10:00</option>
                <option>12:00</option>
                <option>14:00</option>
                <option>16:00</option>
                <option>18:00</option>
                <option>20:00</option>
              </select>
            </div>
          </div>
          <button type="submit" class="w-full bg-red-600 hover:bg-red-700 text-white font-bold py-4 rounded-xl transition-all uppercase tracking-wider text-sm mt-4 shadow-lg shadow-red-600/30">
            WhatsApp İle Randevuyu Onayla
          </button>
        </form>
      </div>
    </section>
  </main>

  <!-- 2. SAYFA: FOTOĞRAF GALERİSİ / TRAŞ KATALOĞU -->
  <main id="gallery-page" class="hidden max-w-5xl mx-auto px-6 py-12 w-full">
    <div class="text-center mb-10">
      <h2 class="text-3xl md:text-5xl font-extrabold text-white mb-2">TRAŞ MODELLERİ & GALERİ</h2>
      <p class="red-script text-3xl">Efsane Dizayn İşlemleri</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Taper Fade -->
      <div class="bg-zinc-900 border border-zinc-800 rounded-3xl overflow-hidden neon-border">
        <img src="https://images.unsplash.com/photo-1622286342621-4bd786c2447c?w=600&auto=format&fit=crop" alt="Taper Fade" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="font-bold text-xl text-white mb-2">Taper Fade</h3>
          <p class="text-zinc-400 text-sm mb-4">Yan ve ense bölgesinde yumuşak ve pürüzsüz geçiş sağlayan modern tarz.</p>
          <button onclick="selectModelAndBook('Taper Fade')" class="w-full bg-zinc-800 hover:bg-red-600 text-white font-bold py-3 rounded-xl transition-all text-xs uppercase">
            Bu Modeli İstiyorum (350 TL)
          </button>
        </div>
      </div>

      <!-- Low Fade -->
      <div class="bg-zinc-900 border border-zinc-800 rounded-3xl overflow-hidden neon-border">
        <img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?w=600&auto=format&fit=crop" alt="Low Fade" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="font-bold text-xl text-white mb-2">Low Fade</h3>
          <p class="text-zinc-400 text-sm mb-4">Kulak hizasından başlayan hafif ve karizmatik geçişli kesim modeli.</p>
          <button onclick="selectModelAndBook('Low Fade')" class="w-full bg-zinc-800 hover:bg-red-600 text-white font-bold py-3 rounded-xl transition-all text-xs uppercase">
            Bu Modeli İstiyorum (350 TL)
          </button>
        </div>
      </div>

      <!-- Dizayn & Çizikli Traşlar -->
      <div class="bg-zinc-900 border border-zinc-800 rounded-3xl overflow-hidden neon-border">
        <img src="https://images.unsplash.com/photo-1599351431202-1e0f0137899a?w=600&auto=format&fit=crop" alt="Dizayn Çizikli Traş" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="font-bold text-xl text-white mb-2">Dizayn & Çizikli Traş</h3>
          <p class="text-zinc-400 text-sm mb-4">Ustura ve profesyonel makinelerle kafaya özel çizik ve şekil tasarımı.</p>
          <button onclick="selectModelAndBook('Dizayn & Çizikli Traş')" class="w-full bg-zinc-800 hover:bg-red-600 text-white font-bold py-3 rounded-xl transition-all text-xs uppercase">
            Bu Modeli İstiyorum (350 TL)
          </button>
        </div>
      </div>

      <!-- Sakal & VIP Dizayn -->
      <div class="bg-zinc-900 border border-zinc-800 rounded-3xl overflow-hidden neon-border">
        <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?w=600&auto=format&fit=crop" alt="VIP Sakal Tasarımı" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="font-bold text-xl text-white mb-2">VIP Sakal Tasarımı</h3>
          <p class="text-zinc-400 text-sm mb-4">Keskin hatlar, sıcak havlu bakımı ve sakal yapısına özel dizayn.</p>
          <button onclick="selectModelAndBook('Sakal Tıraşı & Hat Çizimi')" class="w-full bg-zinc-800 hover:bg-red-600 text-white font-bold py-3 rounded-xl transition-all text-xs uppercase">
            Bu Modeli İstiyorum (200 TL)
          </button>
        </div>
      </div>
    </div>
  </main>

  <!-- Admin Modal (Şifre: 1234) -->
  <div id="admin-modal" class="fixed inset-0 bg-black/80 backdrop-blur hidden items-center justify-center p-4 z-50">
    <div class="bg-zinc-900 border border-red-500/40 p-6 rounded-3xl max-w-md w-full relative">
      <button onclick="closeAdminModal()" class="absolute top-4 right-4 text-zinc-400 hover:text-white">&times;</button>
      
      <!-- Login Form -->
      <div id="admin-login-view">
        <h3 class="red-script text-3xl mb-4">Admin Girişi</h3>
        <input id="admin-pass" type="password" placeholder="Şifre Girin (Varsayılan: 1234)" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-3 text-sm text-white mb-4">
        <button onclick="verifyAdmin()" class="w-full bg-red-600 hover:bg-red-700 text-white font-bold py-3 rounded-xl text-sm">Giriş Yap</button>
      </div>

      <!-- Dashboard View -->
      <div id="admin-dashboard-view" class="hidden space-y-4">
        <h3 class="red-script text-3xl">Yönetici Paneli</h3>
        
        <div>
          <label class="block text-xs font-bold text-zinc-400 uppercase mb-1">WhatsApp Randevu Numarası</label>
          <input id="admin-phone-input" type="text" placeholder="Örn: 905XXXXXXXXX" class="w-full bg-zinc-950 border border-zinc-800 rounded-xl p-2.5 text-sm text-white">
          <button onclick="saveAdminSettings()" class="bg-zinc-800 hover:bg-red-600 text-white text-xs font-bold px-4 py-2 rounded-lg mt-2">Kaydet</button>
        </div>

        <hr class="border-zinc-800 my-4">

        <div>
          <h4 class="font-bold text-sm text-zinc-300 mb-2">Alınan Son Randevular</h4>
          <div id="appointments-list" class="space-y-2 max-h-40 overflow-y-auto text-xs text-zinc-400">
            <!-- JS ile doldurulacak -->
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="border-t border-zinc-900 py-6 text-center text-xs text-zinc-600">
    <p>© 2026 <span class="red-script text-base text-red-500">Berkay Hair Design</span> - Her Zaman 1 Adım Önde.</p>
  </footer>

  <script>
    let myPhone = "905XXXXXXXXX";
    let appointments = JSON.parse(localStorage.getItem('bhd_appointments') || '[]');

    function showPage(pageName) {
      if(pageName === 'home') {
        document.getElementById('home-page').classList.remove('hidden');
        document.getElementById('gallery-page').classList.add('hidden');
      } else {
        document.getElementById('home-page').classList.add('hidden');
        document.getElementById('gallery-page').classList.remove('hidden');
      }
    }

    function selectModelAndBook(modelName) {
      showPage('home');
      const serviceSelect = document.getElementById('client-service');
      serviceSelect.value = modelName;
      document.getElementById('randevu').scrollIntoView({ behavior: 'smooth' });
    }

    function handleAppointment(e) {
      e.preventDefault();
      const name = document.getElementById('client-name').value;
      const phone = document.getElementById('client-phone').value;
      const service = document.getElementById('client-service').value;
      const day = document.getElementById('client-day').value;
      const time = document.getElementById('client-time').value;

      // Local storage kaydı
      appointments.push({ name, phone, service, day, time, date: new Date().toLocaleDateString() });
      localStorage.setItem('bhd_appointments', JSON.stringify(appointments));

      // WhatsApp Yönlendirme
      const msg = `Merhaba Berkay Hair Design! Web sitenizden randevu almak istiyorum:%0A%0A👤 *Müşteri:* ${name}%0A📞 *Telefon:* ${phone}%0A✂️ *Hizmet:* ${service}%0A📅 *Gün:* ${day}%0A⏰ *Saat:* ${time}`;
      window.open(`https://wa.me/${myPhone}?text=${msg}`, '_blank');
    }

    function openAdminModal() {
      document.getElementById('admin-modal').classList.remove('hidden');
      document.getElementById('admin-modal').classList.add('flex');
    }

    function closeAdminModal() {
      document.getElementById('admin-modal').classList.add('hidden');
      document.getElementById('admin-modal').classList.remove('flex');
    }

    function verifyAdmin() {
      const pass = document.getElementById('admin-pass').value;
      if(pass === "1234") {
        document.getElementById('admin-login-view').classList.add('hidden');
        document.getElementById('admin-dashboard-view').classList.remove('hidden');
        renderAppointments();
      } else {
        alert("Hatalı şifre!");
      }
    }

    function renderAppointments() {
      const listDiv = document.getElementById('appointments-list');
      if(appointments.length === 0) {
        listDiv.innerHTML = "<p>Henüz randevu alınmadı.</p>";
        return;
      }
      listDiv.innerHTML = appointments.map((a, i) => `
        <div class="bg-zinc-950 p-2 rounded border border-zinc-800">
          <span class="text-white font-bold">${a.name}</span> (${a.phone})<br>
          ${a.service} - <span class="text-red-400">${a.day} ${a.time}</span>
        </div>
      `).join('');
    }

    function saveAdminSettings() {
      const p = document.getElementById('admin-phone-input').value;
      if(p) {
        myPhone = p;
        alert("WhatsApp numaranız güncellendi!");
      }
    }
  </script>
</body>
</html>
