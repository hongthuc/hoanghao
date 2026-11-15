<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Gạch Men & TBVS Hoàng Hảo - Gạch Ốp Lát, Sơn Nước, Thiết Bị Vệ Sinh Đà Nẵng | hoanghao.com</title>
  <meta name="description" content="Gạch Men & TBVS Hoàng Hảo (hoanghao.com) tại 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng. Chuyên cung cấp Gạch men, Sơn nước, Sen vòi & Thiết bị vệ sinh chính hãng giá sỉ lẻ tốt nhất. Hotline: 0934 940 340.">

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://hoanghao.com/">
  <meta property="og:site_name" content="hoanghao.com - Gạch Men & TBVS Hoàng Hảo">
  <meta property="og:title" content="Gạch Men & TBVS Hoàng Hảo - Chuyên Gạch Men, Sơn Nước, Thiết Bị Vệ Sinh Đà Nẵng">
  <meta property="og:description" content="Showroom Gạch Men, Sơn Nước, Sen Vòi & Thiết Bị Vệ Sinh Hoàng Hảo - 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng. Hotline/Zalo: 0934 940 340.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w1200">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW=w1200">
  <meta property="og:image:alt" content="Logo Gạch Men & TBVS Hoàng Hảo">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w1200">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w200">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Inter & Roboto (Chuẩn Flatsome Việt hóa) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#0f2952',     /* Xanh đậm chủ đạo theo tông Logo & Quang Hưng */
              primary: '#163d7a',  /* Xanh thương hiệu */
              light: '#e8f0fe',    /* Nền xanh nhạt */
              accent: '#d92b2b',   /* Đỏ điểm nhấn giảm giá & tiêu đề Flatsome */
              gold: '#f59e0b',     /* Vàng cam điểm nhấn */
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      padding-left: 10px;
      padding-right: 10px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 768px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tối ưu thanh cuộn ngang cho danh mục điện thoại nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Nút liên hệ nổi bật hiệu ứng sóng */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 43, 43, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 43, 43, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 43, 43, 0); }
    }
    .pulse-btn {
      animation: pulse-ring 2s infinite;
    }

    /* Flatsome Section Title Divider */
    .section-title-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #163d7a;
      margin-bottom: 1rem;
      padding-bottom: 0.4rem;
      flex-wrap: wrap;
      gap: 0.5rem;
    }
    .section-title-main {
      background-color: #163d7a;
      color: #ffffff;
      padding: 0.45rem 1rem;
      font-weight: 700;
      font-size: 0.95rem;
      text-transform: uppercase;
      letter-spacing: 0.02em;
      border-top-left-radius: 6px;
      border-top-right-radius: 6px;
      margin-bottom: -0.45rem;
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
    }
  </style>

  <script>
    // Hàm xử lý ảnh Google Drive tự động chuyển đổi dự phòng nếu link chính bị giới hạn
    function handleDriveImgError(img, fallbackLabel) {
      const fileId = img.getAttribute('data-drive-id');
      const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);

      if (fileId && step === 0) {
        img.setAttribute('data-fallback-step', '1');
        img.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
      } else if (fileId && step === 1) {
        img.setAttribute('data-fallback-step', '2');
        img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        img.onerror = null;
        const text = encodeURIComponent(fallbackLabel || 'Hoang Hao');
        img.src = 'https://placehold.co/600x600/163d7a/ffffff?text=' + text;
      }
    }
  </script>
