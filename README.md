<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nhôm Kính Anh Linh - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng | nhomkinhanhlinh.com</title>
  <meta name="description" content="Nhôm kính Anh Linh Đà Nẵng chuyên thi công cửa nhôm Xingfa nhập khẩu chính hãng, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính tại 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng. Hotline: 0967.168.479.">

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ đường link website -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://nhomkinhanhlinh.com/">
  <meta property="og:title" content="Nhôm Kính Anh Linh - Cửa Nhôm Xingfa Chính Hãng Đà Nẵng">
  <meta property="og:description" content="Thiết kế, gia công, lắp đặt Cửa Nhôm Xingfa, Cửa Kính Cường Lực, Cầu Thang Kính, Phòng Tắm Kính uy tín tại Đà Nẵng. Hotline: 0967.168.479">
  <meta property="og:image" content="https://nhomkinhanhlinh.com/wp-content/uploads/logo-nhom-kinh-anh-linh-thumb.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://nhomkinhanhlinh.com/wp-content/uploads/logo-nhom-kinh-anh-linh-thumb.png">

  <!-- Favicon SVG đồng bộ logo -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B3B6B'/%3E%3Cpath d='M16 46L28 16h8l12 30h-7l-2.6-7H25.6L23 46h-7zm12.2-13h7.6L32 23.2 28.2 33z' fill='%23FFFFFF'/%3E%3Crect x='14' y='49' width='36' height='4' rx='2' fill='%23E59A00'/%3E%3C/svg%3E">

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#0A315A',     /* Xanh navy đậm chủ đạo từ logo */
              primary: '#0F4C81',  /* Xanh dương kiến trúc chuẩn logo */
              light: '#1A6CB3',    /* Xanh dương sáng nhấn hover */
              soft: '#EEF5FC',     /* Nền xanh nhạt sạch sẽ */
              gold: '#E59A00',     /* Vàng kim nhấn logo & giảm giá */
              goldDark: '#C48100',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo Box Sizing & chống tràn ngang tuyệt đối trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Container chuẩn 95% màn hình trên máy tính, cân giữa tuyệt đối */
    .ux-container {
      width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .ux-container {
        padding-left: 16px;
        padding-right: 16px;
      }
    }

    @media (min-width: 1024px) {
      .ux-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Dropdown menu mượt mà theo chuẩn Flatsome */
    .nav-dropdown-wrap {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      pointer-events: none;
    }
    .nav-dropdown-wrap:hover .nav-dropdown-menu,
    .nav-dropdown-wrap:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
      pointer-events: auto;
    }

    /* Banner 2 slide bằng kích thước tuyệt đối bằng CSS Grid Stack */
    .banner-grid-stack {
      display: grid;
      grid-template-columns: 1fr;
    }
    .banner-slide-item {
      grid-area: 1 / 1;
      transition: opacity 0.65s ease, visibility 0.65s ease;
    }
    .banner-slide-item.is-active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }
    .banner-slide-item.is-hidden {
      opacity: 0;
      visibility: hidden;
      z-index: 1;
      pointer-events: none;
    }

    /* Hiệu ứng sóng nhẹ cho nút Hotline nổi bật */
    @keyframes pulseRing {
      0% { transform: scale(1); opacity: 0.65; }
      100% { transform: scale(1.45); opacity: 0; }
    }
    .hotline-pulse::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background-color: #DC2626;
      z-index: -1;
      animation: pulseRing 1.8s cubic-bezier(0.215, 0.61, 0.355, 1) infinite;
    }

    /* Gạch chân tiêu đề chuẩn Flatsome Section Title */
    .flatsome-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-title::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      border-radius: 999px;
      background: linear-gradient(90deg, #0F4C81, #E59A00);
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- UX BUILDER: TOP BAR (Thông tin địa chỉ, giờ làm việc - không thanh edit) -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
    <div class="ux-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
          <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Tư vấn & thi công 24/7</span>
        </span>
      </div>
      <div class="flex items-center gap-4">
        <span class="hidden md:inline text-slate-200">Website: <strong class="text-white font-semibold">nhomkinhanhlinh.com</strong></span>
        <span class="inline-flex items-center gap-1 text-brand-gold font-semibold">
          <span>Hotline: 0967.168.479</span>
        </span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: HEADER & MAIN NAVIGATION (Gọn, 1 hàng trên PC, không nút gọi) -->
  <!-- ===================================================================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="ux-container">
      <div class="flex items-center justify-between gap-2 py-2.5">
        <!-- Logo Nhôm Kính Anh Linh (Thiết kế chuyên nghiệp, gọn nhỏ) -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Trang chủ Nhôm kính Anh Linh">
          <!-- Biểu tượng SVG khung cửa nhôm & kính sắc nét -->
          <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0 transition-transform duration-200 group-hover:scale-105" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="64" height="64" rx="12" fill="#0A315A"/>
            <!-- Khung nhôm kiến trúc -->
            <rect x="8" y="8" width="48" height="48" rx="7" stroke="#E59A00" stroke-width="2.5"/>
            <!-- Đường ánh sáng kính cường lực -->
            <path d="M16 47L27.5 16H34L45.5 47H39.2L36.7 39.8H24.8L22.3 47H16ZM26.6 34.8H34.9L30.75 22.8L26.6 34.8Z" fill="#FFFFFF"/>
            <!-- Điểm nhấn chữ L góc dưới -->
            <path d="M44 22H49V47H44V22Z" fill="#E59A00"/>
            <path d="M15 51H49V53.5H15V51Z" fill="#7CC0F5" opacity="0.85"/>
          </svg>
          <div class="leading-tight">
            <div class="text-sm sm:text-base font-extrabold tracking-tight text-brand-dark uppercase">NHÔM KÍNH ANH LINH</div>
            <div class="text-[10px] font-semibold tracking-wider text-brand-gold uppercase">nhomkinhanhlinh.com</div>
          </div>
        </a>

        <!-- Desktop Navigation Menu (Tất cả nằm gọn trên 1 hàng, không bao giờ xuống dòng tên danh mục) -->
        <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-0.5 xl:gap-1" aria-label="Danh mục chính">
          <a href="#trang-chu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-brand-primary bg-brand-soft transition-colors">
            Trang chủ
          </a>
          <a href="#gioi-thieu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Giới thiệu
          </a>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <div class="nav-dropdown-wrap">
            <a href="#san-pham-xingfa" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-56 z-50">
              <div class="bg-white rounded-xl shadow-xl border border-slate-200 py-1.5 overflow-hidden">
                <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa 1 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa 2 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa 3 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa 4 cánh</a>
                <a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa 5 cánh</a>
              </div>
            </div>
          </div>

          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa kính cường lực')" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Cửa kính cường lực
          </a>

          <!-- Dropdown: Sản phẩm -->
          <div class="nav-dropdown-wrap">
            <a href="#danh-muc-san-pham" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
              <span>Sản phẩm</span>
              <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-52 z-50">
              <div class="bg-white rounded-xl shadow-xl border border-slate-200 py-1.5 overflow-hidden">
                <a href="#san-pham-xingfa" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhôm xingfa</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa nhựa lõi thép')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa nhựa lõi thép</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa kính tự động')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cửa kính tự động</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cầu thang kính')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Cầu thang kính</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Kính ốp bếp')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Kính ốp bếp</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Phòng tắm kính')" class="block whitespace-nowrap px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">Phòng tắm kính</a>
              </div>
            </div>
          </div>

          <a href="#cong-trinh" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Công trình
          </a>
          <a href="#bao-gia" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Báo giá
          </a>
          <a href="#tin-tuc" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Tin tức
          </a>
          <a href="#lien-he" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-lg text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary hover:bg-brand-soft transition-colors">
            Liên hệ
          </a>
        </nav>

        <!-- Nút mở Menu Mobile (Không đặt nút gọi ngay trên header để tránh tràn viền) -->
        <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-xl bg-brand-soft text-brand-dark hover:bg-brand-primary hover:text-white transition-colors" aria-label="Mở menu danh mục">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </div>
  </header>

  <!-- Mobile Navigation Drawer (Tối ưu xem danh mục trên điện thoại) -->
  <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 bottom-0 w-[82%] max-w-[320px] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
    <div class="flex items-center justify-between px-4 py-3.5 bg-brand-dark text-white">
      <div class="font-bold text-sm tracking-wide uppercase">Danh mục Nhôm kính Anh Linh</div>
      <button id="closeMobileDrawer" type="button" class="p-1.5 rounded-lg hover:bg-white/15" aria-label="Đóng menu">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto py-2 px-3 space-y-1 text-sm">
      <a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-brand-primary bg-brand-soft">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Giới thiệu</a>

      <!-- Accordion: Cửa nhôm xingfa -->
      <div class="rounded-lg border border-slate-100">
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-700 hover:bg-brand-soft rounded-lg">
          <span>Cửa nhôm xingfa</span>
          <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="mobile-accordion-content hidden pl-4 pr-2 pb-2 space-y-1 text-[13px]">
          <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa kính cường lực')" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Cửa kính cường lực</a>

      <!-- Accordion: Sản phẩm -->
      <div class="rounded-lg border border-slate-100">
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-700 hover:bg-brand-soft rounded-lg">
          <span>Sản phẩm</span>
          <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="mobile-accordion-content hidden pl-4 pr-2 pb-2 space-y-1 text-[13px]">
          <a href="#san-pham-xingfa" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa nhựa lõi thép')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa kính tự động')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cửa kính tự động</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cầu thang kính')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Cầu thang kính</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Kính ốp bếp')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Kính ốp bếp</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('Phòng tắm kính')" class="mobile-nav-link block py-1.5 px-2.5 rounded-md text-slate-600 hover:bg-brand-soft hover:text-brand-primary">+ Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Công trình</a>
      <a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Tin tức</a>
      <a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg font-semibold text-slate-700 hover:bg-brand-soft">Liên hệ</a>
    </div>
    <div class="p-4 border-t border-slate-100 bg-slate-50 text-xs text-slate-600 space-y-1">
      <p class="font-semibold text-brand-dark">483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</p>
      <p>Hotline: <a href="tel:0967168479" class="font-bold text-brand-primary">0967.168.479</a></p>
    </div>
  </aside>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: HERO BANNER SLIDER (2 Banner tự trượt kích thước bằng nhau, chữ nằm trọn & cách xa viền) -->
  <!-- ===================================================================== -->
  <section id="trang-chu" class="py-3 sm:py-5 bg-slate-50">
    <div class="ux-container">
      <div id="heroSlider" class="relative rounded-2xl overflow-hidden shadow-lg border border-slate-200 bg-brand-dark">
        <!-- Grid stack đảm bảo 2 slide LUÔN có chiều cao & chiều rộng bằng nhau tuyệt đối trên cả PC & Mobile -->
        <div class="banner-grid-stack">

          <!-- BANNER 1 -->
          <div class="banner-slide-item is-active bg-gradient-to-br from-[#082647] via-[#0F4C81] to-[#1662A3] text-white">
            <!-- Khoảng đệm lớn từ 4 viền để chữ và hình luôn nằm trọn trong banner, không bao giờ bị thiếu chữ -->
            <div class="px-8 sm:px-14 lg:px-20 py-10 sm:py-12 lg:py-16 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
              <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-brand-gold">
                  NHÔM KÍNH ANH LINH — ĐÀ NẴNG
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight text-white">
                  THI CÔNG CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                  Chuyên gia công, lắp đặt cửa nhôm Xingfa hệ 55, 63, 93 đồng bộ phụ kiện Kinlong chính hãng. Độ bền vượt trội, cách âm kín khít, bảo hành dài hạn tại Đà Nẵng.
                </p>
                <div class="pt-2 flex flex-wrap items-center gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm shadow-md transition-colors">
                    Nhận báo giá ngay
                  </a>
                  <a href="#san-pham-xingfa" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-colors">
                    Xem mẫu cửa Xingfa
                  </a>
                </div>
              </div>
              <div class="lg:col-span-5">
                <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-brand-dark/40 aspect-[16/10] w-full">
                  <img
                    src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w1000"
                    data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                    alt="Cửa nhôm Xingfa nhập khẩu Nhôm kính Anh Linh Đà Nẵng"
                    class="drive-img w-full h-full object-cover"
                    loading="eager"
                  />
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="banner-slide-item is-hidden bg-gradient-to-br from-[#0B2E52] via-[#124B78] to-[#0A315A] text-white">
            <div class="px-8 sm:px-14 lg:px-20 py-10 sm:py-12 lg:py-16 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
              <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-brand-gold">
                  GIẢI PHÁP KIẾN TRÚC HIỆN ĐẠI — NHOMKINHANHLINH.COM
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight text-white">
                  CỬA KÍNH CƯỜNG LỰC — CẦU THANG & PHÒNG TẮM KÍNH
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                  Thiết kế, khảo sát đo đạc tận nơi miễn phí cho nhà phố, biệt thự, khách sạn và resort tại Đà Nẵng. Thi công đúng tiến độ, giá xưởng cạnh tranh nhất khu vực.
                </p>
                <div class="pt-2 flex flex-wrap items-center gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm shadow-md transition-colors">
                    Xem dự án đã thi công
                  </a>
                  <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-colors">
                    Liên hệ khảo sát
                  </a>
                </div>
              </div>
              <div class="lg:col-span-5">
                <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-brand-dark/40 aspect-[16/10] w-full">
                  <img
                    src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1000"
                    data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                    alt="Công trình thi công nhôm kính khách sạn tại Đà Nẵng - Nhôm kính Anh Linh"
                    class="drive-img w-full h-full object-cover"
                    loading="eager"
                  />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Trái / Phải nằm sát mép gọn gàng -->
        <button id="prevSlide" type="button" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Banner trước">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button id="nextSlide" type="button" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Banner kế tiếp">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" data-slide="0" class="slider-dot w-7 h-2 rounded-full bg-brand-gold transition-all" aria-label="Chọn banner 1"></button>
          <button type="button" data-slide="1" class="slider-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Chọn banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: GIỚI THIỆU NHÔM KÍNH ANH LINH (Bố cục đơn giản Flatsome) -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <div class="lg:col-span-7 space-y-4">
          <h2 class="text-xl sm:text-2xl font-extrabold text-brand-dark uppercase tracking-tight">
            CÔNG TY NHÔM KÍNH ĐÀ NẴNG – NHÔM KÍNH ANH LINH
          </h2>
          <div class="w-16 h-1 bg-brand-gold rounded-full"></div>
          <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
            <strong>Nhôm Kính Anh Linh</strong> (tại 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng) là đơn vị chuyên thiết kế, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính chất lượng cao tại Đà Nẵng và khu vực Miền Trung.
          </p>
          <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
            Các dòng sản phẩm chủ lực của chúng tôi bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu</strong>, <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong>. Với phương châm <em>“Uy tín – Chất lượng – Thẩm mỹ”</em>, Nhôm Kính Anh Linh cam kết mang lại không gian sống hiện đại, bền bỉ và an toàn cho mọi công trình.
          </p>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-sm text-slate-700">
            <div class="flex items-center gap-2">
              <span class="w-2 h-2 rounded-full bg-brand-gold shrink-0"></span>
              <span>Khảo sát, tư vấn & báo giá tận nơi miễn phí</span>
            </div>
            <div class="flex items-center gap-2">
              <span class="w-2 h-2 rounded-full bg-brand-gold shrink-0"></span>
              <span>Nhôm Xingfa tem đỏ & phụ kiện chính hãng 100%</span>
            </div>
            <div class="flex items-center gap-2">
              <span class="w-2 h-2 rounded-full bg-brand-gold shrink-0"></span>
              <span>Giá trực tiếp tại xưởng, thi công đúng tiến độ</span>
            </div>
            <div class="flex items-center gap-2">
              <span class="w-2 h-2 rounded-full bg-brand-gold shrink-0"></span>
              <span>Bảo hành chính hãng dài hạn, bảo trì nhanh chóng</span>
            </div>
          </div>
        </div>

        <!-- 4 Thông số nổi bật đơn giản -->
        <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
          <div class="p-5 rounded-xl bg-brand-soft border border-brand-primary/10 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
            <div class="mt-1 text-xs sm:text-sm font-medium text-slate-600">Dự án đã hoàn thành</div>
          </div>
          <div class="p-5 rounded-xl bg-brand-soft border border-brand-primary/10 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">50+</div>
            <div class="mt-1 text-xs sm:text-sm font-medium text-slate-600">Thợ kỹ thuật kinh nghiệm</div>
          </div>
          <div class="p-5 rounded-xl bg-brand-soft border border-brand-primary/10 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
            <div class="mt-1 text-xs sm:text-sm font-medium text-slate-600">Mẫu sản phẩm đa dạng</div>
          </div>
          <div class="p-5 rounded-xl bg-brand-soft border border-brand-primary/10 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-gold">100%</div>
            <div class="mt-1 text-xs sm:text-sm font-medium text-slate-600">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: DANH MỤC SẢN PHẨM NỔI BẬT (Chữ danh mục nhỏ gọn, 2 cột Mobile, 3 cột PC) -->
  <!-- ===================================================================== -->
  <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-100">
    <div class="ux-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          DANH MỤC SẢN PHẨM NỔI BẬT
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Đầy đủ các hạng mục nhôm kính cao cấp gia công trực tiếp tại xưởng Nhôm Kính Anh Linh
        </p>
      </div>

      <!-- Grid 6 danh mục sản phẩm đúng hình ảnh thực tế -->
      <div id="categoryGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Rendered by JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG (Có giá & giảm giá % góc trái trên, 2 cột Mobile) -->
  <!-- ===================================================================== -->
  <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-white">
    <div class="ux-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Sản phẩm cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông đồng bộ phụ kiện Kinlong chính hãng
        </p>
      </div>

      <!-- Bộ lọc nhanh đơn giản -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
        <button type="button" onclick="filterProducts('all')" data-filter="all" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition-colors">
          Tất cả mẫu cửa
        </button>
        <button type="button" onclick="filterProducts('mo-quay')" data-filter="mo-quay" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">
          Cửa đi mở quay
        </button>
        <button type="button" onclick="filterProducts('xep-truot')" data-filter="xep-truot" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">
          Cửa đi xếp trượt
        </button>
        <button type="button" onclick="filterProducts('mo-hat')" data-filter="mo-hat" class="product-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft hover:text-brand-primary transition-colors">
          Cửa sổ mở hất
        </button>
      </div>

      <!-- Grid sản phẩm: 2 cột chuẩn trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Rendered by JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG (6 công trình thực tế) -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-100">
    <div class="ux-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Những công trình khách sạn, resort và nhà phố tiêu biểu do đội ngũ Nhôm Kính Anh Linh thi công
        </p>
      </div>

      <!-- Grid dự án: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Rendered by JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: BẢNG GIÁ & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
  <!-- ===================================================================== -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-white">
    <div class="ux-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          BẢNG GIÁ THAM KHẢO & YÊU CẦU BÁO GIÁ
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Để lại thông tin để kỹ thuật viên Nhôm Kính Anh Linh gọi tư vấn và báo giá chi tiết trong 15 phút
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        <!-- Bảng báo giá nhanh -->
        <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="bg-brand-dark text-white px-5 py-3.5 font-bold text-sm sm:text-base">
            Bảng giá thi công nhôm kính tham khảo tại Đà Nẵng
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-soft text-brand-dark border-b border-slate-200">
                  <th class="py-3 px-4 font-bold">Hạng mục sản phẩm</th>
                  <th class="py-3 px-4 font-bold">Quy cách tiêu chuẩn</th>
                  <th class="py-3 px-4 font-bold text-right">Đơn giá (VNĐ)</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-100">
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi mở quay nhôm Xingfa (1-4 cánh)</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 55 dày 2.0mm, kính 8mm</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">1.990.000 đ/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi xếp trượt nhôm Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 63 nhập khẩu, phụ kiện Kinlong</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">2.150.000 đ/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Cửa sổ mở hất / mở quay Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 55 dày 1.4mm, kính 8mm</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">1.890.000 đ/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Cửa kính cường lực bản lề sàn</td>
                  <td class="py-3 px-4 text-slate-600">Kính cường lực 10mm - 12mm</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">750.000 đ/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Cầu thang kính / Phòng tắm kính</td>
                  <td class="py-3 px-4 text-slate-600">Kính 10mm + Phụ kiện Inox 304</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">1.250.000 đ/md</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-semibold text-slate-800">Kính ốp bếp cường lực sơn màu</td>
                  <td class="py-3 px-4 text-slate-600">Kính 8mm cường lực phun nhiệt</td>
                  <td class="py-3 px-4 text-right font-bold text-brand-primary whitespace-nowrap">850.000 đ/md</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="px-5 py-3 bg-slate-50 text-xs text-slate-500 border-t border-slate-100">
            * Đơn giá trên đã bao gồm công vận chuyển và lắp đặt hoàn thiện tại nội thành Đà Nẵng. Liên hệ <strong>0967.168.479</strong> để nhận chiết khấu cho khối lượng lớn.
          </div>
        </div>

        <!-- Form Đăng ký Nhận Báo Giá -->
        <div class="lg:col-span-5 bg-brand-soft rounded-2xl border border-brand-primary/15 p-5 sm:p-6 shadow-sm">
          <h3 class="text-base sm:text-lg font-extrabold text-brand-dark uppercase mb-1">
            Đăng ký nhận báo giá miễn phí
          </h3>
          <p class="text-xs sm:text-sm text-slate-600 mb-4">
            Điền thông tin công trình, chúng tôi sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết.
          </p>

          <form id="quoteForm" class="space-y-3.5">
            <div>
              <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
              <input id="qName" type="text" required placeholder="Nhập họ tên của anh/chị" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary">
            </div>
            <div>
              <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
              <input id="qPhone" type="tel" required placeholder="Ví dụ: 0967 168 479" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary">
            </div>
            <div>
              <label for="qService" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá</label>
              <select id="qService" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary">
                <option value="Cửa nhôm Xingfa nhập khẩu">Cửa nhôm Xingfa nhập khẩu (1 - 5 cánh / xếp trượt)</option>
                <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                <option value="Cửa kính tự động">Cửa kính tự động</option>
                <option value="Cầu thang kính">Cầu thang kính</option>
                <option value="Kính ốp bếp">Kính ốp bếp</option>
                <option value="Phòng tắm kính">Phòng tắm kính</option>
                <option value="Thi công trọn gói nhà phố / khách sạn">Thi công trọn gói nhà phố / khách sạn</option>
              </select>
            </div>
            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình & kích thước sơ bộ</label>
              <textarea id="qNote" rows="3" placeholder="Nhập địa chỉ tại Đà Nẵng hoặc kích thước cửa dự kiến..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-primary focus:border-brand-primary"></textarea>
            </div>
            <button type="submit" class="w-full py-3 px-5 rounded-xl bg-brand-primary hover:bg-brand-dark text-white font-bold text-sm shadow-md transition-colors">
              Gửi yêu cầu báo giá ngay
            </button>
          </form>

          <!-- Hộp thông báo sau khi gửi (Không dùng alert) -->
          <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: DANH MỤC BÀI VIẾT TIN TỨC NỔI BẬT TRANG CHỦ -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-100">
    <div class="ux-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          TIN TỨC & KINH NGHIỆM NHÔM KÍNH
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Chia sẻ kiến thức lựa chọn cửa nhôm Xingfa, kính cường lực bền đẹp cho ngôi nhà của bạn
        </p>
      </div>

      <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Rendered by JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: ĐỐI TÁC CỦA CHÚNG TÔI (6 ảnh đối tác thực tế) -->
  <!-- ===================================================================== -->
  <section class="py-10 bg-white border-t border-slate-100">
    <div class="ux-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div id="partnerGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Rendered by JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200">
    <div class="ux-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-title text-lg sm:text-2xl font-extrabold text-brand-dark uppercase">
          BẢN ĐỒ CHỈ ĐƯỜNG & KẾT NỐI FANPAGE
        </h2>
        <p class="mt-2.5 text-xs sm:text-sm text-slate-500">
          Xưởng gia công & Văn phòng: 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng — Hotline: 0967.168.479
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Google Map nhúng trực tiếp địa chỉ 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng -->
        <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 bg-brand-dark text-white flex items-center justify-between gap-2">
            <span class="text-xs sm:text-sm font-bold">Vị trí Nhôm Kính Anh Linh trên Google Maps</span>
            <a href="https://www.google.com/maps/search/?api=1&query=483+Nguy%E1%BB%85n+L%C6%B0%C6%A1ng+B%E1%BA%B1ng,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs text-brand-gold hover:underline font-semibold whitespace-nowrap">
              Mở chỉ đường &rarr;
            </a>
          </div>
          <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Nhôm kính Anh Linh - 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng"
              src="https://maps.google.com/maps?q=483%20Nguy%E1%BB%85n%20L%C6%B0%C6%A1ng%20B%E1%BA%B1ng,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen>
            </iframe>
          </div>
        </div>

        <!-- Khung Fanpage Facebook ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
            <div class="flex items-center gap-2 font-bold text-xs sm:text-sm">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
              <span>Fanpage Facebook Chính Thức</span>
            </div>
            <span class="text-[11px] text-white/90">Cập nhật công trình mỗi ngày</span>
          </div>

          <!-- Giao diện hộp Fanpage Facebook trực quan -->
          <div class="p-4 flex-1 flex flex-col justify-between space-y-4">
            <!-- Cover + Avatar Fanpage -->
            <div class="relative rounded-xl overflow-hidden border border-slate-200">
              <div class="h-28 bg-gradient-to-r from-brand-dark via-brand-primary to-brand-light relative">
                <img
                  src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w800"
                  data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                  alt="Ảnh bìa Fanpage Nhôm Kính Anh Linh"
                  class="drive-img w-full h-full object-cover opacity-40"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-3">
                  <div class="w-12 h-12 rounded-xl bg-brand-dark border-2 border-white shadow flex items-center justify-center shrink-0">
                    <span class="text-white font-extrabold text-base tracking-tight">AL</span>
                  </div>
                  <div class="text-white min-w-0">
                    <div class="font-bold text-sm leading-tight truncate">Nhôm Kính Anh Linh - Đà Nẵng</div>
                    <div class="text-[11px] text-slate-200">nhomkinhanhlinh.com • 0967.168.479</div>
                  </div>
                </div>
              </div>
              <div class="p-3 bg-slate-50 flex items-center justify-between gap-2 text-xs">
                <span class="text-slate-600 font-medium">Thi công Nhôm Xingfa & Kính Cường Lực</span>
                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-semibold whitespace-nowrap transition-colors">
                  Theo dõi trang
                </a>
              </div>
            </div>

            <!-- Bài đăng mới nhất mô phỏng feed Fanpage -->
            <div class="rounded-xl border border-slate-200 p-3.5 bg-white space-y-2 text-xs sm:text-[13px]">
              <div class="flex items-center justify-between text-slate-500 text-[11px]">
                <strong class="text-brand-dark">Nhôm Kính Anh Linh</strong>
                <span>483 Nguyễn Lương Bằng, Đà Nẵng</span>
              </div>
              <p class="text-slate-600 leading-relaxed">
                Hoàn thiện bàn giao hệ cửa đi mở quay 4 cánh & cửa xếp trượt nhôm Xingfa nhập khẩu tem đỏ cho công trình nhà phố tại Liên Chiểu, Đà Nẵng. Cảm ơn Quý khách hàng đã tin tưởng!
              </p>
              <div class="pt-1 flex items-center gap-2">
                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 rounded-lg bg-brand-soft hover:bg-brand-primary hover:text-white text-brand-primary font-semibold transition-colors">
                  Xem Fanpage Facebook
                </a>
                <a href="https://zalo.me/0967168479" target="_blank" rel="noopener noreferrer" class="flex-1 text-center py-2 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold transition-colors">
                  Nhắn Zalo tư vấn
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER: FOOTER (4 cột gọn gàng chuẩn Flatsome) -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6 border-t-4 border-brand-gold">
    <div class="ux-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect width="64" height="64" rx="12" fill="#0F4C81"/>
              <rect x="8" y="8" width="48" height="48" rx="7" stroke="#E59A00" stroke-width="2.5"/>
              <path d="M16 47L27.5 16H34L45.5 47H39.2L36.7 39.8H24.8L22.3 47H16ZM26.6 34.8H34.9L30.75 22.8L26.6 34.8Z" fill="#FFFFFF"/>
              <path d="M44 22H49V47H44V22Z" fill="#E59A00"/>
            </svg>
            <div>
              <div class="font-extrabold text-white text-sm uppercase">NHÔM KÍNH ANH LINH</div>
              <div class="text-[11px] text-brand-gold font-semibold">nhomkinhanhlinh.com</div>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-slate-300">
            Chuyên sản xuất, gia công và lắp đặt cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, phòng tắm kính tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-xs text-slate-200">
            <li><strong>Địa chỉ:</strong> 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</li>
            <li><strong>Hotline / Zalo:</strong> <a href="tel:0967168479" class="text-brand-gold font-bold hover:underline">0967.168.479</a></li>
            <li><strong>Website:</strong> nhomkinhanhlinh.com</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15">Cửa nhôm Xingfa</h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa 5 cánh / Xếp trượt</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15">Danh mục sản phẩm</h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa nhôm xingfa')" class="hover:text-brand-gold transition-colors">Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa nhựa lõi thép')" class="hover:text-brand-gold transition-colors">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cửa kính tự động')" class="hover:text-brand-gold transition-colors">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Cầu thang kính')" class="hover:text-brand-gold transition-colors">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Kính ốp bếp')" class="hover:text-brand-gold transition-colors">Kính ốp bếp màu cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('Phòng tắm kính')" class="hover:text-brand-gold transition-colors">Phòng tắm kính cao cấp</a></li>
          </ul>
        </div>

        <!-- Cột 4: Thông tin hỗ trợ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15">Cam kết dịch vụ</h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li>Khảo sát đo đạc thực tế miễn phí tại Đà Nẵng</li>
            <li>Báo giá rõ ràng, minh bạch, không phát sinh</li>
            <li>Sử dụng phụ kiện đồng bộ chính hãng 100%</li>
            <li>Bảo hành kỹ thuật tận nơi nhanh chóng</li>
            <li class="pt-1 text-brand-gold font-semibold">Giờ làm việc: 07:30 – 20:00 (Cả T7 & CN)</li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright 2026 © Bản quyền thuộc về <strong class="text-white">Nhôm Kính Anh Linh</strong> — nhomkinhanhlinh.com</div>
        <div>483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Tương thích PC & Mobile) -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Facebook Nhôm kính Anh Linh" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition-all">
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
      <span class="hidden sm:inline text-xs font-bold pr-0.5">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0967168479" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0967.168.479" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition-all">
      <svg class="w-5 h-5 shrink-0" viewBox="0 0 32 32" fill="none">
        <circle cx="16" cy="16" r="15" fill="white"/>
        <text x="16" y="20.5" text-anchor="middle" fill="#0068FF" font-size="11" font-weight="800" font-family="Inter, sans-serif">Zalo</text>
      </svg>
      <span class="hidden sm:inline text-xs font-bold pr-0.5">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật có hiệu ứng nhịp nhẹ -->
    <a href="tel:0967168479" aria-label="Gọi Hotline 0967.168.479" class="hotline-pulse relative flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full p-3 sm:px-4 sm:py-2.5 shadow-xl transition-all">
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0967.168.479</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM NHANH SẢN PHẨM / DỰ ÁN / BÀI VIẾT -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-slate-900/65 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-100 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-brand-dark pr-4"></h3>
        <button id="closeModalBtn" type="button" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600" aria-label="Đóng cửa sổ">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: Dữ liệu thực tế, Slider, Filter, Fallback ảnh Google Drive -->
  <!-- ===================================================================== -->
  <script>
    // =========================================================================
    // 1. DỮ LIỆU CHÍNH XÁC TỪ GOOGLE DRIVE & THÔNG TIN THỰC TẾ NGÀNH NHÔM KÍNH
    // =========================================================================

    const CATEGORIES = [
      {
        name: "Cửa nhôm Xingfa",
        driveId: "1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX",
        desc: "Hệ nhôm Xingfa nhập khẩu tem đỏ Quảng Đông hệ 55, 63, 93 dày 1.4mm - 2.0mm, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội."
      },
      {
        name: "Cửa nhựa lõi thép",
        driveId: "1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA",
        desc: "Thanh nhựa uPVC lõi thép gia cường chống cong vênh, kín khít cao, phù hợp cửa phòng ngủ, cửa vệ sinh và cửa sổ cách âm."
      },
      {
        name: "Cửa kính tự động",
        driveId: "1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ",
        desc: "Hệ cửa kính cường lực cảm biến đóng mở tự động cho khách sạn, showroom, siêu thị và văn phòng hiện đại tại Đà Nẵng."
      },
      {
        name: "Cầu thang kính",
        driveId: "1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul",
        desc: "Lan can cầu thang kính cường lực 10mm - 12mm kết hợp tay vịn gỗ hoặc inox 304 sang trọng, giúp mở rộng không gian sống."
      },
      {
        name: "Kính ốp bếp",
        driveId: "1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb",
        desc: "Kính cường lực 8mm sơn màu chịu nhiệt cao cấp, bề mặt phẳng bóng không mạch vữa, cực kỳ dễ lau chùi dầu mỡ."
      },
      {
        name: "Phòng tắm kính",
        driveId: "1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH",
        desc: "Cabin vách tắm kính cường lực 10mm bản lề inox 304 chống gỉ sét, ngăn nước hiệu quả giữ phòng tắm luôn khô ráo sạch sẽ."
      }
    ];

    const PRODUCTS = [
      {
        id: 1,
        name: "Cửa đi quay mở 1 cánh nhôm Xingfa",
        categoryKey: "mo-quay",
        wingKey: "1-canh",
        driveId: "1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm",
        originalPrice: 2350000,
        salePrice: 1990000,
        discount: 15,
        unit: "₫/m²",
        specs: "Nhôm Xingfa hệ 55 dày 2.0mm • Kính cường lực 8mm • Phụ kiện Kinlong nhập khẩu chính hãng • Bảo hành 5 năm."
      },
      {
        id: 2,
        name: "Cửa đi quay mở 2 cánh nhôm Xingfa",
        categoryKey: "mo-quay",
        wingKey: "2-canh",
        driveId: "1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb",
        originalPrice: 2400000,
        salePrice: 2050000,
        discount: 15,
        unit: "₫/m²",
        specs: "Nhôm Xingfa hệ 55 dày 2.0mm • Sơn tĩnh điện ngoài trời chống ăn mòn biển • Bản lề 3D & khóa đa điểm Kinlong."
      },
      {
        id: 3,
        name: "Cửa đi quay mở 3 cánh nhôm Xingfa",
        categoryKey: "mo-quay",
        wingKey: "3-canh",
        driveId: "17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR",
        originalPrice: 2450000,
        salePrice: 2080000,
        discount: 15,
        unit: "₫/m²",
        specs: "Thiết kế linh hoạt cho mặt tiền vừa và rộng • Thanh nhôm Xingfa Quảng Đông hệ 55 dày 2.0mm • Kín nước kín khí tuyệt đối."
      },
      {
        id: 4,
        name: "Cửa đi quay mở 4 cánh nhôm Xingfa",
        categoryKey: "mo-quay",
        wingKey: "4-canh",
        driveId: "1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-",
        originalPrice: 2500000,
        salePrice: 2100000,
        discount: 16,
        unit: "₫/m²",
        specs: "Lựa chọn số 1 cho cửa chính nhà phố & biệt thự • Khung nhôm hệ 55 dày 2.0mm • Gioăng EPDM kép cách âm tối đa."
      },
      {
        id: 5,
        name: "Cửa Nhôm Xingfa Cửa Đi Xếp Trượt",
        categoryKey: "xep-truot",
        wingKey: "xep-truot",
        driveId: "1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ",
        originalPrice: 2600000,
        salePrice: 2150000,
        discount: 17,
        unit: "₫/m²",
        specs: "Nhôm Xingfa hệ 63 xếp trượt gấp gọn (3 cánh, 4 cánh, 5 cánh, 6 cánh) • Mở rộng tối đa không gian sân vườn & ban công."
      },
      {
        id: 6,
        name: "Cửa sổ mở hất 2 cánh nhôm Xingfa",
        categoryKey: "mo-hat",
        wingKey: "2-canh",
        driveId: "11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA",
        originalPrice: 2200000,
        salePrice: 1890000,
        discount: 14,
        unit: "₫/m²",
        specs: "Nhôm Xingfa hệ 55 dày 1.4mm • Thanh chống gió định vị góc mở 45 độ an toàn khi mưa bão tại Đà Nẵng."
      }
    ];

    const PROJECTS = [
      {
        title: "DỰ ÁN KHÁCH SẠN RUBY LIGHT",
        driveId: "1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ",
        location: "Đà Nẵng",
        scope: "Thi công trọn gói hệ cửa nhôm Xingfa nhập khẩu, vách kính mặt dựng và phòng tắm kính cường lực."
      },
      {
        title: "DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”",
        driveId: "1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ",
        location: "Quảng Nam – Đà Nẵng",
        scope: "Cung cấp & lắp đặt toàn bộ hệ cửa đi xếp trượt nhôm Xingfa và cửa sổ kính hộp cách âm tiêu chuẩn 4 sao."
      },
      {
        title: "THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE",
        driveId: "1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy",
        location: "Đà Nẵng",
        scope: "Lắp đặt hệ mặt dựng nhôm kính, cửa kính tự động khu vực sảnh lễ tân và vách tắm kính cao cấp."
      },
      {
        title: "THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA",
        driveId: "1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64",
        location: "Đà Nẵng",
        scope: "Gia công thi công cửa nhôm Xingfa màu xám ghi, lan can kính ban công và cửa kính cường lực."
      },
      {
        title: "THI CÔNG DỰ ÁN KHÁCH SẠN SOHO",
        driveId: "1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt",
        location: "Đà Nẵng",
        scope: "Thi công hệ cửa nhôm kính chống ồn ven biển, vách kính cường lực chịu áp lực gió cao."
      },
      {
        title: "THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL",
        driveId: "1za_IJpAm850uulT6IuhBsk1THb3LuPuc",
        location: "Biển Mỹ Khê, Đà Nẵng",
        scope: "Thi công hoàn thiện cửa nhôm Xingfa cao cấp, vách ngăn phòng tắm kính và lan can kính cường lực 12mm."
      }
    ];

    const PARTNERS = [
      { name: "Đối tác Nhôm kính 1", driveId: "13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" },
      { name: "Đối tác Nhôm kính 2", driveId: "1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" },
      { name: "Đối tác Nhôm kính 3", driveId: "1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" },
      { name: "Đối tác Nhôm kính 4", driveId: "1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" },
      { name: "Đối tác Nhôm kính 5", driveId: "1SDcarhnX0yypmqdbawICjYBRtFnKngn-" },
      { name: "Đối tác Nhôm kính 6", driveId: "1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" }
    ];

    const NEWS_ARTICLES = [
      {
        title: "Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?",
        driveId: "1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX",
        date: "Cẩm nang chọn cửa",
        excerpt: "Khí hậu ven biển Đà Nẵng có độ ẩm và hơi muối cao. Nhôm Xingfa sơn tĩnh điện tiêu chuẩn quốc tế giúp chống oxy hóa và chịu gió bão cực tốt.",
        content: "Đà Nẵng nằm ở khu vực duyên hải Miền Trung với đặc trưng nắng nóng mùa hè và mưa bão kèm hơi muối biển. Cửa nhôm Xingfa nhập khẩu sử dụng thanh profile hợp kim nhôm 6063-T5 dày từ 1.4mm – 2.0mm, phủ lớp sơn tĩnh điện cao cấp chống ăn mòn hiệu quả. Khi kết hợp hệ gioăng cao su EPDM kín khít và keo ép góc chuyên dụng, cửa chịu được áp lực gió bão lớn và chống thấm nước mưa tuyệt đối."
      },
      {
        title: "Cửa nhôm Xingfa có tiết kiệm điện năng và cách âm tốt không?",
        driveId: "1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-",
        date: "Tư vấn kỹ thuật",
        excerpt: "Cấu trúc khoang rỗng kết hợp các đường gân gia cường và kính cường lực giúp hạn chế thất thoát nhiệt máy lạnh đáng kể.",
        content: "Nhờ cấu tạo khoang trống bên trong thanh profile nhôm cùng hệ gioăng cao su kép EPDM, cửa nhôm Xingfa hạn chế tối đa việc truyền âm và truyền nhiệt từ bên ngoài vào trong nhà. Điều này giúp không gian phòng luôn yên tĩnh, mát mẻ và giảm tới 25–30% chi phí điện năng cho điều hòa trong những ngày hè nóng bức."
      },
      {
        title: "So sánh cửa nhôm Xingfa với cửa gỗ và cửa nhựa lõi thép",
        driveId: "1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb",
        date: "Kinh nghiệm xây nhà",
        excerpt: "Nên chọn cửa nhôm Xingfa, cửa gỗ tự nhiên hay cửa nhựa lõi thép cho nhà phố? Cùng Nhôm Kính Anh Linh phân tích chi tiết ưu nhược điểm.",
        content: "So với cửa gỗ truyền thống dễ cong vênh, co ngót hoặc mối mọt khi gặp thời tiết ẩm ướt, cửa nhôm Xingfa khắc phục hoàn toàn các nhược điểm này với tuổi thọ lên tới hàng chục năm. So với cửa nhựa lõi thép, khung nhôm Xingfa có độ cứng vững cao hơn, màu sắc đa dạng (xám ghi, đen tuyền, nâu cafe, trắng sứ, vân gỗ) và thiết kế thanh mảnh sang trọng hơn."
      },
      {
        title: "Cách chọn kính ốp bếp và phòng tắm kính bền đẹp dễ vệ sinh",
        driveId: "1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb",
        date: "Nội thất kính",
        excerpt: "Bí quyết lựa chọn độ dày kính cường lực và phụ kiện inox 304 chuẩn để khu vực bếp và nhà tắm luôn sáng bóng theo thời gian.",
        content: "Đối với kính ốp bếp, nên chọn kính cường lực dày 8mm sơn màu chịu nhiệt công nghệ cao để tránh nứt vỡ khi nấu nướng và không bị bay màu. Đối với phòng tắm kính, nên dùng kính cường lực 10mm đi kèm bộ phụ kiện kẹp, bản lề và tay nắm chất liệu Inox 304 chống gỉ để vận hành êm ái suốt nhiều năm."
      }
    ];

    // =========================================================================
    // 2. HÀM XỬ LÝ LINK ẢNH GOOGLE DRIVE & FALLBACK AN TOÀN
    // =========================================================================
    function getDriveThumbUrl(id) {
      return `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
    }

    function attachDriveFallback(img) {
      if (!img || img.dataset.fallbackBound) return;
      img.dataset.fallbackBound = "true";
      img.addEventListener("error", function () {
        const step = Number(img.dataset.errStep || "0");
        const id = img.dataset.driveId;
        const altText = encodeURIComponent((img.alt || "Nhom Kinh Anh Linh").slice(0, 32));
        if (step === 0 && id) {
          img.dataset.errStep = "1";
          img.src = `https://lh3.googleusercontent.com/d/${id}=w1000`;
        } else if (step === 1) {
          img.dataset.errStep = "2";
          img.src = `https://placehold.co/600x450/0F4C81/FFFFFF?text=${altText}`;
        }
      });
    }

    function bindAllDriveImages() {
      document.querySelectorAll("img.drive-img").forEach(attachDriveFallback);
    }

    function formatVND(num) {
      return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ".");
    }

    // =========================================================================
    // 3. RENDER DANH MỤC SẢN PHẨM, SẢN PHẨM CÓ GIẢM GIÁ %, DỰ ÁN, TIN TỨC, ĐỐI TÁC
    // =========================================================================
    function renderCategories() {
      const container = document.getElementById("categoryGrid");
      container.innerHTML = CATEGORIES.map((cat) => `
        <button type="button" onclick="openCategoryDetail('${cat.name}')" class="group text-left bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveThumbUrl(cat.driveId)}"
              data-drive-id="${cat.driveId}"
              alt="${cat.name} - Nhôm kính Anh Linh Đà Nẵng"
              class="drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="px-2.5 py-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <span class="text-[12px] sm:text-[13px] font-bold text-brand-dark group-hover:text-brand-primary uppercase leading-snug">
              ${cat.name}
            </span>
          </div>
        </button>
      `).join("");
      bindAllDriveImages();
    }

    function renderProducts(filterType = "all") {
      const container = document.getElementById("productGrid");
      const filtered = PRODUCTS.filter((p) => {
        if (filterType === "all") return true;
        return p.categoryKey === filterType || p.wingKey === filterType;
      });

      container.innerHTML = filtered.map((p) => `
        <article class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary shadow-xs hover:shadow-lg transition-all flex flex-col">
          <!-- Khung ảnh sản phẩm + Giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 sm:px-2.5 sm:py-1 rounded-lg bg-red-600 text-white text-[11px] sm:text-xs font-extrabold shadow">
              -${p.discount}%
            </span>
            <img
              src="${getDriveThumbUrl(p.driveId)}"
              data-drive-id="${p.driveId}"
              alt="${p.name}"
              class="drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-300 cursor-pointer"
              onclick="openProductModal(${p.id})"
              loading="lazy"
            />
          </div>

          <!-- Nội dung sản phẩm (Tên hiển thị đầy đủ, không bị tràn hay mất chữ trên mobile) -->
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 onclick="openProductModal(${p.id})" class="cursor-pointer text-[13px] sm:text-[15px] font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                ${p.name}
              </h3>

              <!-- Giá gốc & Giá khuyến mãi -->
              <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-base font-extrabold text-red-600">
                  ${formatVND(p.salePrice)} ${p.unit}
                </span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                  ${formatVND(p.originalPrice)} ₫
                </span>
              </div>
            </div>

            <div class="mt-3 pt-2.5 border-t border-slate-100 grid grid-cols-2 gap-1.5 sm:gap-2">
              <button type="button" onclick="openProductModal(${p.id})" class="py-1.5 sm:py-2 px-2 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-[11px] sm:text-xs transition-colors">
                Xem chi tiết
              </button>
              <button type="button" onclick="selectProductForQuote('${p.name}')" class="py-1.5 sm:py-2 px-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition-colors">
                Nhận báo giá
              </button>
            </div>
          </div>
        </article>
      `).join("");
      bindAllDriveImages();
    }

    function filterProducts(filterType) {
      renderProducts(filterType);
      document.querySelectorAll(".product-filter-btn").forEach((btn) => {
        const isMatch = btn.dataset.filter === filterType || (filterType.includes("canh") && btn.dataset.filter === "mo-quay");
        btn.classList.toggle("bg-brand-primary", isMatch);
        btn.classList.toggle("text-white", isMatch);
        btn.classList.toggle("bg-slate-100", !isMatch);
        btn.classList.toggle("text-slate-700", !isMatch);
      });
    }

    function renderProjects() {
      const container = document.getElementById("projectGrid");
      container.innerHTML = PROJECTS.map((proj, idx) => `
        <article onclick="openProjectModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/11] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveThumbUrl(proj.driveId)}"
              data-drive-id="${proj.driveId}"
              alt="${proj.title}"
              class="drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-sm font-bold text-brand-dark group-hover:text-brand-primary leading-snug break-words">
              ${proj.title}
            </h3>
            <p class="mt-2 text-[11px] sm:text-xs text-slate-500">
              Địa điểm: ${proj.location}
            </p>
          </div>
        </article>
      `).join("");
      bindAllDriveImages();
    }

    function renderNews() {
      const container = document.getElementById("newsGrid");
      container.innerHTML = NEWS_ARTICLES.map((art, idx) => `
        <article onclick="openNewsModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveThumbUrl(art.driveId)}"
              data-drive-id="${art.driveId}"
              alt="${art.title}"
              class="drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] font-semibold text-brand-gold uppercase mb-1">${art.date}</div>
              <h3 class="text-sm font-bold text-brand-dark group-hover:text-brand-primary leading-snug">
                ${art.title}
              </h3>
              <p class="mt-2 text-xs text-slate-600 leading-relaxed">
                ${art.excerpt}
              </p>
            </div>
            <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-bold text-brand-primary">
              Đọc bài viết &rarr;
            </div>
          </div>
        </article>
      `).join("");
      bindAllDriveImages();
    }

    function renderPartners() {
      const container = document.getElementById("partnerGrid");
      container.innerHTML = PARTNERS.map((pt) => `
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/40 hover:shadow-sm transition-all">
          <img
            src="${getDriveThumbUrl(pt.driveId)}"
            data-drive-id="${pt.driveId}"
            alt="${pt.name}"
            class="drive-img max-h-full max-w-full object-contain"
            loading="lazy"
          />
        </div>
      `).join("");
      bindAllDriveImages();
    }

    // =========================================================================
    // 4. MODAL XEM CHI TIẾT SẢN PHẨM / DANH MỤC / DỰ ÁN / BÀI VIẾT
    // =========================================================================
    const modal = document.getElementById("detailModal");
    const modalTitle = document.getElementById("modalTitle");
    const modalBody = document.getElementById("modalBody");

    function showModal(title, htmlContent) {
      modalTitle.textContent = title;
      modalBody.innerHTML = htmlContent;
      modal.classList.remove("hidden");
      modal.classList.add("flex");
      document.body.style.overflow = "hidden";
      bindAllDriveImages();
    }

    function closeModal() {
      modal.classList.add("hidden");
      modal.classList.remove("flex");
      document.body.style.overflow = "";
    }

    document.getElementById("closeModalBtn").addEventListener("click", closeModal);
    modal.addEventListener("click", (e) => {
      if (e.target === modal) closeModal();
    });

    function openProductModal(productId) {
      const p = PRODUCTS.find((item) => item.id === productId);
      if (!p) return;
      showModal(p.name, `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
            <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-lg bg-red-600 text-white text-xs font-extrabold">-${p.discount}%</span>
            <img src="${getDriveThumbUrl(p.driveId)}" data-drive-id="${p.driveId}" alt="${p.name}" class="drive-img w-full h-56 object-cover"/>
          </div>
          <div class="space-y-3">
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-red-600">${formatVND(p.salePrice)} ${p.unit}</span>
              <span class="text-sm text-slate-400 line-through">${formatVND(p.originalPrice)} ₫</span>
            </div>
            <p class="text-sm text-slate-600 leading-relaxed">${p.specs}</p>
            <div class="p-3 rounded-xl bg-brand-soft text-xs text-brand-dark space-y-1">
              <div><strong>Xưởng thi công:</strong> 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng</div>
              <div><strong>Hotline tư vấn:</strong> 0967.168.479</div>
            </div>
            <div class="flex gap-2 pt-1">
              <button type="button" onclick="closeModal(); selectProductForQuote('${p.name}')" class="flex-1 py-2.5 px-4 rounded-xl bg-brand-primary hover:bg-brand-dark text-white font-bold text-xs sm:text-sm">
                Yêu cầu báo giá mẫu này
              </button>
              <a href="tel:0967168479" class="py-2.5 px-4 rounded-xl bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm">
                Gọi ngay
              </a>
            </div>
          </div>
        </div>
      `);
    }

    function openCategoryDetail(categoryName) {
      const found = CATEGORIES.find((c) => c.name.toLowerCase() === categoryName.toLowerCase());
      const desc = found
        ? found.desc
        : "Thi công trọn gói kính cường lực 10mm – 12mm chính hãng, phụ kiện inox 304 đồng bộ, đo đạc miễn phí tận nơi tại Đà Nẵng.";
      const driveId = found ? found.driveId : "1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX";

      showModal(`Danh mục: ${categoryName}`, `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
            <img src="${getDriveThumbUrl(driveId)}" data-drive-id="${driveId}" alt="${categoryName}" class="drive-img w-full h-full object-cover"/>
          </div>
          <p class="text-sm text-slate-700 leading-relaxed">${desc}</p>
          <div class="flex flex-wrap gap-2.5">
            <button type="button" onclick="closeModal(); selectProductForQuote('${categoryName}')" class="px-5 py-2.5 rounded-xl bg-brand-primary hover:bg-brand-dark text-white font-bold text-sm">
              Nhận báo giá ${categoryName}
            </button>
            <a href="https://zalo.me/0967168479" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-xl bg-[#0068FF] hover:bg-blue-700 text-white font-bold text-sm">
              Tư vấn qua Zalo
            </a>
          </div>
        </div>
      `);
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      showModal(proj.title, `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <img src="${getDriveThumbUrl(proj.driveId)}" data-drive-id="${proj.driveId}" alt="${proj.title}" class="drive-img w-full max-h-[380px] object-cover"/>
          </div>
          <div class="space-y-2 text-sm text-slate-700">
            <p><strong>Địa điểm thi công:</strong> ${proj.location}</p>
            <p><strong>Hạng mục thực hiện:</strong> ${proj.scope}</p>
            <p><strong>Đơn vị thi công:</strong> Nhôm Kính Anh Linh – 483 Nguyễn Lương Bằng, Liên Chiểu, Đà Nẵng.</p>
          </div>
          <button type="button" onclick="closeModal(); selectProductForQuote('Tư vấn thi công tương tự ${proj.title}')" class="px-5 py-2.5 rounded-xl bg-brand-primary hover:bg-brand-dark text-white font-bold text-sm">
            Liên hệ tư vấn dự án
          </button>
        </div>
      `);
    }

    function openNewsModal(index) {
      const art = NEWS_ARTICLES[index];
      if (!art) return;
      showModal(art.title, `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
            <img src="${getDriveThumbUrl(art.driveId)}" data-drive-id="${art.driveId}" alt="${art.title}" class="drive-img w-full h-full object-cover"/>
          </div>
          <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-3.5 rounded-xl bg-brand-soft text-xs sm:text-sm text-brand-dark">
            Cần tư vấn đo đạc thực tế? Gọi ngay <strong>Nhôm Kính Anh Linh – 0967.168.479</strong> để được hỗ trợ miễn phí!
          </div>
        </div>
      `);
    }

    function selectProductForQuote(itemName) {
      const noteField = document.getElementById("qNote");
      const baoGiaSection = document.getElementById("bao-gia");
      if (noteField) {
        noteField.value = `Tôi cần nhận báo giá chi tiết cho: ${itemName}`;
      }
      if (baoGiaSection) {
        baoGiaSection.scrollIntoView({ behavior: "smooth" });
      }
    }

    // =========================================================================
    // 5. HERO SLIDER TỰ TRƯỢT 2 BANNER (Có hỗ trợ vuốt cảm ứng trên điện thoại)
    // =========================================================================
    let currentSlide = 0;
    let slideInterval = null;
    const slides = document.querySelectorAll(".banner-slide-item");
    const dots = document.querySelectorAll(".slider-dot");

    function goToSlide(index) {
      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        slide.classList.toggle("is-active", i === currentSlide);
        slide.classList.toggle("is-hidden", i !== currentSlide);
      });
      dots.forEach((dot, i) => {
        if (i === currentSlide) {
          dot.classList.add("w-7", "bg-brand-gold");
          dot.classList.remove("w-2.5", "bg-white/50");
        } else {
          dot.classList.remove("w-7", "bg-brand-gold");
          dot.classList.add("w-2.5", "bg-white/50");
        }
      });
    }

    function startAutoSlide() {
      clearInterval(slideInterval);
      slideInterval = setInterval(() => goToSlide(currentSlide + 1), 5000);
    }

    document.getElementById("prevSlide").addEventListener("click", () => {
      goToSlide(currentSlide - 1);
      startAutoSlide();
    });
    document.getElementById("nextSlide").addEventListener("click", () => {
      goToSlide(currentSlide + 1);
      startAutoSlide();
    });
    dots.forEach((dot) => {
      dot.addEventListener("click", () => {
        goToSlide(Number(dot.dataset.slide));
        startAutoSlide();
      });
    });

    // Vuốt chuyển banner trên điện thoại
    const heroSlider = document.getElementById("heroSlider");
    let touchStartX = 0;
    heroSlider.addEventListener("touchstart", (e) => {
      touchStartX = e.changedTouches[0].screenX;
    }, { passive: true });
    heroSlider.addEventListener("touchend", (e) => {
      const diff = touchStartX - e.changedTouches[0].screenX;
      if (Math.abs(diff) > 45) {
        goToSlide(diff > 0 ? currentSlide + 1 : currentSlide - 1);
        startAutoSlide();
      }
    }, { passive: true });

    // =========================================================================
    // 6. MENU MOBILE DRAWER & ACCORDION
    // =========================================================================
    const mobileMenuBtn = document.getElementById("mobileMenuBtn");
    const closeMobileDrawer = document.getElementById("closeMobileDrawer");
    const mobileDrawer = document.getElementById("mobileDrawer");
    const mobileDrawerBackdrop = document.getElementById("mobileDrawerBackdrop");

    function openMobileMenu() {
      mobileDrawer.classList.remove("-translate-x-full");
      mobileDrawerBackdrop.classList.remove("hidden");
      document.body.style.overflow = "hidden";
    }
    function closeMobileMenu() {
      mobileDrawer.classList.add("-translate-x-full");
      mobileDrawerBackdrop.classList.add("hidden");
      document.body.style.overflow = "";
    }

    mobileMenuBtn.addEventListener("click", openMobileMenu);
    closeMobileDrawer.addEventListener("click", closeMobileMenu);
    mobileDrawerBackdrop.addEventListener("click", closeMobileMenu);

    document.querySelectorAll(".mobile-nav-link").forEach((link) => {
      link.addEventListener("click", closeMobileMenu);
    });

    document.querySelectorAll(".mobile-accordion-btn").forEach((btn) => {
      btn.addEventListener("click", () => {
        const content = btn.nextElementSibling;
        const icon = btn.querySelector("svg");
        content.classList.toggle("hidden");
        icon.classList.toggle("rotate-180");
      });
    });

    // =========================================================================
    // 7. XỬ LÝ FORM ĐĂNG KÝ BÁO GIÁ (Không sử dụng alert)
    // =========================================================================
    document.getElementById("quoteForm").addEventListener("submit", function (e) {
      e.preventDefault();
      const name = document.getElementById("qName").value.trim();
      const phone = document.getElementById("qPhone").value.trim();
      const service = document.getElementById("qService").value;
      const box = document.getElementById("quoteSuccessBox");

      box.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá <strong>${service}</strong> (SĐT: <strong>${phone}</strong>) đã được gửi tới <strong>Nhôm Kính Anh Linh</strong>. Kỹ thuật viên sẽ liên hệ lại qua số <strong>0967.168.479</strong> trong ít phút.`;
      box.classList.remove("hidden");
      this.reset();
    });

    // Khởi tạo toàn bộ nội dung khi tải trang
    window.addEventListener("DOMContentLoaded", () => {
      renderCategories();
      renderProducts("all");
      renderProjects();
      renderNews();
      renderPartners();
      bindAllDriveImages();
      startAutoSlide();
    });
  </script>
</body>
</html>