</head>
<body class="bg-slate-50 text-slate-800">

  <!-- =====================================================================
       FLATSOME TOP BAR (Đơn giản, không có thanh UX Builder ở trên cùng)
  ====================================================================== -->
  <div class="bg-brand-dark text-white text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 overflow-hidden">
        <span class="inline-flex items-center gap-1.5 font-medium truncate">
          <i class="fa-solid fa-location-dot text-amber-400"></i>
          681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng
        </span>
        <span class="hidden lg:inline-block text-white/30">|</span>
        <span class="hidden lg:inline-flex items-center gap-1.5 text-slate-200">
          <i class="fa-solid fa-clock text-amber-400"></i>
          Mở cửa: 07:00 - 18:00 (Thứ 2 - Chủ Nhật)
        </span>
      </div>
      <div class="flex items-center gap-3 ml-auto">
        <a href="https://hoanghao.com" class="hover:text-amber-300 transition hidden sm:inline-flex items-center gap-1">
          <i class="fa-solid fa-globe text-amber-400"></i> hoanghao.com
        </a>
        <span class="hidden sm:inline-block text-white/30">|</span>
        <a href="https://www.facebook.com/gachmenhoanghao" target="_blank" rel="noopener" class="hover:text-amber-300 transition inline-flex items-center gap-1">
          <i class="fa-brands fa-facebook text-blue-400"></i> Fanpage Hoàng Hảo
        </a>
        <span class="text-white/30">|</span>
        <a href="#bao-gia" class="text-amber-300 font-semibold hover:underline">
          Báo giá sỉ & lẻ
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       HEADER CHÍNH (Logo gọn nhỏ, Không để nút Gọi ngay để tránh tràn viền)
  ====================================================================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
      
      <!-- Nút Menu trên điện thoại -->
      <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="md:hidden p-2 rounded-lg text-brand-dark bg-slate-100 hover:bg-slate-200 transition shrink-0">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
      <a href="#" class="flex items-center gap-2.5 shrink-0 group max-w-[75%] sm:max-w-none">
        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
          <img
            src="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w300"
            data-drive-id="1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW"
            onerror="handleDriveImgError(this, 'Logo HH')"
            alt="Logo Gạch Men & TBVS Hoàng Hảo"
            class="w-full h-full object-contain"
          >
        </div>
        <div class="leading-tight overflow-hidden">
          <span class="block text-sm sm:text-base md:text-lg font-extrabold text-brand-dark tracking-tight truncate">
            HOÀNG HẢO CERAMIC
          </span>
          <span class="block text-[11px] sm:text-xs text-slate-600 font-medium truncate">
            Gạch Men • Sơn Nước • Sen Vòi & TBVS
          </span>
        </div>
      </a>

      <!-- Ô tìm kiếm sản phẩm (Chuẩn Flatsome Header Search) -->
      <div class="hidden md:flex flex-1 max-w-xl mx-4">
        <div class="relative w-full flex items-center">
          <input
            id="desktopSearchInput"
            type="text"
            oninput="filterProductsBySearch(this.value)"
            placeholder="Tìm gạch lát nền 60x60, 80x80, gạch ốp tường, sơn nước, sen vòi..."
            class="w-full pl-3.5 pr-10 py-2 text-xs lg:text-sm bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:bg-white transition"
          >
          <button onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)" class="absolute right-1.5 px-2.5 py-1.5 bg-brand-primary text-white rounded-md hover:bg-brand-dark transition text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Cam kết chính hãng gọn nhẹ trên máy tính (Không để nút gọi ngay tránh tràn viền) -->
      <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-truck-fast text-brand-primary text-base"></i>
          <div>
            <strong class="block text-slate-800">Giao hàng tận nơi</strong>
            <span>Đà Nẵng & Miền Trung</span>
          </div>
        </div>
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-medal text-brand-accent text-base"></i>
          <div>
            <strong class="block text-slate-800">Giá kho tận gốc</strong>
            <span>Chiết khấu công trình cao</span>
          </div>
        </div>
      </div>

      <!-- Nút mở ô tìm kiếm trên điện thoại -->
      <button onclick="toggleMobileSearch()" aria-label="Tìm kiếm" class="md:hidden p-2 rounded-lg text-brand-dark bg-slate-100 hover:bg-slate-200 transition shrink-0">
        <i class="fa-solid fa-magnifying-glass text-base"></i>
      </button>
    </div>

    <!-- Ô tìm kiếm ẩn/hiện trên điện thoại -->
    <div id="mobileSearchBar" class="hidden md:hidden border-t border-slate-100 bg-white px-2.5 py-2">
      <div class="relative flex items-center">
        <input
          id="mobileSearchInput"
          type="text"
          oninput="filterProductsBySearch(this.value)"
          placeholder="Nhập tên gạch men, sơn nước, thiết bị vệ sinh..."
          class="w-full pl-3 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary"
        >
        <i class="fa-solid fa-magnifying-glass absolute right-3 text-slate-400 text-xs"></i>
      </div>
    </div>

    <!-- =====================================================================
         THANH DANH MỤC TRÊN MÁY TÍNH (Viết liền trên 1 hàng chữ nhỏ gọn,
         tuyệt đối không xuống dòng bên trong tên danh mục, tự xuống hàng 2 nếu hẹp)
    ====================================================================== -->
    <nav class="hidden md:block bg-brand-primary text-white border-t border-brand-dark/20">
      <div class="flatsome-container">
        <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-1 py-1">
          <li>
            <a href="#trang-chu" onclick="selectCategory('all')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-semibold bg-amber-500 text-slate-950 whitespace-nowrap hover:bg-amber-400 transition">
              <i class="fa-solid fa-house text-[11px]"></i> Trang chủ
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('gach-lat-nen')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Gạch lát nền
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('gach-op-tuong')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Gạch ốp tường
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('gach-gia-go')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Gạch giả gỗ
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('gach-san-vuon')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Gạch lát sân vườn
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('tbvs-sen-voi')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Sen vòi & Thiết bị vệ sinh
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('son-nuoc')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Sơn nước
            </a>
          </li>
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('gach-trang-tri')" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Gạch trang trí & Tranh đá
            </a>
          </li>
          <li>
            <a href="#doi-tac" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Đối tác
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Kiến thức xây dựng
            </a>
          </li>
          <li>
            <a href="#bao-gia" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Báo giá
            </a>
          </li>
          <li>
            <a href="#lien-he-map" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded text-[12px] lg:text-[13px] font-medium whitespace-nowrap hover:bg-white/15 transition">
              Bản đồ & Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- =====================================================================
       MENU DRAWER TRÊN ĐIỆN THOẠI
  ====================================================================== -->
  <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
    <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
    <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
      <div>
        <div class="p-3.5 bg-brand-dark text-white flex items-center justify-between">
          <span class="font-bold text-sm uppercase tracking-wider">Danh Mục Hoàng Hảo</span>
          <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center">
            <i class="fa-solid fa-xmark"></i>
          </button>
        </div>
        <ul class="divide-y divide-slate-100 text-sm font-medium text-slate-700">
          <li><a href="#san-pham-chinh" onclick="selectCategory('all'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Tất cả sản phẩm</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('gach-lat-nen'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Gạch lát nền cao cấp</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('gach-op-tuong'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Gạch ốp tường</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('gach-gia-go'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Gạch giả gỗ</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('gach-san-vuon'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Gạch lát sân vườn</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('tbvs-sen-voi'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Sen vòi & Thiết bị vệ sinh</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('son-nuoc'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Sơn nước & Chống thấm</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#san-pham-chinh" onclick="selectCategory('gach-trang-tri'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Gạch trang trí & Tranh đá</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#doi-tac" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Đối tác thương hiệu</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#tin-tuc" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Tin tức & Kiến thức</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#bao-gia" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Yêu cầu báo giá</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
          <li><a href="#lien-he-map" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Bản đồ & Fanpage</span><i class="fa-solid fa-chevron-right text-xs text-slate-400"></i></a></li>
        </ul>
      </div>
      <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
        <p class="font-bold text-brand-dark">GẠCH MEN & TBVS HOÀNG HẢO</p>
        <p><i class="fa-solid fa-location-dot text-brand-accent mr-1"></i> 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</p>
        <p><i class="fa-solid fa-phone text-brand-primary mr-1"></i> Hotline/Zalo: <strong>0934 940 340</strong></p>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       MAIN CONTENT (UX BUILDER SECTIONS)
  ====================================================================== -->
  <main id="trang-chu" class="py-3 md:py-5 space-y-6 md:space-y-8">

    <!-- ===================================================================
         SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Hình ảnh và chữ nằm gọn bên trong banner
         - Chữ cách xa viền ảnh banner (padding rộng rãi)
         - Đảm bảo trên điện thoại và máy tính không bị thiếu chữ
    ==================================================================== -->
    <section class="flatsome-container">
      <div class="relative w-full h-[250px] sm:h-[320px] md:h-[400px] lg:h-[430px] rounded-xl overflow-hidden shadow-md bg-brand-dark">
        
        <!-- SLIDE 1: Gạch Men, Sơn Nước, Thiết Bị Vệ Sinh Trọn Gói -->
        <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
          <!-- Ảnh nền cửa hàng thực tế kết hợp lớp phủ thương hiệu -->
          <img
            src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1600"
            data-drive-id="1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61"
            onerror="handleDriveImgError(this, 'Showroom Hoang Hao')"
            alt="Showroom Gạch Men & TBVS Hoàng Hảo"
            class="w-full h-full object-cover object-center opacity-35"
          >
          <div class="absolute inset-0 bg-gradient-to-r from-brand-dark via-brand-dark/90 to-brand-primary/75"></div>

          <!-- Nội dung chữ & ảnh nằm trọn bên trong, cách xa viền ảnh banner -->
          <div class="relative z-10 w-full h-full px-7 py-5 sm:px-12 sm:py-8 md:px-16 lg:px-20 flex items-center justify-between gap-4 md:gap-8">
            <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300">
                HOANGHAO.COM • TỔNG KHO PHÂN PHỐI TẠI ĐÀ NẴNG
              </p>
              <h1 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                GẠCH MEN & TBVS HOÀNG HẢO
              </h1>
              <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed">
                Chuyên cung cấp: <strong class="text-amber-300">Gạch men ốp lát</strong> • <strong class="text-amber-300">Sơn nước chính hãng</strong> • <strong class="text-amber-300">Sen vòi & Thiết bị vệ sinh</strong> mẫu mã sang trọng, giá sỉ & lẻ tốt nhất thị trường.
              </p>
              <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs md:text-sm">
                <span class="bg-white/15 border border-white/25 px-2.5 py-1 rounded-md text-white">
                  <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>681 Nguyễn Lương Bằng, P. Hải Vân, Đà Nẵng
                </span>
                <a href="#bao-gia" class="bg-amber-400 hover:bg-amber-300 text-slate-950 font-bold px-3.5 py-1.5 rounded-md transition">
                  Nhận Báo Giá Ngay
                </a>
              </div>
            </div>

            <!-- Khung hình ảnh thực tế nằm gọn bên trong Banner (Desktop & Tablet) -->
            <div class="hidden md:grid grid-cols-2 gap-2.5 w-5/12 max-w-[380px] shrink-0 p-2 bg-white/10 rounded-xl border border-white/20">
              <img
                src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600"
                data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY"
                onerror="handleDriveImgError(this, 'Gach Men')"
                alt="Gạch men Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30"
              >
              <img
                src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w600"
                data-drive-id="19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r"
                onerror="handleDriveImgError(this, 'Sen Voi TBVS')"
                alt="Thiết bị vệ sinh Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30"
              >
              <img
                src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w600"
                data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8"
                onerror="handleDriveImgError(this, 'Son Nuoc')"
                alt="Sơn nước & Vật liệu Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30 col-span-2"
              >
            </div>
          </div>
        </div>

        <!-- SLIDE 2: Giải Pháp Hoàn Thiện Ngôi Nhà Việt - Chiết Khấu Công Trình -->
        <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
          <img
            src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w1600"
            data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP"
            onerror="handleDriveImgError(this, 'Gach Op Lat')"
            alt="Gạch ốp lát cao cấp Hoàng Hảo"
            class="w-full h-full object-cover object-center opacity-30"
          >
          <div class="absolute inset-0 bg-gradient-to-r from-slate-900 via-brand-dark/95 to-brand-primary/85"></div>

          <!-- Nội dung chữ & ảnh nằm trọn bên trong, cách xa viền ảnh banner -->
          <div class="relative z-10 w-full h-full px-7 py-5 sm:px-12 sm:py-8 md:px-16 lg:px-20 flex items-center justify-between gap-4 md:gap-8">
            <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300">
                ƯU ĐÃI ĐẶC BIỆT CHO NHÀ THẦU & CHỦ NHÀ
              </p>
              <h2 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                TRỌN GÓI VẬT LIỆU HOÀN THIỆN
              </h2>
              <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed">
                Đầy đủ kích thước <strong class="text-amber-300">Gạch 60x60, 80x80, 60x120, Gạch giả gỗ</strong> cùng <strong class="text-amber-300">Sơn nước chống thấm</strong> và <strong class="text-amber-300">Combo Phòng Tắm</strong> bền đẹp theo thời gian.
              </p>
              <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs md:text-sm">
                <span class="bg-white/15 border border-white/25 px-2.5 py-1 rounded-md text-white">
                  <i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>Hotline/Zalo: 0934 940 340
                </span>
                <a href="#san-pham-chinh" class="bg-amber-400 hover:bg-amber-300 text-slate-950 font-bold px-3.5 py-1.5 rounded-md transition">
                  Xem Sản Phẩm Thực Tế
                </a>
              </div>
            </div>

            <!-- Khung hình ảnh thực tế nằm gọn bên trong Banner 2 -->
            <div class="hidden md:grid grid-cols-2 gap-2.5 w-5/12 max-w-[380px] shrink-0 p-2 bg-white/10 rounded-xl border border-white/20">
              <img
                src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w600"
                data-drive-id="1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr"
                onerror="handleDriveImgError(this, 'Gach Van Da')"
                alt="Mẫu gạch vân đá Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30"
              >
              <img
                src="https://drive.google.com/thumbnail?id=1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h&sz=w600"
                data-drive-id="1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h"
                onerror="handleDriveImgError(this, 'Thiet Bi Ve Sinh')"
                alt="Mẫu thiết bị vệ sinh Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30"
              >
              <img
                src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w600"
                data-drive-id="1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61"
                onerror="handleDriveImgError(this, 'Cua Hang Hoang Hao')"
                alt="Cửa hàng Gạch Men Hoàng Hảo"
                class="w-full h-28 lg:h-32 object-cover rounded-lg border border-white/30 col-span-2"
              >
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Banner Trái/Phải -->
        <button onclick="prevBanner()" aria-label="Banner trước" class="absolute left-1.5 sm:left-2.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button onclick="nextBanner()" aria-label="Banner tiếp" class="absolute right-1.5 sm:right-2.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm tròn chuyển Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button id="bannerDot0" onclick="goToBanner(0)" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
          <button id="bannerDot1" onclick="goToBanner(1)" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Giống mẫu quanghungceramic.vn)
         - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng không bị gãy dòng
         - Đẹp mắt và đồng bộ trên cả điện thoại và máy tính
    ==================================================================== -->
    <section class="flatsome-container">
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="flex items-center justify-between mb-3">
          <h2 class="text-sm sm:text-base font-bold text-brand-dark uppercase flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-brand-primary"></i>
            Danh Mục Sản Phẩm
          </h2>
          <span class="text-[11px] sm:text-xs text-slate-500">Chạm để lọc theo danh mục</span>
        </div>

        <!-- Lưới danh mục: chữ nhỏ gọn, whitespace-nowrap để không bao giờ bị rớt chữ -->
        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
          
          <button onclick="selectCategory('gach-lat-nen')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w300" data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY" onerror="handleDriveImgError(this, 'Gach Lat Nen')" alt="Gạch lát nền" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Gạch lát nền
            </span>
          </button>

          <button onclick="selectCategory('gach-op-tuong')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=1X31hmhpLVVORV-tmMSZYzBO-qtpyusry&sz=w300" data-drive-id="1X31hmhpLVVORV-tmMSZYzBO-qtpyusry" onerror="handleDriveImgError(this, 'Gach Op Tuong')" alt="Gạch ốp tường" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Gạch ốp tường
            </span>
          </button>

          <button onclick="selectCategory('gach-gia-go')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w300" data-drive-id="1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg" onerror="handleDriveImgError(this, 'Gach Gia Go')" alt="Gạch giả gỗ" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Gạch giả gỗ
            </span>
          </button>

          <button onclick="selectCategory('gach-san-vuon')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w300" data-drive-id="1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4" onerror="handleDriveImgError(this, 'Gach San Vuon')" alt="Gạch lát sân vườn" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Gạch lát sân vườn
            </span>
          </button>

          <button onclick="selectCategory('tbvs-sen-voi')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w300" data-drive-id="19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r" onerror="handleDriveImgError(this, 'Sen Voi TBVS')" alt="Thiết bị vệ sinh" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Thiết bị vệ sinh
            </span>
          </button>

          <button onclick="selectCategory('son-nuoc')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w300" data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8" onerror="handleDriveImgError(this, 'Son Nuoc')" alt="Sơn nước" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Sơn nước
            </span>
          </button>

          <button onclick="selectCategory('gach-trang-tri')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_&sz=w300" data-drive-id="15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_" onerror="handleDriveImgError(this, 'Gach Trang Tri')" alt="Gạch trang trí" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">
              Gạch trang trí
            </span>
          </button>

          <button onclick="selectCategory('all')" class="cat-card group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-primary hover:bg-brand-light/40 transition text-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-1.5 border border-slate-200 bg-slate-100 shrink-0">
              <img src="https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w300" data-drive-id="1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh" onerror="handleDriveImgError(this, 'Tat Ca SP')" alt="Tất cả sản phẩm" class="w-full h-full object-cover group-hover:scale-105 transition">
            </div>
            <span class="text-[11px] sm:text-xs font-semibold text-brand-primary whitespace-nowrap">
              Xem tất cả (19)
            </span>
          </button>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 3: TẤT CẢ SẢN PHẨM THỰC TẾ (19 ẢNH TỪ GOOGLE DRIVE)
         - Chia 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính
         - Có % giảm giá góc trên bên trái giống Flatsome + giá gốc gạch ngang & giá giảm
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
    ==================================================================== -->
    <section id="san-pham-chinh" class="flatsome-container space-y-6">
      
      <!-- Thanh lọc nhanh theo danh mục -->
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 id="currentCategoryTitle" class="section-title-main">
            <i class="fa-solid fa-table-cells-large"></i>
            SẢN PHẨM THỰC TẾ TẠI HOÀNG HẢO
          </h2>
          <!-- Các nút lọc chữ nhỏ gọn, nằm liền trên 1 hàng -->
          <div class="flex flex-wrap items-center gap-1.5 pt-1 sm:pt-0">
            <button onclick="selectCategory('all')" data-cat-btn="all" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-brand-primary text-white whitespace-nowrap transition">
              Tất cả (19)
            </button>
            <button onclick="selectCategory('gach-lat-nen')" data-cat-btn="gach-lat-nen" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Gạch lát nền
            </button>
            <button onclick="selectCategory('gach-op-tuong')" data-cat-btn="gach-op-tuong" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Gạch ốp tường
            </button>
            <button onclick="selectCategory('gach-gia-go')" data-cat-btn="gach-gia-go" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Gạch giả gỗ
            </button>
            <button onclick="selectCategory('gach-san-vuon')" data-cat-btn="gach-san-vuon" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Gạch lát sân vườn
            </button>
            <button onclick="selectCategory('tbvs-sen-voi')" data-cat-btn="tbvs-sen-voi" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Sen vòi & TBVS
            </button>
            <button onclick="selectCategory('son-nuoc')" data-cat-btn="son-nuoc" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Sơn nước
            </button>
            <button onclick="selectCategory('gach-trang-tri')" data-cat-btn="gach-trang-tri" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
              Gạch trang trí
            </button>
          </div>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột tablet, 5 cột desktop -->
        <div id="productGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5 md:gap-4">
          <!-- Sản phẩm sẽ được render từ danh sách 19 ảnh thực tế Google Drive bên dưới -->
        </div>
      </div>

      <!-- Khối chuyên đề 1: GẠCH ỐP LÁT NỔI BẬT (Chuẩn bố cục quanghungceramic.vn) -->
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-border-all"></i>
            GẠCH MEN ỐP LÁT BÁN CHẠY
          </h2>
          <div class="flex flex-wrap items-center gap-2 text-xs text-slate-600">
            <span class="whitespace-nowrap">Kích thước: 60x60</span> •
            <span class="whitespace-nowrap">80x80</span> •
            <span class="whitespace-nowrap">60x120</span> •
            <span class="whitespace-nowrap">30x60</span>
          </div>
        </div>
        <div id="tileHighlightGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5 md:gap-4"></div>
      </div>

      <!-- Khối chuyên đề 2: SEN VÒI, THIẾT BỊ VỆ SINH & SƠN NƯỚC -->
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-faucet-drip"></i>
            SEN VÒI, THIẾT BỊ VỆ SINH & SƠN NƯỚC
          </h2>
          <div class="flex flex-wrap items-center gap-2 text-xs text-slate-600">
            <span class="whitespace-nowrap">Bồn cầu 1 khối</span> •
            <span class="whitespace-nowrap">Sen cây tắm</span> •
            <span class="whitespace-nowrap">Lavabo</span> •
            <span class="whitespace-nowrap">Sơn nội ngoại thất</span>
          </div>
        </div>
        <div id="sanitaryAndPaintGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5 md:gap-4"></div>
      </div>

    </section>

    <!-- ===================================================================
         SECTION 4: HÌNH ẢNH CỬA HÀNG THỰC TẾ & GIỚI THIỆU HOÀNG HẢO
         (Sử dụng ảnh cửa hàng 1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61)
    ==================================================================== -->
    <section class="flatsome-container">
      <div class="bg-white rounded-xl p-4 sm:p-6 shadow-xs border border-slate-200">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
          <div class="lg:col-span-6">
            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100 shadow-sm">
              <img
                src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1200"
                data-drive-id="1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61"
                onerror="handleDriveImgError(this, 'Showroom Hoang Hao 681 Nguyen Luong Bang')"
                alt="Showroom Gạch Men & TBVS Hoàng Hảo - 681 Nguyễn Lương Bằng, Đà Nẵng"
                class="w-full h-64 sm:h-80 md:h-96 object-cover"
              >
            </div>
          </div>
          <div class="lg:col-span-6 space-y-3.5">
            <span class="inline-block text-xs font-bold uppercase tracking-wider text-brand-primary bg-brand-light px-3 py-1 rounded-md">
              Về Chúng Tôi • hoanghao.com
            </span>
            <h2 class="text-lg sm:text-2xl font-extrabold text-brand-dark leading-snug">
              SHOWROOM GẠCH MEN & THIẾT BỊ VỆ SINH HOÀNG HẢO ĐÀ NẴNG
            </h2>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Tọa lạc tại <strong class="text-slate-800">681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</strong>, <strong>Gạch Men & TBVS Hoàng Hảo</strong> là địa chỉ tin cậy hàng đầu chuyên phân phối sỉ và lẻ vật liệu hoàn thiện cho nhà phố, biệt thự, căn hộ và các dự án xây dựng tại Đà Nẵng và khu vực miền Trung.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-2.5 pt-1">
              <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                <i class="fa-solid fa-table-cells text-brand-primary text-lg mb-1"></i>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800">Gạch Men Cao Cấp</h3>
                <p class="text-[11px] text-slate-500 mt-0.5">Gạch lát nền, ốp tường, giả gỗ, sân vườn đa quy cách.</p>
              </div>
              <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                <i class="fa-solid fa-fill-drip text-brand-accent text-lg mb-1"></i>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800">Sơn Nước Chính Hãng</h3>
                <p class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất, chống thấm bền màu, pha màu vi tính.</p>
              </div>
              <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                <i class="fa-solid fa-bath text-amber-500 text-lg mb-1"></i>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800">Sen Vòi & TBVS</h3>
                <p class="text-[11px] text-slate-500 mt-0.5">Bồn cầu, lavabo, sen cây tắm inox 304 bảo hành dài hạn.</p>
              </div>
            </div>
            <div class="pt-2 flex flex-wrap items-center gap-3">
              <a href="tel:0934940340" class="inline-flex items-center gap-2 bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
                <i class="fa-solid fa-phone"></i> Tư vấn: 0934 940 340
              </a>
              <a href="#bao-gia" class="inline-flex items-center gap-2 bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-lg transition">
                <i class="fa-solid fa-file-invoice-dollar text-brand-accent"></i> Gửi yêu cầu báo giá
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 5: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
    ==================================================================== -->
    <section id="bao-gia" class="flatsome-container">
      <div class="bg-gradient-to-br from-brand-dark to-brand-primary rounded-xl p-4 sm:p-6 md:p-8 text-white shadow-md">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          
          <div class="lg:col-span-5 space-y-3">
            <span class="inline-block text-xs font-bold uppercase tracking-wider bg-amber-400 text-slate-950 px-3 py-1 rounded">
              Hỗ Trợ Nhanh 24/7
            </span>
            <h2 class="text-lg sm:text-2xl font-extrabold leading-snug">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ / LẺ
            </h2>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
              Quý khách hàng, chủ nhà, thầu xây dựng cần báo giá gạch men ốp lát, sơn nước hoặc combo thiết bị vệ sinh trọn gói? Hãy để lại thông tin, Hoàng Hảo sẽ gửi bảng báo giá chiết khấu tốt nhất qua Zalo hoặc SĐT ngay!
            </p>
            <ul class="space-y-2 text-xs sm:text-sm text-slate-100 pt-1">
              <li class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-amber-400"></i>
                <span>Chiết khấu cao cho công trình nhà phố, biệt thự, nhà trọ</span>
              </li>
              <li class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-amber-400"></i>
                <span>Hỗ trợ tính toán số lượng gạch & sơn chuẩn xác, tiết kiệm</span>
              </li>
              <li class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-amber-400"></i>
                <span>Giao hàng nhanh tận chân công trình tại Đà Nẵng</span>
              </li>
            </ul>
          </div>

          <div class="lg:col-span-7">
            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-lg space-y-3.5">
              <h3 class="text-sm sm:text-base font-bold text-brand-dark border-b border-slate-200 pb-2">
                <i class="fa-solid fa-paper-plane text-brand-primary mr-1.5"></i>Thông Tin Yêu Cầu Báo Giá
              </h3>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="qName" type="text" required placeholder="Ví dụ: Anh Minh / Chị Lan" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary">
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Nhập SĐT nhận báo giá..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục cần báo giá *</label>
                  <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary bg-white">
                    <option value="Trọn gói Gạch men + Sơn nước + TBVS">Trọn gói: Gạch men + Sơn nước + TBVS</option>
                    <option value="Gạch men (Lát nền, Ốp tường, Giả gỗ, Sân vườn)">Gạch men (Lát nền, Ốp tường, Giả gỗ...)</option>
                    <option value="Sen vòi & Thiết bị vệ sinh">Sen vòi & Thiết bị vệ sinh</option>
                    <option value="Sơn nước & Chống thấm">Sơn nước & Chống thấm</option>
                    <option value="Khác / Báo giá đại lý & nhà thầu">Báo giá sỉ cho Nhà thầu / Công trình</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình</label>
                  <input id="qAddress" type="text" placeholder="Quận Liên Chiểu, Hải Vân, Đà Nẵng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary">
                </div>
              </div>

              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Nội dung chi tiết (Mã sản phẩm, diện tích m², số lượng...)</label>
                <textarea id="qNote" rows="2" placeholder="Ví dụ: Cần báo giá 120m2 gạch lát nền 80x80, 2 bộ bồn cầu + sen cây và sơn nhà 3 tầng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary"></textarea>
              </div>

              <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm"></div>

              <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                <button type="submit" class="w-full sm:w-auto px-6 py-2.5 bg-brand-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm rounded-lg transition cursor-pointer">
                  <i class="fa-solid fa-check-circle mr-1"></i> GỬI YÊU CẦU BÁO GIÁ
                </button>
                <a href="https://zalo.me/0934940340" target="_blank" rel="noopener" class="w-full sm:w-auto text-center px-4 py-2.5 bg-blue-50 hover:bg-blue-100 text-brand-primary font-semibold text-xs sm:text-sm rounded-lg transition">
                  Chat Zalo: 0934 940 340
                </a>
              </div>
            </form>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KIẾN THỨC XÂY DỰNG)
    ==================================================================== -->
    <section id="tin-tuc" class="flatsome-container">
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-newspaper"></i>
            TIN TỨC & KIẾN THỨC XÂY DỰNG
          </h2>
          <span class="text-xs text-slate-500">Kinh nghiệm chọn gạch men, sơn nước & TBVS</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
          
          <!-- Bài viết 1 -->
          <article class="rounded-lg border border-slate-200 overflow-hidden bg-white hover:shadow-md transition flex flex-col">
            <div class="relative h-40 bg-slate-100 overflow-hidden">
              <img
                src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w600"
                data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP"
                onerror="handleDriveImgError(this, 'Kinh Nghiem Chon Gach')"
                alt="Kinh nghiệm chọn gạch lát nền"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
              >
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
              <div>
                <span class="text-[11px] text-brand-primary font-semibold">Kiến thức gạch ốp lát</span>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-0.5 leading-snug">
                  Kinh nghiệm chọn gạch lát nền 60x60, 80x80 và 60x120 chuẩn đẹp cho nhà phố Đà Nẵng
                </h3>
                <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                  Hướng dẫn cách phối màu gạch vân đá bóng kiếng Porcelain giúp phòng khách rộng rãi, sang trọng và chống thấm ố hiệu quả.
                </p>
              </div>
              <a href="#bao-gia" class="text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1 pt-1">
                Tư vấn mẫu gạch này <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="rounded-lg border border-slate-200 overflow-hidden bg-white hover:shadow-md transition flex flex-col">
            <div class="relative h-40 bg-slate-100 overflow-hidden">
              <img
                src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w600"
                data-drive-id="19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r"
                onerror="handleDriveImgError(this, 'Combo Thiet Bi Ve Sinh')"
                alt="Cách chọn thiết bị vệ sinh"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
              >
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
              <div>
                <span class="text-[11px] text-brand-primary font-semibold">Thiết bị vệ sinh & Sen vòi</span>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-0.5 leading-snug">
                  Bí quyết chọn trọn bộ Bồn cầu 1 khối, Lavabo và Sen cây tắm bền đẹp, tiết kiệm chi phí
                </h3>
                <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                  Lựa chọn men sứ phủ Nano kháng khuẩn kết hợp sen vòi Inox 304 và đồng thau mạ Crom giúp phòng tắm luôn sáng bóng.
                </p>
              </div>
              <a href="#bao-gia" class="text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1 pt-1">
                Nhận báo giá combo <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="rounded-lg border border-slate-200 overflow-hidden bg-white hover:shadow-md transition flex flex-col">
            <div class="relative h-40 bg-slate-100 overflow-hidden">
              <img
                src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w600"
                data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8"
                onerror="handleDriveImgError(this, 'Son Nuoc Chong Tham')"
                alt="Giải pháp sơn nước chống thấm"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
              >
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
              <div>
                <span class="text-[11px] text-brand-primary font-semibold">Sơn nước & Chống thấm</span>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-0.5 leading-snug">
                  Quy trình sơn nước và chống thấm tường ngoài trời bền màu trước khí hậu miền Trung
                </h3>
                <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                  Giải pháp kết hợp bột trét, sơn lót kháng kiềm và sơn phủ ngoại thất cao cấp giúp bảo vệ ngôi nhà khỏi ẩm mốc, bong tróc.
                </p>
              </div>
              <a href="#bao-gia" class="text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1 pt-1">
                Tính lượng sơn miễn phí <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="rounded-lg border border-slate-200 overflow-hidden bg-white hover:shadow-md transition flex flex-col">
            <div class="relative h-40 bg-slate-100 overflow-hidden">
              <img
                src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w600"
                data-drive-id="1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61"
                onerror="handleDriveImgError(this, 'Showroom Hoang Hao')"
                alt="Tổng kho gạch men Hoàng Hảo Liên Chiểu Hải Vân"
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
              >
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
              <div>
                <span class="text-[11px] text-brand-primary font-semibold">Tin tức Hoàng Hảo</span>
                <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-0.5 leading-snug">
                  Hoàng Hảo Ceramic cập nhật các mẫu gạch giả gỗ & gạch sân vườn chống trơn mới nhất
                </h3>
                <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                  Trực tiếp tham quan hàng trăm mẫu gạch men, sơn nước và thiết bị vệ sinh thực tế tại 681 Nguyễn Lương Bằng, Đà Nẵng.
                </p>
              </div>
              <a href="#lien-he-map" class="text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1 pt-1">
                Xem địa chỉ cửa hàng <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 7: DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU
    ==================================================================== -->
    <section id="doi-tac" class="flatsome-container">
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-handshake"></i>
            ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
          </h2>
          <span class="text-xs text-slate-500">Hàng chính hãng 100% từ nhà máy</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-6 gap-2.5">
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-brand-dark tracking-wider">VIGLACERA</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát & TBVS</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-red-700 tracking-wider">PRIME</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gạch men cao cấp</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-blue-800 tracking-wider">ĐỒNG TÂM</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gạch Porcelain & Ceramic</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-sky-700 tracking-wider">INAX / TOTO</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh & Sen vòi</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-indigo-800 tracking-wider">DULUX / JOTUN</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn nước nội ngoại thất</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <span class="text-sm sm:text-base font-extrabold text-amber-700 tracking-wider">KOVA / NIPPON</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn nước & Chống thấm</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================
         SECTION 8: ĐƯA GOOGLE MAP VÀ FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
         - Địa chỉ: 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng
         - SĐT: 0934 940 340
         - Fanpage: https://www.facebook.com/gachmenhoanghao
    ==================================================================== -->
    <section id="lien-he-map" class="flatsome-container">
      <div class="bg-white rounded-xl p-3 sm:p-5 shadow-xs border border-slate-200">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-map-location-dot"></i>
            BẢN ĐỒ GOOGLE MAPS & FANPAGE HOÀNG HẢO
          </h2>
          <span class="text-xs text-slate-600 font-medium">681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
          
          <!-- Cột Trái (7/12): Bản đồ Google Maps ngoài trang chủ -->
          <div class="lg:col-span-7 flex flex-col justify-between rounded-xl border border-slate-200 overflow-hidden bg-slate-50">
            <div class="p-3 bg-slate-100 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
              <div class="text-xs sm:text-sm font-bold text-brand-dark flex items-center gap-1.5">
                <i class="fa-solid fa-location-dot text-brand-accent"></i>
                <span>Vị trí Showroom: 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</span>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=G%E1%BA%A1ch+Men+TBVS+Ho%C3%A0ng+H%E1%BA%A3o+681+Nguy%E1%BB%85n+L%C6%B0%C6%A1ng+B%E1%BA%B1ng+%C4%90%C3%A0+N%E1%BA%B5ng"
                target="_blank"
                rel="noopener"
                class="text-xs font-semibold text-white bg-brand-primary hover:bg-brand-dark px-3 py-1 rounded transition inline-flex items-center gap-1"
              >
                <i class="fa-solid fa-diamond-turn-right"></i> Chỉ đường Google Maps
              </a>
            </div>
            <div class="w-full h-72 sm:h-80 md:h-96 relative bg-slate-200">
              <iframe
                title="Bản đồ Gạch Men & TBVS Hoàng Hảo 681 Nguyễn Lương Bằng Đà Nẵng"
                src="https://maps.google.com/maps?q=681%20Nguy%E1%BB%85n%20L%C6%B0%C6%A1ng%20B%E1%BA%B1ng,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột Phải (5/12): Fanpage Facebook Gạch Men & TBVS Hoàng Hảo ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col justify-between rounded-xl border border-slate-200 overflow-hidden bg-slate-50 p-3.5 sm:p-4 space-y-3">
            <div class="flex items-center justify-between border-b border-slate-200 pb-2.5">
              <div class="flex items-center gap-2.5">
                <img
                  src="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w200"
                  data-drive-id="1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW"
                  onerror="handleDriveImgError(this, 'Logo')"
                  alt="Logo Hoàng Hảo"
                  class="w-10 h-10 rounded-full object-contain border border-slate-300 bg-white p-0.5"
                >
                <div>
                  <h3 class="font-bold text-xs sm:text-sm text-brand-dark">Gạch Men & TBVS Hoàng Hảo</h3>
                  <p class="text-[11px] text-slate-500">facebook.com/gachmenhoanghao</p>
                </div>
              </div>
              <a
                href="https://www.facebook.com/gachmenhoanghao"
                target="_blank"
                rel="noopener"
                class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold px-3 py-1.5 rounded-lg inline-flex items-center gap-1.5 transition shrink-0"
              >
                <i class="fa-brands fa-facebook"></i> Theo dõi Trang
              </a>
            </div>

            <!-- Nhúng Facebook Page Plugin kết hợp Thẻ thông tin trực tiếp của Fanpage -->
            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white flex flex-col items-center">
              <iframe
                title="Fanpage Gạch Men Hoàng Hảo"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fgachmenhoanghao&tabs=timeline&width=340&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                width="340"
                height="220"
                style="border:none;overflow:hidden;max-width:100%;"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>

            <!-- Thông tin trực quan Fanpage & Cửa hàng để luôn hiển thị rõ trên mọi trình duyệt -->
            <div class="bg-white rounded-lg p-3 border border-slate-200 space-y-2 text-xs">
              <div class="flex items-start gap-2">
                <i class="fa-solid fa-store text-brand-primary mt-0.5"></i>
                <span><strong>Chuyên cung cấp:</strong> Gạch men ốp lát, Sơn nước nội ngoại thất, Sen vòi & Thiết bị vệ sinh.</span>
              </div>
              <div class="flex items-start gap-2">
                <i class="fa-solid fa-location-dot text-brand-accent mt-0.5"></i>
                <span><strong>Địa chỉ:</strong> 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</span>
              </div>
              <div class="flex items-start gap-2">
                <i class="fa-solid fa-phone-volume text-emerald-600 mt-0.5"></i>
                <span><strong>Hotline / Zalo báo giá:</strong> <a href="tel:0934940340" class="font-bold text-brand-accent hover:underline">0934 940 340</a></span>
              </div>
              <div class="pt-1 flex flex-wrap gap-2">
                <a href="https://www.facebook.com/gachmenhoanghao" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-blue-50 hover:bg-blue-100 text-[#1877F2] font-semibold transition">
                  <i class="fa-brands fa-facebook-messenger mr-1"></i> Nhắn tin Fanpage
                </a>
                <a href="https://zalo.me/0934940340" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-emerald-50 hover:bg-emerald-100 text-emerald-700 font-semibold transition">
                  <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Zalo Ngay
                </a>
              </div>
            </div>

          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- =====================================================================
       MODAL XEM NHANH ẢNH THỰC TẾ & YÊU CẦU BÁO GIÁ SẢN PHẨM
  ====================================================================== -->
  <div id="productModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-4 bg-slate-900/75 backdrop-blur-xs">
    <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-4 py-3 bg-brand-dark text-white">
        <h3 id="modalTitle" class="font-bold text-sm sm:text-base truncate pr-2">Chi tiết sản phẩm</h3>
        <button onclick="closeProductModal()" class="w-8 h-8 rounded-lg bg-white/10 hover:bg-white/20 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-5 grid grid-cols-1 sm:grid-cols-2 gap-4 items-center">
        <div class="relative rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-square">
          <span id="modalDiscountBadge" class="absolute top-2.5 left-2.5 z-10 bg-brand-accent text-white text-xs font-bold px-2.5 py-1 rounded shadow">
            -20%
          </span>
          <img id="modalImg" src="" alt="Ảnh thực tế sản phẩm" class="w-full h-full object-cover">
        </div>
        <div class="space-y-3">
          <span id="modalCategory" class="inline-block text-xs font-semibold text-brand-primary bg-brand-light px-2.5 py-1 rounded">
            Danh mục
          </span>
          <h4 id="modalName" class="text-base sm:text-lg font-bold text-slate-800 leading-snug"></h4>
          <div class="flex items-baseline gap-2.5">
            <span id="modalSalePrice" class="text-lg sm:text-xl font-extrabold text-brand-accent"></span>
            <del id="modalOldPrice" class="text-xs sm:text-sm text-slate-400"></del>
          </div>
          <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed"></p>
          <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200 text-xs space-y-1 text-slate-700">
            <p><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Hàng chính hãng có sẵn tại Showroom Hoàng Hảo</p>
            <p><i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i>681 Nguyễn Lương Bằng, P. Hải Vân, Đà Nẵng</p>
          </div>
          <div class="pt-2 flex flex-col gap-2">
            <a href="tel:0934940340" class="w-full py-2.5 px-4 bg-brand-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm rounded-lg text-center transition">
              <i class="fa-solid fa-phone mr-1.5"></i> Gọi Hotline: 0934 940 340
            </a>
            <button onclick="selectProductForQuote()" class="w-full py-2.5 px-4 bg-brand-primary hover:bg-brand-dark text-white font-semibold text-xs sm:text-sm rounded-lg text-center transition cursor-pointer">
              <i class="fa-solid fa-file-signature mr-1.5"></i> Nhận Báo Giá Sỉ / Công Trình Mẫu Này
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       FOOTER CHUẨN FLATSOME (Đầy đủ thông tin hoanghao.com, Địa chỉ, SĐT)
  ====================================================================== -->
  <footer class="bg-brand-dark text-slate-200 mt-8 border-t-4 border-amber-400">
    <div class="flatsome-container py-8 md:py-10">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 md:gap-8">
        
        <!-- Cột 1: Thông tin Gạch Men & TBVS Hoàng Hảo -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <div class="w-11 h-11 rounded-lg bg-white p-1 flex items-center justify-center shrink-0">
              <img
                src="https://drive.google.com/thumbnail?id=1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW&sz=w200"
                data-drive-id="1I7SR5hfEQ9KYf5uWor4eUTMBQUDM_AgW"
                onerror="handleDriveImgError(this, 'HH')"
                alt="Logo Hoàng Hảo"
                class="w-full h-full object-contain"
              >
            </div>
            <div>
              <h3 class="text-base sm:text-lg font-extrabold text-white uppercase">
                GẠCH MEN & TBVS HOÀNG HẢO
              </h3>
              <p class="text-xs text-amber-300 font-medium">Website: hoanghao.com</p>
            </div>
          </div>
          <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
            Chuyên cung cấp sỉ & lẻ: <strong>Gạch men ốp lát</strong>, <strong>Sơn nước chính hãng</strong>, <strong>Sen vòi & Thiết bị vệ sinh</strong> chất lượng cao, mẫu mã đa dạng cho mọi công trình tại Đà Nẵng và khu vực miền Trung.
          </p>
          <ul class="space-y-1.5 text-xs sm:text-sm text-slate-200">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
              <span><strong>Địa chỉ:</strong> 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone-volume text-amber-400"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0934940340" class="text-amber-300 font-bold hover:underline">0934 940 340</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-amber-400"></i>
              <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/gachmenhoanghao" target="_blank" rel="noopener" class="hover:underline">facebook.com/gachmenhoanghao</a></span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm (Giống web mẫu) -->
        <div class="lg:col-span-4 space-y-2.5">
          <h4 class="text-sm font-bold text-white uppercase tracking-wider border-b border-white/15 pb-2">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="grid grid-cols-2 gap-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#san-pham-chinh" onclick="selectCategory('gach-lat-nen')" class="hover:text-amber-300 transition">• Gạch lát nền</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('gach-op-tuong')" class="hover:text-amber-300 transition">• Gạch ốp tường</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('gach-gia-go')" class="hover:text-amber-300 transition">• Gạch giả gỗ</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('gach-san-vuon')" class="hover:text-amber-300 transition">• Gạch lát sân vườn</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('tbvs-sen-voi')" class="hover:text-amber-300 transition">• Thiết bị vệ sinh</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('tbvs-sen-voi')" class="hover:text-amber-300 transition">• Sen vòi cao cấp</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('son-nuoc')" class="hover:text-amber-300 transition">• Sơn nước nội ngoại thất</a></li>
            <li><a href="#san-pham-chinh" onclick="selectCategory('gach-trang-tri')" class="hover:text-amber-300 transition">• Gạch trang trí & Tranh đá</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
        <div class="lg:col-span-3 space-y-2.5">
          <h4 class="text-sm font-bold text-white uppercase tracking-wider border-b border-white/15 pb-2">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">• Chính sách báo giá sỉ công trình</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">• Chính sách giao – nhận hàng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">• Chính sách bảo hành chính hãng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">• Chính sách đổi/trả hàng linh hoạt</a></li>
            <li><a href="#lien-he-map" class="hover:text-amber-300 transition">• Chỉ đường đến Showroom</a></li>
          </ul>
        </div>

      </div>
    </div>

    <!-- Dòng bản quyền dưới cùng -->
    <div class="bg-slate-950 py-3 text-center text-xs text-slate-400 border-t border-white/10">
      <div class="flatsome-container flex flex-col sm:flex-row items-center justify-between gap-2">
        <p>© Bản quyền thuộc về <strong class="text-white">Gạch Men & TBVS Hoàng Hảo (hoanghao.com)</strong>.</p>
        <p>Địa chỉ: 681 Nguyễn Lương Bằng, P. Hải Vân, TP. Đà Nẵng • SĐT: 0934 940 340</p>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền
  ====================================================================== -->
  <div class="fixed bottom-3 right-3 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a
      href="https://www.facebook.com/gachmenhoanghao"
      target="_blank"
      rel="noopener"
      aria-label="Chat Facebook Fanpage"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <i class="fa-brands fa-facebook-f text-sm sm:text-base w-4 text-center"></i>
      <span class="text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a
      href="https://zalo.me/0934940340"
      target="_blank"
      rel="noopener"
      aria-label="Chat Zalo 0934 940 340"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <span class="font-extrabold text-xs bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
      <span class="text-xs font-bold pr-1">0934.940.340</span>
    </a>

    <!-- Nút Gọi Hotline nổi bật -->
    <a
      href="tel:0934940340"
      aria-label="Gọi Hotline 0934 940 340"
      class="pulse-btn flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition"
    >
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs sm:text-sm font-extrabold">0934 940 340</span>
    </a>

  </div>

  <!-- =====================================================================
       JAVASCRIPT QUẢN LÝ DỮ LIỆU 19 ẢNH SẢN PHẨM THỰC TẾ, SLIDER & BỘ LỌC
  ====================================================================== -->
  <script>
    // Danh sách 19 sản phẩm thực tế lấy trực tiếp từ 19 file Google Drive của Hoàng Hảo
    const productsData = [
      {
        id: 1,
        driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
        name: 'Gạch Lát Nền Vân Đá Bóng Kiếng 80x80 Hoàng Hảo HH-801',
        category: 'gach-lat-nen',
        categoryLabel: 'Gạch lát nền',
        oldPrice: '310.000₫/m²',
        salePrice: '245.000₫/m²',
        discount: '-21%',
        desc: 'Xương đá Porcelain cứng chắc, bề mặt men bóng kiếng chống bám bẩn, phù hợp lát nền phòng khách nhà phố và biệt thự.'
      },
      {
        id: 2,
        driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
        name: 'Gạch Lát Nền Khổ Lớn Vân Mây 80x80 Cao Cấp HH-802',
        category: 'gach-lat-nen',
        categoryLabel: 'Gạch lát nền',
        oldPrice: '325.000₫/m²',
        salePrice: '260.000₫/m²',
        discount: '-20%',
        desc: 'Họa tiết vân đá tự nhiên sang trọng, độ phẳng cao, chống thấm nước tuyệt đối.'
      },
      {
        id: 3,
        driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
        name: 'Gạch Lát Nền Porcelain Vân Đá Cẩm Thạch 60x60 HH-601',
        category: 'gach-lat-nen',
        categoryLabel: 'Gạch lát nền',
        oldPrice: '230.000₫/m²',
        salePrice: '185.000₫/m²',
        discount: '-20%',
        desc: 'Kích thước chuẩn 60x60cm dễ phối nội thất, chịu lực tốt, bền màu theo thời gian.'
      },
      {
        id: 4,
        driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
        name: 'Gạch Ốp Tường Vân Đá Hiện Đại 30x60 Hoàng Hảo HH-3601',
        category: 'gach-op-tuong',
        categoryLabel: 'Gạch ốp tường',
        oldPrice: '210.000₫/m²',
        salePrice: '168.000₫/m²',
        discount: '-20%',
        desc: 'Gạch ốp tường phòng khách, hành lang và phòng tắm, bề mặt láng mịn dễ lau chùi.'
      },
      {
        id: 5,
        driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
        name: 'Gạch Ốp Lát Khổ Lớn 60x120 Vân Đá Ý Sang Trọng HH-612',
        category: 'gach-op-tuong',
        categoryLabel: 'Gạch ốp tường',
        oldPrice: '450.000₫/m²',
        salePrice: '360.000₫/m²',
        discount: '-20%',
        desc: 'Dòng gạch khổ lớn 60x120 tạo không gian liền mạch, đẳng cấp cho mặt tiền và phòng khách.'
      },
      {
        id: 6,
        driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
        name: 'Gạch Giả Gỗ Tự Nhiên Chống Trầy Xước Hoàng Hảo HH-G01',
        category: 'gach-gia-go',
        categoryLabel: 'Gạch giả gỗ',
        oldPrice: '240.000₫/m²',
        salePrice: '195.000₫/m²',
        discount: '-19%',
        desc: 'Tông màu gỗ ấm cúng, không cong vênh hay mối mọt, thích hợp lát phòng ngủ và phòng thờ.'
      },
      {
        id: 7,
        driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
        name: 'Gạch Lát Sân Vườn Chống Trơn Ngoại Thất 50x50 HH-SV01',
        category: 'gach-san-vuon',
        categoryLabel: 'Gạch lát sân vườn',
        oldPrice: '195.000₫/m²',
        salePrice: '155.000₫/m²',
        discount: '-21%',
        desc: 'Bề mặt định hình chống trơn trượt khi trời mưa, chịu lực xe ô tô đậu đỗ ngoài sân.'
      },
      {
        id: 8,
        driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
        name: 'Gạch Lát Sân Vườn Giả Đá Tự Nhiên Bền Đẹp HH-SV02',
        category: 'gach-san-vuon',
        categoryLabel: 'Gạch lát sân vườn',
        oldPrice: '205.000₫/m²',
        salePrice: '162.000₫/m²',
        discount: '-21%',
        desc: 'Chống rêu mốc vượt trội, tạo điểm nhấn sân vườn, ban công và sân thượng.'
      },
      {
        id: 9,
        driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
        name: 'Bồn Cầu Một Khối Men Nano Kháng Khuẩn Cao Cấp HH-BC01',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '4.500.000₫',
        salePrice: '3.350.000₫',
        discount: '-26%',
        desc: 'Hệ thống xả xoáy siêu mạnh, êm ái, nắp đóng êm, men sứ trắng sáng bảo hành dài hạn.'
      },
      {
        id: 10,
        driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
        name: 'Bộ Sen Cây Tắm Đứng Nóng Lạnh Inox 304 Cao Cấp HH-SC01',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '3.200.000₫',
        salePrice: '2.390.000₫',
        discount: '-25%',
        desc: 'Sen cây tắm bát lớn tỏa nước êm, chất liệu chống gỉ sét, thiết kế sang trọng hiện đại.'
      },
      {
        id: 11,
        driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
        name: 'Bộ Tủ Chậu Rửa Mặt Lavabo Kèm Gương Phòng Tắm HH-LV01',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '3.800.000₫',
        salePrice: '2.890.000₫',
        discount: '-24%',
        desc: 'Chậu sứ đặt bàn chống bám bẩn kết hợp tủ lavabo chống nước tuyệt đối.'
      },
      {
        id: 12,
        driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
        name: 'Chậu Rửa Lavabo Đặt Bàn & Vòi Nóng Lạnh Đồng Thau HH-LV02',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '2.150.000₫',
        salePrice: '1.650.000₫',
        discount: '-23%',
        desc: 'Kiểu dáng tinh tế, lòng chậu sâu chống bắn nước, phù hợp mọi không gian phòng tắm.'
      },
      {
        id: 13,
        driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
        name: 'Combo Thiết Bị Vệ Sinh & Phụ Kiện Phòng Tắm Đồng Bộ HH-CB01',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '6.900.000₫',
        salePrice: '5.200.000₫',
        discount: '-25%',
        desc: 'Giải pháp trọn bộ phòng tắm tiết kiệm chi phí cho nhà mới xây tại Đà Nẵng.'
      },
      {
        id: 14,
        driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
        name: 'Vòi Rửa Chén & Sen Vòi Nóng Lạnh Chính Hãng HH-VR01',
        category: 'tbvs-sen-voi',
        categoryLabel: 'Thiết bị vệ sinh',
        oldPrice: '1.250.000₫',
        salePrice: '920.000₫',
        discount: '-26%',
        desc: 'Đầu vòi tạo bọt tiết kiệm nước, cần xoay linh hoạt 360 độ tiện lợi.'
      },
      {
        id: 15,
        driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
        name: 'Sơn Nước Ngoại Thất Cao Cấp Chống Thấm & Bền Màu HH-SN01',
        category: 'son-nuoc',
        categoryLabel: 'Sơn nước',
        oldPrice: '2.450.000₫/thùng',
        salePrice: '1.890.000₫/thùng',
        discount: '-23%',
        desc: 'Màng sơn bóng đẹp, chống tia UV, chống rêu mốc và bong tróc dưới thời tiết khắc nghiệt.'
      },
      {
        id: 16,
        driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
        name: 'Sơn Nước Nội Thất Lau Chùi Hiệu Quả Kháng Khuẩn HH-SN02',
        category: 'son-nuoc',
        categoryLabel: 'Sơn nước',
        oldPrice: '1.850.000₫/thùng',
        salePrice: '1.420.000₫/thùng',
        discount: '-23%',
        desc: 'Độ phủ cao, nhẹ mùi, an toàn sức khỏe, bảng màu đa dạng pha máy vi tính chuẩn xác.'
      },
      {
        id: 17,
        driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
        name: 'Hợp Chất Chống Thấm Đa Năng Sàn & Tường Ngoài Trời HH-CT01',
        category: 'son-nuoc',
        categoryLabel: 'Sơn nước',
        oldPrice: '1.650.000₫/thùng',
        salePrice: '1.280.000₫/thùng',
        discount: '-22%',
        desc: 'Ngăn thấm nước tối ưu cho tường đứng, sàn vệ sinh, sân thượng và ban công.'
      },
      {
        id: 18,
        driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
        name: 'Gạch Trang Trí Ốp Mặt Tiền & Điểm Nhấn Nội Thất HH-TT01',
        category: 'gach-trang-tri',
        categoryLabel: 'Gạch trang trí',
        oldPrice: '290.000₫/m²',
        salePrice: '235.000₫/m²',
        discount: '-19%',
        desc: 'Tạo chiều sâu kiến trúc cho trụ cổng, mảng tường phòng khách và quầy bar.'
      },
      {
        id: 19,
        driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
        name: 'Gạch Bông & Tranh Đá Trang Trí Nghệ Thuật Cao Cấp HH-TT02',
        category: 'gach-trang-tri',
        categoryLabel: 'Gạch trang trí',
        oldPrice: '340.000₫/m²',
        salePrice: '275.000₫/m²',
        discount: '-19%',
        desc: 'Hoa văn sắc nét, men matt mịn sang trọng, tô điểm không gian sống độc đáo.'
      }
    ];

    // Hàm tạo thẻ HTML sản phẩm chuẩn Flatsome:
    // - % giảm giá góc trên bên trái
    // - Tên sản phẩm hiển thị đầy đủ không bị tràn hay thiếu chữ
    function createProductCardHTML(product) {
      return `
        <div class="group bg-white rounded-lg border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col justify-between overflow-hidden">
          <div>
            <!-- Khung ảnh vuông + Badge % giảm giá góc trên bên trái giống Flatsome -->
            <div onclick="openProductModal(${product.id})" class="relative w-full aspect-square bg-slate-100 overflow-hidden cursor-pointer">
              <span class="absolute top-2 left-2 z-10 bg-brand-accent text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded shadow-xs">
                ${product.discount}
              </span>
              <img
                src="https://drive.google.com/thumbnail?id=${product.driveId}&sz=w700"
                data-drive-id="${product.driveId}"
                onerror="handleDriveImgError(this, '${product.categoryLabel}')"
                alt="${product.name}"
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
              >
            </div>

            <!-- Thông tin sản phẩm: Tên sản phẩm tự xuống dòng đầy đủ, không cắt chữ -->
            <div class="p-2.5 sm:p-3">
              <span class="block text-[10px] sm:text-[11px] text-slate-400 font-medium uppercase tracking-wide mb-0.5">
                ${product.categoryLabel}
              </span>
              <h3 onclick="openProductModal(${product.id})" class="text-xs sm:text-[13px] md:text-sm font-semibold text-slate-800 group-hover:text-brand-primary leading-snug break-words cursor-pointer">
                ${product.name}
              </h3>
            </div>
          </div>

          <!-- Giá gốc gạch ngang + Giá giảm + Nút đặt hàng/báo giá -->
          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100">
            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
              <span class="text-xs sm:text-sm font-extrabold text-brand-accent">
                ${product.salePrice}
              </span>
              <del class="text-[11px] sm:text-xs text-slate-400">
                ${product.oldPrice}
              </del>
            </div>
            <button
              onclick="openProductModal(${product.id})"
              class="w-full py-1.5 px-2 rounded bg-slate-100 group-hover:bg-brand-primary text-slate-700 group-hover:text-white text-[11px] sm:text-xs font-semibold transition cursor-pointer"
            >
              Xem & Nhận Báo Giá
            </button>
          </div>
        </div>
      `;
    }

    // Render danh sách sản phẩm chính và các khối chuyên đề
    function renderAllGrids(filterCat = 'all', searchKeyword = '') {
      const mainGrid = document.getElementById('productGrid');
      const kw = searchKeyword.trim().toLowerCase();

      const filtered = productsData.filter(item => {
        const matchCat = (filterCat === 'all') || (item.category === filterCat);
        const matchKw = !kw || item.name.toLowerCase().includes(kw) || item.categoryLabel.toLowerCase().includes(kw);
        return matchCat && matchKw;
      });

      if (filtered.length === 0) {
        mainGrid.innerHTML = `
          <div class="col-span-full py-8 text-center text-slate-500 text-sm">
            Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi <strong>0934 940 340</strong> để nhận mẫu trực tiếp qua Zalo!
          </div>
        `;
      } else {
        mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');
      }

      // Render khối Gạch Ốp Lát bán chạy
      const tileGrid = document.getElementById('tileHighlightGrid');
      if (tileGrid) {
        const tiles = productsData.filter(p =>
          ['gach-lat-nen', 'gach-op-tuong', 'gach-gia-go', 'gach-san-vuon', 'gach-trang-tri'].includes(p.category)
        );
        tileGrid.innerHTML = tiles.slice(0, 10).map(createProductCardHTML).join('');
      }

      // Render khối Sen Vòi, Thiết Bị Vệ Sinh & Sơn Nước
      const sanitaryGrid = document.getElementById('sanitaryAndPaintGrid');
      if (sanitaryGrid) {
        const sanitaryAndPaint = productsData.filter(p =>
          ['tbvs-sen-voi', 'son-nuoc'].includes(p.category)
        );
        sanitaryGrid.innerHTML = sanitaryAndPaint.map(createProductCardHTML).join('');
      }
    }

    // Chuyển danh mục sản phẩm
    let activeCategory = 'all';
    function selectCategory(cat) {
      activeCategory = cat;
      const buttons = document.querySelectorAll('.cat-filter-btn');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-cat-btn') === cat) {
          btn.className = 'cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-brand-primary text-white whitespace-nowrap transition';
        } else {
          btn.className = 'cat-filter-btn px-2.5 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition';
        }
      });
      renderAllGrids(cat, '');
    }

    // Tìm kiếm sản phẩm
    function filterProductsBySearch(val) {
      renderAllGrids(activeCategory, val);
    }

    // Quản lý Modal xem chi tiết sản phẩm
    let selectedModalProduct = null;
    function openProductModal(id) {
      const product = productsData.find(p => p.id === id);
      if (!product) return;
      selectedModalProduct = product;

      document.getElementById('modalTitle').textContent = product.name;
      document.getElementById('modalCategory').textContent = product.categoryLabel;
      document.getElementById('modalName').textContent = product.name;
      document.getElementById('modalSalePrice').textContent = product.salePrice;
      document.getElementById('modalOldPrice').textContent = product.oldPrice;
      document.getElementById('modalDiscountBadge').textContent = product.discount;
      document.getElementById('modalDesc').textContent = product.desc;

      const modalImg = document.getElementById('modalImg');
      modalImg.setAttribute('data-drive-id', product.driveId);
      modalImg.setAttribute('data-fallback-step', '0');
      modalImg.src = 'https://drive.google.com/thumbnail?id=' + product.driveId + '&sz=w1000';
      modalImg.onerror = function() {
        handleDriveImgError(this, product.categoryLabel);
      };

      const modal = document.getElementById('productModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function selectProductForQuote() {
      if (selectedModalProduct) {
        const noteInput = document.getElementById('qNote');
        noteInput.value = 'Tôi cần tư vấn & báo giá mẫu: ' + selectedModalProduct.name + ' (' + selectedModalProduct.salePrice + ')';
      }
      closeProductModal();
      document.getElementById('bao-gia').scrollIntoView({ behavior: 'smooth' });
      document.getElementById('qName').focus();
    }

    // Xử lý gửi Form Báo Giá (Không dùng alert)
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;
      const msgBox = document.getElementById('quoteSuccessMsg');

      msgBox.innerHTML = `
        <strong><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá của ${name}!</strong><br>
        Bộ phận kinh doanh <strong>Gạch Men & TBVS Hoàng Hảo</strong> sẽ liên hệ số điện thoại/Zalo <strong>${phone}</strong> đối với hạng mục <em>"${category}"</em> trong ít phút tới. Hotline hỗ trợ tức thì: <strong>0934 940 340</strong>.
      `;
      msgBox.classList.remove('hidden');
      document.getElementById('quoteRequestForm').reset();
    }

    // Quản lý Menu & Tìm kiếm trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      drawer.classList.toggle('hidden');
    }

    function toggleMobileSearch() {
      const bar = document.getElementById('mobileSearchBar');
      bar.classList.toggle('hidden');
      if (!bar.classList.contains('hidden')) {
        document.getElementById('mobileSearchInput').focus();
      }
    }

    // Quản lý 2 Banner tự trượt chuyên nghiệp
    let currentBannerIndex = 0;
    const totalBanners = 2;
    let bannerInterval = null;

    function showBanner(index) {
      currentBannerIndex = (index + totalBanners) % totalBanners;
      for (let i = 0; i < totalBanners; i++) {
        const slide = document.getElementById('bannerSlide' + i);
        const dot = document.getElementById('bannerDot' + i);
        if (i === currentBannerIndex) {
          slide.classList.remove('opacity-0', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
          dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0');
          dot.className = 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
        }
      }
    }

    function nextBanner() {
      showBanner(currentBannerIndex + 1);
      resetBannerTimer();
    }

    function prevBanner() {
      showBanner(currentBannerIndex - 1);
      resetBannerTimer();
    }

    function goToBanner(index) {
      showBanner(index);
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        showBanner(currentBannerIndex + 1);
      }, 5000);
    }

    // Khởi chạy khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderAllGrids('all', '');
      resetBannerTimer();
    });
  </script>
</body>
</html>
