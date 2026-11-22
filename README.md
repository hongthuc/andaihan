<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH THƯƠNG MẠI &amp; DỊCH VỤ AN ĐẠI HÂN | Thiết Kế &amp; Thi Công Xây Dựng Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ AN ĐẠI HÂN (andaihan.com) - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện, xây nhà trọn gói, biệt thự, nhà phố, căn hộ tại Đà Nẵng. Hotline: 0971.646.699.">

    <!-- Open Graph & Thumbnail Logo khi chia sẻ đường dẫn andaihan.com lên Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ AN ĐẠI HÂN">
    <meta property="og:url" content="https://andaihan.com/">
    <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ AN ĐẠI HÂN - Xây Dựng & Kiến Trúc Đà Nẵng">
    <meta property="og:description" content="Thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện, nội thất trọn gói uy tín tại Đà Nẵng. Địa chỉ: 200 Bùi Công Trừng, Hòa Xuân, Đà Nẵng. Hotline: 0971.646.699.">
    <meta property="og:image" content="https://andaihan.com/assets/logo-an-dai-han-thumbnail.png">
    <meta property="og:image:secure_url" content="https://andaihan.com/assets/logo-an-dai-han-thumbnail.png">
    <meta property="og:image:type" content="image/png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Công ty TNHH Thương Mại & Dịch Vụ An Đại Hân">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ AN ĐẠI HÂN">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng - Hotline: 0971.646.699">
    <meta name="twitter:image" content="https://andaihan.com/assets/logo-an-dai-han-thumbnail.png">

    <!-- Favicon biểu tượng logo An Đại Hân -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2A4A'/%3E%3Cpath d='M32 10L12 28h7v24h10V38h6v14h10V28h7L32 10z' fill='%23C8922A'/%3E%3Cpath d='M32 17L20 28h24L32 17z' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2A4A',      /* Màu chính theo Logo: Xanh Navy Kiến Trúc */
                            navyDark: '#091B31',
                            navyLight: '#1A3F6B',
                            gold: '#C8922A',      /* Màu nhấn theo Logo: Vàng Đồng Sang Trọng */
                            goldHover: '#B07D1E',
                            goldSoft: '#FBF5E8',
                            surface: '#F6F8FA',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền ngang và chống lệch phải tuyệt đối trên mọi màn hình */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Quy chuẩn bề ngang 95% trên máy tính, tối ưu đệm lề trên điện thoại */
        .container-95 {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .container-95 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }
        @media (min-width: 1024px) {
            .container-95 {
                width: 95%;
                max-width: 95vw;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Dropdown menu chuẩn Flatsome trên máy tính */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner tự trượt 2 ảnh kích thước tuyệt đối bằng nhau */
        .banner-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 12px;
        }
        .banner-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            width: 50%;
            flex-shrink: 0;
            position: relative;
            display: flex;
            align-items: center;
            min-height: 360px;
        }
        @media (min-width: 640px) {
            .banner-slide {
                min-height: 410px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slide {
                min-height: 480px;
            }
        }

        /* Nút liên hệ nổi tương thích mượt trên máy tính và điện thoại */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(200, 146, 42, 0); }
            100% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0); }
        }
        .pulse-hotline {
            animation: softPulse 2s infinite;
        }

        /* Tab bộ lọc mượt mà trên di động không gây tràn trang */
        .hide-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .hide-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- =======================================================================
         TOP BAR THÔNG TIN NHANH (CHUẨN FLATSOME - KHÔNG CÓ THANH CHỈNH SỬA UXBUILDER)
    ======================================================================== -->
    <div class="bg-brand-navy text-white text-xs border-b border-white/10">
        <div class="container-95 py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0971646699" class="flex items-center gap-1.5 hover:text-brand-gold transition-colors">
                    <i class="fa-solid fa-phone text-brand-gold text-[11px]"></i>
                    <span class="font-semibold">0971.646.699</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <a href="mailto:lienhe@andaihan.com" class="hidden sm:flex items-center gap-1.5 hover:text-brand-gold transition-colors">
                    <i class="fa-solid fa-envelope text-brand-gold text-[11px]"></i>
                    <span>lienhe@andaihan.com</span>
                </a>
                <span class="hidden lg:inline text-white/30">|</span>
                <span class="hidden lg:flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-brand-gold text-[11px]"></i>
                    <span>200 Bùi Công Trừng, Phường Hòa Xuân, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="hidden md:inline text-slate-300">Website: <strong class="text-white">andaihan.com</strong></span>
                <div class="flex items-center gap-2">
                    <a href="https://facebook.com/andaihan" target="_blank" rel="noopener" aria-label="Facebook An Đại Hân" class="w-6 h-6 rounded-full bg-white/10 hover:bg-brand-gold flex items-center justify-center transition-colors">
                        <i class="fa-brands fa-facebook-f text-[11px]"></i>
                    </a>
                    <a href="https://zalo.me/0971646699" target="_blank" rel="noopener" aria-label="Zalo An Đại Hân" class="w-6 h-6 rounded-full bg-white/10 hover:bg-brand-gold flex items-center justify-center transition-colors font-bold text-[10px]">
                        Z
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =======================================================================
         HEADER CHÍNH (LOGO GỌN NHỎ CHUYÊN NGHIỆP + MENU 1 HÀNG - KHÔNG CÓ NÚT GỌI NGAY)
    ======================================================================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-200">
        <div class="container-95 h-16 lg:h-[72px] flex items-center justify-between gap-3">

            <!-- LOGO MỚI THIẾT KẾ CHUYÊN NGHIỆP, GỌN NHỎ CHO AN ĐẠI HÂN -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="An Đại Hân Trang Chủ">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="12" fill="#0F2A4A"/>
                    <!-- Khung kiến trúc hiện đại biểu tượng chữ A & mái công trình -->
                    <path d="M32 10L12 27.5V52H22V35.5H42V52H52V27.5L32 10Z" fill="#C8922A"/>
                    <path d="M32 16.5L18.5 28.5H45.5L32 16.5Z" fill="#FFFFFF"/>
                    <!-- Trụ cột bền vững ở trung tâm -->
                    <rect x="27" y="38.5" width="4" height="13.5" rx="1" fill="#FFFFFF"/>
                    <rect x="33" y="38.5" width="4" height="13.5" rx="1" fill="#FFFFFF"/>
                    <rect x="24" y="34" width="16" height="3" rx="1" fill="#0F2A4A"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors">
                        AN ĐẠI HÂN
                    </div>
                    <div class="text-[9px] sm:text-[10px] font-semibold tracking-wider text-brand-gold uppercase">
                        Xây Dựng &amp; Kiến Trúc
                    </div>
                </div>
            </a>

            <!-- DANH MỤC TRÊN MÁY TÍNH: VIẾT LIỀN 1 HÀNG, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-0.5 xl:gap-1" aria-label="Menu chính">
                <a href="#trang-chu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold transition-colors rounded-md">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md">
                    Giới thiệu
                </a>

                <!-- Dropdown: Công trình thực tế (theo mẫu tintruongthinh.com) -->
                <div class="nav-item relative">
                    <a href="#cong-trinh-thuc-te" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md flex items-center gap-1">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1.5 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động (theo mẫu tintruongthinh.com) -->
                <div class="nav-item relative">
                    <a href="#linh-vuc" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md flex items-center gap-1">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1.5 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5">
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Thi công phần thô</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Thi công hoàn thiện</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md">
                    Dự án Đà Nẵng
                </a>

                <!-- Dropdown: Báo giá -->
                <div class="nav-item relative">
                    <a href="#bao-gia" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md flex items-center gap-1">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1.5 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#doi-tac" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md">
                    Đối tác
                </a>
                <a href="#tin-tuc" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md">
                    Tin tức
                </a>
                <a href="#lien-he" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold transition-colors rounded-md">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút mở menu trên điện thoại / máy tính bảng -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden p-2.5 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-50 transition-colors">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- MENU NGĂN KÉO TRÊN ĐIỆN THOẠI (RÕ RÀNG, ĐẸP MẮT, DỄ CHẠM) -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="container-95 py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" class="py-2.5 hover:text-brand-gold mobile-link">Trang chủ</a>
                <a href="#gioi-thieu" class="py-2.5 hover:text-brand-gold mobile-link">Giới thiệu công ty</a>
                <a href="#linh-vuc" class="py-2.5 hover:text-brand-gold mobile-link">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="py-2.5 hover:text-brand-gold mobile-link">Công trình thực tế &amp; Sản phẩm</a>
                <a href="#du-an-da-nang" class="py-2.5 hover:text-brand-gold mobile-link">Dự án tiêu biểu tại Đà Nẵng</a>
                <a href="#doi-tac" class="py-2.5 hover:text-brand-gold mobile-link">Đối tác chiến lược</a>
                <a href="#bao-gia" class="py-2.5 hover:text-brand-gold mobile-link">Yêu cầu tư vấn &amp; Báo giá</a>
                <a href="#tin-tuc" class="py-2.5 hover:text-brand-gold mobile-link">Tin tức &amp; Kiến thức xây dựng</a>
                <a href="#lien-he" class="py-2.5 hover:text-brand-gold mobile-link">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu">

        <!-- ===================================================================
             SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             - Toàn bộ hình ảnh và chữ nằm gọn bên trong banner
             - Chữ cách xa viền ảnh và nút điều hướng, không bao giờ bị thiếu chữ
        ==================================================================== -->
        <section class="py-4 sm:py-6 bg-brand-surface">
            <div class="container-95">
                <div class="banner-wrapper shadow-lg bg-brand-navy" id="heroSlider">
                    <div class="banner-track" id="bannerTrack">

                        <!-- BANNER 1 -->
                        <div class="banner-slide">
                            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                                 data-gdrive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="handleDriveError(this)"
                                 alt="Thiết kế và thi công xây dựng trọn gói tại Đà Nẵng - An Đại Hân"
                                 class="absolute inset-0 w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/95 via-brand-navy/85 to-brand-navy/50"></div>

                            <!-- Vùng nội dung cách xa viền banner ở mọi góc (px-10 sm:px-16 lg:px-20) -->
                            <div class="relative z-10 w-full px-10 sm:px-16 lg:px-20 py-10 sm:py-14">
                                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                                    <div class="lg:col-span-8 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-bold tracking-[0.18em] uppercase text-brand-gold">
                                            CÔNG TY TNHH THƯƠNG MẠI &amp; DỊCH VỤ AN ĐẠI HÂN
                                        </p>
                                        <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                            THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP TẠI ĐÀ NẴNG
                                        </h1>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                            Chuyên Nhà phố, Biệt thự, Khách sạn, Căn hộ dịch vụ và Văn phòng. Cam kết tiến độ chuẩn xác, chất lượng bền vững và tối ưu chi phí cho chủ đầu tư.
                                        </p>
                                        <div class="pt-2 flex flex-wrap gap-3">
                                            <a href="#bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm shadow transition-colors">
                                                <span>Nhận báo giá miễn phí</span>
                                                <i class="fa-solid fa-arrow-right text-xs"></i>
                                            </a>
                                            <a href="#du-an-da-nang" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-colors">
                                                <span>Xem dự án Đà Nẵng</span>
                                            </a>
                                        </div>
                                    </div>
                                    <div class="hidden lg:block lg:col-span-4">
                                        <div class="rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-2xl aspect-[4/3] bg-brand-navyDark">
                                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000"
                                                 data-gdrive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                                 onerror="handleDriveError(this)"
                                                 alt="Thi công công trình thực tế An Đại Hân"
                                                 class="w-full h-full object-cover">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 -->
                        <div class="banner-slide">
                            <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600"
                                 data-gdrive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                 onerror="handleDriveError(this)"
                                 alt="Thi công phần thô, hoàn thiện và nội thất chuẩn kỹ thuật - An Đại Hân"
                                 class="absolute inset-0 w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/95 via-brand-navy/85 to-brand-navy/50"></div>

                            <!-- Vùng nội dung cách xa viền banner ở mọi góc (px-10 sm:px-16 lg:px-20) -->
                            <div class="relative z-10 w-full px-10 sm:px-16 lg:px-20 py-10 sm:py-14">
                                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                                    <div class="lg:col-span-8 text-white space-y-3 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-bold tracking-[0.18em] uppercase text-brand-gold">
                                            AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – UY TÍN
                                        </p>
                                        <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                            THI CÔNG PHẦN THÔ, HOÀN THIỆN &amp; NỘI THẤT CHUẨN KỸ THUẬT
                                        </h2>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                            Đội ngũ kỹ sư giám sát trực tiếp tại công trình, vật tư chính hãng minh bạch, bảo hành kết cấu dài hạn giúp gia chủ an tâm trọn vẹn.
                                        </p>
                                        <div class="pt-2 flex flex-wrap gap-3">
                                            <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm shadow transition-colors">
                                                <span>Công trình thực tế</span>
                                                <i class="fa-solid fa-arrow-right text-xs"></i>
                                            </a>
                                            <a href="tel:0971646699" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-white/30 font-semibold text-xs sm:text-sm transition-colors">
                                                <i class="fa-solid fa-phone text-xs text-brand-gold"></i>
                                                <span>Tư vấn: 0971.646.699</span>
                                            </a>
                                        </div>
                                    </div>
                                    <div class="hidden lg:block lg:col-span-4">
                                        <div class="rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-2xl aspect-[4/3] bg-brand-navyDark">
                                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                                                 data-gdrive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                                 onerror="handleDriveError(this)"
                                                 alt="Giám sát thi công xây dựng An Đại Hân"
                                                 class="w-full h-full object-cover">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng banner trái/phải gọn gàng sát mép ngoài vùng chữ -->
                    <button type="button" id="prevSlideBtn" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button type="button" id="nextSlideBtn" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo chuyển slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToSlide(0)" id="dot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="dot1" aria-label="Slide 2" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 2: DỊCH VỤ TIÊU BIỂU (CHUẨN MẪU TINTRUONGTHINH.COM - FLATSOME ROW)
        ==================================================================== -->
        <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-8 sm:mb-10">
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Dịch Vụ Tiêu Biểu
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Giải pháp toàn diện từ khâu lên ý tưởng thiết kế đến thi công xây dựng hoàn thiện chìa khóa trao tay.
                    </p>
                </div>

                <!-- 4 cột chuẩn UX Builder Flatsome (2 cột trên mobile) -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/80 hover:border-brand-gold hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
                            <i class="fa-solid fa-compass-drafting"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase mb-1.5">Thiết Kế Kiến Trúc</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Thiết kế mặt tiền, công năng tối ưu cho nhà phố, biệt thự, khách sạn và căn hộ hiện đại.
                        </p>
                    </div>

                    <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/80 hover:border-brand-gold hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
                            <i class="fa-solid fa-trowel-bricks"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase mb-1.5">Thi Công Phần Thô</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Đảm bảo kết cấu móng, khung cột, sàn bê tông vững chắc đúng bản vẽ kỹ thuật và tiêu chuẩn xây dựng.
                        </p>
                    </div>

                    <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/80 hover:border-brand-gold hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
                            <i class="fa-solid fa-helmet-safety"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase mb-1.5">Thi Công Hoàn Thiện</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Thi công trọn gói hệ thống điện nước, ốp lát, sơn bả, trần thạch cao tinh tế và sắc nét.
                        </p>
                    </div>

                    <div class="bg-brand-surface rounded-xl p-4 sm:p-6 border border-slate-200/80 hover:border-brand-gold hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
                            <i class="fa-solid fa-couch"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase mb-1.5">Thi Công Nội Thất</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Sản xuất và lắp đặt nội thất đồng bộ theo phong cách hiện đại, tối ưu thẩm mỹ và công năng sống.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 3: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA AN ĐẠI HÂN
        ==================================================================== -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200/70">
            <div class="container-95">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-10 sm:mb-12">
                    <div class="lg:col-span-6 space-y-4">
                        <p class="text-xs font-bold uppercase tracking-widest text-brand-gold">Về Chúng Tôi</p>
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy leading-snug">
                            CÔNG TY TNHH THƯƠNG MẠI &amp; DỊCH VỤ AN ĐẠI HÂN
                        </h2>
                        <div class="w-16 h-1 bg-brand-gold rounded-full"></div>
                        <p class="text-sm text-slate-700 leading-relaxed">
                            <strong>AN ĐẠI HÂN</strong> chuyên hoạt động trong lĩnh vực Thiết kế Kiến trúc – Thi công xây dựng – Hoàn thiện nội thất các công trình <strong>Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng</strong> tại khu vực Đà Nẵng và Miền Trung.
                        </p>
                        <p class="text-sm text-slate-700 leading-relaxed">
                            Với phương châm <strong>“An toàn – Chất lượng – Tiến độ – Sự hài lòng của khách hàng”</strong>, đội ngũ kỹ sư, kiến trúc sư và tổ thợ tay nghề cao của An Đại Hân luôn đặt cái tâm trong từng hạng mục thi công, minh bạch vật tư và chi phí ngay từ khâu báo giá ban đầu.
                        </p>
                        <div class="grid grid-cols-3 gap-3 pt-2">
                            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình thực hiện</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">100%</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Vật tư chính hãng</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
                                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">24/7</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Tư vấn &amp; Bảo hành</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6">
                        <div class="grid grid-cols-2 gap-3 sm:gap-4">
                            <div class="rounded-xl overflow-hidden shadow-md aspect-[4/3] bg-slate-200">
                                <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                                     data-gdrive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                     onerror="handleDriveError(this)"
                                     alt="Thi công công trình An Đại Hân"
                                     class="w-full h-full object-cover">
                            </div>
                            <div class="rounded-xl overflow-hidden shadow-md aspect-[4/3] bg-slate-200">
                                <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                                     data-gdrive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                                     onerror="handleDriveError(this)"
                                     alt="Đội ngũ thi công xây dựng An Đại Hân"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- THẾ MẠNH CỦA CHÚNG TÔI (6 MỤC THEO MẪU TINTRUONGTHINH.COM) -->
                <div class="pt-4">
                    <h3 class="text-lg sm:text-xl font-bold text-brand-navy uppercase text-center mb-6">
                        Thế Mạnh Của An Đại Hân
                    </h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-users-gear"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Đội ngũ kiến trúc sư, kỹ sư giàu kinh nghiệm</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng kỹ sư giám sát hiện trường và đội thợ lành nghề, tận tâm.</p>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-layer-group"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Cập nhật xu hướng thiết kế hiện đại</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng vật liệu mới và biện pháp thi công tiên tiến, tối ưu ánh sáng và công năng sử dụng.</p>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-calendar-check"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Báo cáo hình ảnh công trình thường xuyên để chủ đầu tư dễ dàng theo dõi từ xa, bàn giao đúng hẹn.</p>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-shield-halved"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Bảo hành công trình lâu dài</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Chính sách hậu mãi chu đáo, hỗ trợ kỹ thuật nhanh chóng ngay khi khách hàng cần.</p>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-file-invoice-dollar"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Chi phí minh bạch, không phát sinh</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, cân đối ngân sách hợp lý nhất cho gia chủ.</p>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl p-5 border border-slate-200/90 flex gap-3.5 items-start">
                            <div class="w-10 h-10 rounded-lg bg-brand-goldSoft text-brand-gold flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-headset"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-brand-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Khảo sát thực tế mặt bằng, tư vấn phương án thiết kế và khái toán chi phí hoàn toàn miễn phí.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 4: CÔNG TRÌNH THỰC TẾ & DANH MỤC SẢN PHẨM THI CÔNG (9 ẢNH DRIVE)
             - Chia 2 cột trên điện thoại, 3 cột trên máy tính
             - Tên sản phẩm hiển thị đầy đủ, không tràn viền hay cắt mất chữ
             - Không gắn nhãn dán (stickers) lên ảnh
        ==================================================================== -->
        <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-6 sm:mb-8">
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Công Trình Thực Tế &amp; Hạng Mục Thi Công
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Hình ảnh thi công thực tế tại công trường do đội ngũ kỹ sư Công ty TNHH Thương Mại &amp; Dịch Vụ An Đại Hân trực tiếp thực hiện.
                    </p>
                </div>

                <!-- Danh mục bộ lọc gọn gàng giống Flatsome Tabs trên tintruongthinh.com -->
                <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto hide-scrollbar pb-3 mb-6">
                    <button type="button" onclick="filterConstruction('all')" data-filter="all" class="filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-brand-navy text-white transition-colors">
                        Tất cả
                    </button>
                    <button type="button" onclick="filterConstruction('nha-pho')" data-filter="nha-pho" class="filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy transition-colors">
                        Nhà phố
                    </button>
                    <button type="button" onclick="filterConstruction('biet-thu')" data-filter="biet-thu" class="filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy transition-colors">
                        Biệt thự
                    </button>
                    <button type="button" onclick="filterConstruction('khach-san')" data-filter="khach-san" class="filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy transition-colors">
                        Khách sạn – Căn hộ – Phòng trọ
                    </button>
                    <button type="button" onclick="filterConstruction('van-phong')" data-filter="van-phong" class="filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy transition-colors">
                        Văn phòng
                    </button>
                </div>

                <!-- Lưới 9 ảnh thực tế thi công xây dựng: 2 cột trên mobile, 3 cột trên desktop -->
                <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Được render tự động bằng JavaScript để đồng bộ bộ lọc và Lightbox -->
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 5: DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DỰ ÁN TỪ GOOGLE DRIVE)
             - 2 cột trên điện thoại, 5 cột trên máy tính (hoặc 3 cột tablet)
             - Thiết kế tối giản, không nhãn dán, dễ dựng lại trên UX Builder Flatsome
        ==================================================================== -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200/70">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Tuyển tập các công trình nhà ở, biệt thự, căn hộ và dự án kiến trúc nổi bật đã hoàn thiện tại khu vực Thành phố Đà Nẵng.
                    </p>
                </div>

                <div id="danangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Render 10 dự án Đà Nẵng từ 10 link Drive -->
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 6: ĐỐI TÁC CHIẾN LƯỢC & NHÀ CUNG CẤP VẬT TƯ
        ==================================================================== -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-white">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-7">
                    <h2 class="text-xl sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Đối Tác Chiến Lược &amp; Cung Ứng Vật Tư
                    </h2>
                    <div class="w-14 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-2.5">
                        An Đại Hân hợp tác trực tiếp cùng các thương hiệu vật liệu xây dựng hàng đầu để bảo chứng chất lượng công trình.
                    </p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">HÒA PHÁT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">HOA SEN</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Tôn &amp; Ống Nhựa</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">SÔNG GIANH</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Xi Măng Cao Cấp</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">DULUX</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn Nội Ngoại Thất</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">JOTUN</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn Bảo Vệ</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">XINGFA</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Cửa Nhôm Kính</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">AN CƯỜNG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Gỗ Nội Thất</span>
                    </div>
                    <div class="bg-brand-surface border border-slate-200 rounded-xl p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-gold transition-colors">
                        <span class="font-extrabold text-brand-navy text-xs sm:text-sm tracking-tight">TOTO</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ MIỄN PHÍ TRANG CHỦ
             (ĐỒNG BỘ CÁC TRƯỜNG DỮ LIỆU GIỐNG MẪU TINTRUONGTHINH.COM)
        ==================================================================== -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
            <div class="container-95">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-5 space-y-4">
                        <p class="text-xs font-bold uppercase tracking-widest text-brand-gold">Miễn Phí Tư Vấn &amp; Khái Toán</p>
                        <h2 class="text-2xl sm:text-3xl font-extrabold leading-snug">
                            YÊU CẦU TƯ VẤN &amp; BÁO GIÁ XÂY DỰNG
                        </h2>
                        <div class="w-16 h-1 bg-brand-gold rounded-full"></div>
                        <p class="text-sm text-slate-200 leading-relaxed">
                            Quý khách đang dự định xây dựng nhà phố, biệt thự, căn hộ cho thuê hay cải tạo văn phòng tại Đà Nẵng? Hãy để lại thông tin để kỹ sư của <strong>An Đại Hân</strong> liên hệ khảo sát và gửi bảng báo giá chi tiết trong 24 giờ.
                        </p>
                        <div class="space-y-2.5 pt-2 text-sm text-slate-100">
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Tư vấn phương án mặt bằng công năng miễn phí</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Bóc tách khối lượng &amp; chủng loại vật tư rõ ràng</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                <span>Hotline trực tiếp: <a href="tel:0971646699" class="font-bold text-brand-gold underline">0971.646.699</a></span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên <span class="text-red-500">*</span></label>
                                    <input type="text" id="customerName" required placeholder="Nhập họ và tên của bạn"
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại <span class="text-red-500">*</span></label>
                                    <input type="tel" id="customerPhone" required placeholder="Nhập số điện thoại liên hệ"
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="projectType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                    <select id="projectType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none bg-white">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="budgetRange" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="budgetRange" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none bg-white">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email (không bắt buộc)</label>
                                    <input type="email" id="customerEmail" placeholder="example@gmail.com"
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="projectArea" class="block text-xs font-semibold text-slate-700 mb-1.5">Diện tích / Vị trí đất</label>
                                    <input type="text" id="projectArea" placeholder="VD: 100m2, Hòa Xuân, Đà Nẵng"
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                            </div>

                            <div>
                                <label for="customerNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết</label>
                                <textarea id="customerNote" rows="2" placeholder="Nhập quy mô số tầng, hạng mục cần báo giá (phần thô / trọn gói / nội thất)..."
                                          class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none resize-none"></textarea>
                            </div>

                            <!-- Hộp thông báo phản hồi ngay trên form (không dùng alert) -->
                            <div id="quoteMessage" class="hidden rounded-lg p-3.5 text-xs sm:text-sm font-medium"></div>

                            <button type="submit" class="w-full py-3 px-6 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm uppercase tracking-wide shadow transition-colors flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Gửi Yêu Cầu Báo Giá Ngay</span>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 8: DANH MỤC CÁC BÀI VIẾT & TIN TỨC XÂY DỰNG TRANG CHỦ
        ==================================================================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Tin Tức &amp; Cẩm Nang Xây Dựng
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Cập nhật kinh nghiệm thi công, kỹ thuật xây dựng và xu hướng thiết kế nhà ở mới nhất tại Đà Nẵng.
                    </p>
                </div>

                <div id="articlesGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                    <!-- Render danh sách bài viết bằng JavaScript -->
                </div>
            </div>
        </section>

        <!-- ===================================================================
             SECTION 9: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ
        ==================================================================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-brand-surface border-t border-slate-200/80">
            <div class="container-95">
                <div class="text-center max-w-2xl mx-auto mb-8">
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
                        Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-3 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3">
                        Trụ sở: 200 Bùi Công Trừng, Phường Hòa Xuân, TP Đà Nẵng — Hotline: 0971.646.699
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- CỘT TRÁI: GOOGLE MAP TRỰC TIẾP TRÊN TRANG CHỦ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-sm font-bold text-brand-navy">
                                <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                                <span>Vị Trí Văn Phòng An Đại Hân</span>
                            </div>
                            <a href="https://maps.google.com/?q=200+B%C3%B9i+C%C3%B4ng+Tr%E1%BB%ABng,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-xs font-semibold text-brand-gold hover:underline">
                                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                        <div class="w-full flex-1 min-h-[300px] sm:min-h-[340px]">
                            <iframe
                                title="Bản đồ Công ty TNHH Thương Mại & Dịch Vụ An Đại Hân - 200 Bùi Công Trừng, Hòa Xuân, Đà Nẵng"
                                src="https://maps.google.com/maps?q=200+B%C3%B9i+C%C3%B4ng+Tr%E1%BB%ABng,+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full min-h-[300px] sm:min-h-[340px] border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- CỘT PHẢI: KHỐI FANPAGE FACEBOOK CHÍNH THỨC TRÊN TRANG CHỦ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
                            <div class="flex items-center gap-2 text-sm font-bold text-brand-navy">
                                <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                                <span>Fanpage Chính Thức</span>
                            </div>
                            <span class="text-[11px] text-slate-500">Cập nhật công trình hằng ngày</span>
                        </div>

                        <!-- Giao diện Fanpage đẹp mắt, luôn hiển thị ổn định trên mọi trình duyệt -->
                        <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                                <!-- Ảnh bìa Fanpage -->
                                <div class="relative h-32 sm:h-36 bg-brand-navy">
                                    <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000"
                                         data-gdrive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                                         onerror="handleDriveError(this)"
                                         alt="Fanpage An Đại Hân"
                                         class="w-full h-full object-cover opacity-80">
                                    <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navy/30 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                                            <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M32 10L12 27.5V52H22V35.5H42V52H52V27.5L32 10Z" fill="#C8922A"/>
                                                <path d="M32 16.5L18.5 28.5H45.5L32 16.5Z" fill="#FFFFFF"/>
                                            </svg>
                                        </div>
                                        <div class="text-white min-w-0">
                                            <div class="font-bold text-sm leading-tight truncate">An Đại Hân - Xây Dựng &amp; Kiến Trúc Đà Nẵng</div>
                                            <div class="text-[11px] text-slate-200 mt-0.5">Công ty Xây dựng • Hòa Xuân, Đà Nẵng</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Thông tin bài đăng gần đây trên Fanpage -->
                                <div class="p-3.5 space-y-3 bg-white">
                                    <div class="flex items-center justify-between gap-2">
                                        <a href="https://facebook.com/andaihan" target="_blank" rel="noopener" class="flex-1 py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1565C0] text-white text-xs font-semibold text-center transition-colors">
                                            <i class="fa-brands fa-facebook-f mr-1.5"></i>Theo dõi Fanpage
                                        </a>
                                        <a href="https://zalo.me/0971646699" target="_blank" rel="noopener" class="flex-1 py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-brand-navy text-xs font-semibold text-center transition-colors">
                                            <i class="fa-solid fa-comment-dots mr-1.5 text-brand-gold"></i>Nhắn tin tư vấn
                                        </a>
                                    </div>

                                    <div class="border-t border-slate-100 pt-3 space-y-2">
                                        <p class="text-xs text-slate-700 leading-relaxed">
                                            <strong>An Đại Hân</strong> vừa cập nhật tiến độ thi công thực tế công trình nhà phố 3 tầng tại Hòa Xuân &amp; các mẫu thiết kế nhà hiện đại 2026 tại Đà Nẵng.
                                        </p>
                                        <div class="grid grid-cols-3 gap-1.5">
                                            <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w600" data-gdrive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k" onerror="handleDriveError(this)" alt="Ảnh công trình 1" class="w-full aspect-square object-cover rounded">
                                            <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w600" data-gdrive-id="1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N" onerror="handleDriveError(this)" alt="Ảnh công trình 2" class="w-full aspect-square object-cover rounded">
                                            <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w600" data-gdrive-id="1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML" onerror="handleDriveError(this)" alt="Ảnh công trình 3" class="w-full aspect-square object-cover rounded">
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="text-xs text-slate-600 flex items-center justify-between bg-brand-goldSoft px-3.5 py-2.5 rounded-lg">
                                <span><i class="fa-solid fa-clock text-brand-gold mr-1.5"></i>Làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
                                <a href="tel:0971646699" class="font-bold text-brand-navy">0971.646.699</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- =======================================================================
         FOOTER CHUYÊN NGHIỆP (CHUẨN FLATSOME)
    ======================================================================== -->
    <footer class="bg-brand-navyDark text-slate-300 pt-12 pb-6">
        <div class="container-95">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3.5">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="12" fill="#1A3F6B"/>
                            <path d="M32 10L12 27.5V52H22V35.5H42V52H52V27.5L32 10Z" fill="#C8922A"/>
                            <path d="M32 16.5L18.5 28.5H45.5L32 16.5Z" fill="#FFFFFF"/>
                            <rect x="27" y="38.5" width="4" height="13.5" rx="1" fill="#FFFFFF"/>
                            <rect x="33" y="38.5" width="4" height="13.5" rx="1" fill="#FFFFFF"/>
                        </svg>
                        <div>
                            <div class="text-white font-extrabold text-sm sm:text-base leading-tight">CÔNG TY TNHH THƯƠNG MẠI &amp; DỊCH VỤ AN ĐẠI HÂN</div>
                            <div class="text-[11px] text-brand-gold font-semibold">andaihan.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
                            <span>Trụ sở: 200 Bùi Công Trừng, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-gold"></i>
                            <span>Hotline: <a href="tel:0971646699" class="text-white font-semibold hover:text-brand-gold">0971.646.699</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-envelope text-brand-gold"></i>
                            <span>Email: <a href="mailto:lienhe@andaihan.com" class="hover:text-brand-gold">lienhe@andaihan.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building-shield text-brand-gold"></i>
                            <span>Mã số thuế: 0402199233</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider">Lĩnh Vực Hoạt Động</h4>
                    <div class="w-10 h-0.5 bg-brand-gold"></div>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc" class="hover:text-brand-gold transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-gold transition-colors">Thi công phần thô</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-gold transition-colors">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc" class="hover:text-brand-gold transition-colors">Thi công nội thất nhà ở &amp; văn phòng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Cải tạo sửa chữa công trình</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div class="lg:col-span-2 space-y-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider">Công Trình</h4>
                    <div class="w-10 h-0.5 bg-brand-gold"></div>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-brand-gold transition-colors">Nhà phố hiện đại</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-brand-gold transition-colors">Biệt thự cao cấp</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="hover:text-brand-gold transition-colors">Khách sạn – Căn hộ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-brand-gold transition-colors">Văn phòng làm việc</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition-colors">Dự án tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div class="lg:col-span-2 space-y-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider">Kết Nối</h4>
                    <div class="w-10 h-0.5 bg-brand-gold"></div>
                    <p class="text-xs text-slate-400 leading-relaxed">Liên hệ trực tiếp để nhận tư vấn và bảng báo giá mới nhất năm 2026.</p>
                    <div class="flex items-center gap-2.5 pt-1">
                        <a href="https://facebook.com/andaihan" target="_blank" rel="noopener" aria-label="Facebook" class="w-9 h-9 rounded-lg bg-[#1877F2] text-white flex items-center justify-center hover:opacity-90">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://zalo.me/0971646699" target="_blank" rel="noopener" aria-label="Zalo" class="w-9 h-9 rounded-lg bg-[#0068FF] text-white font-extrabold text-xs flex items-center justify-center hover:opacity-90">
                            Zalo
                        </a>
                        <a href="tel:0971646699" aria-label="Hotline" class="w-9 h-9 rounded-lg bg-brand-gold text-white flex items-center justify-center hover:bg-brand-goldHover">
                            <i class="fa-solid fa-phone"></i>
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright 2026 &copy; <strong class="text-white">CÔNG TY TNHH THƯƠNG MẠI &amp; DỊCH VỤ AN ĐẠI HÂN</strong> (andaihan.com). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- =======================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO - FACEBOOK - HOTLINE
         Tương thích gọn gàng trên cả máy tính và điện thoại, không che nội dung
    ======================================================================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0971646699" target="_blank" rel="noopener" aria-label="Chat Zalo An Đại Hân"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-1.5 sm:px-3.5 sm:py-2 transition-all">
            <span class="w-9 h-9 sm:w-7 sm:h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-xs flex items-center justify-center shrink-0">
                Zalo
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://facebook.com/andaihan" target="_blank" rel="noopener" aria-label="Facebook An Đại Hân"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#145DBF] text-white rounded-full shadow-lg p-1.5 sm:px-3.5 sm:py-2 transition-all">
            <span class="w-9 h-9 sm:w-7 sm:h-7 rounded-full bg-white text-[#1877F2] text-sm flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0971646699" aria-label="Gọi Hotline 0971.646.699"
           class="pulse-hotline group flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white rounded-full shadow-lg p-1.5 sm:px-3.5 sm:py-2 transition-all">
            <span class="w-9 h-9 sm:w-7 sm:h-7 rounded-full bg-white text-brand-navy text-sm flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">0971.646.699</span>
        </a>
    </div>

    <!-- =======================================================================
         MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH / BÀI VIẾT
    ======================================================================== -->
    <div id="detailModal" class="hidden fixed inset-0 z-[60] bg-black/75 backdrop-blur-xs flex items-center justify-center p-3 sm:p-6">
        <div class="bg-white rounded-xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ"
                    class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-black/50 hover:bg-brand-navy text-white flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modalBody"></div>
        </div>
    </div>

    <!-- =======================================================================
         JAVASCRIPT ĐIỀU KHIỂN DỮ LIỆU THỰC TẾ, SLIDER, BỘ LỌC & FORM BÁO GIÁ
    ======================================================================== -->
    <script>
        /* =====================================================================
           1. HÀM XỬ LÝ TẢI ẢNH GOOGLE DRIVE CÓ FALLBACK AN TOÀN
        ===================================================================== */
        function getDriveUrl(id, size = 'w1000') {
            return `https://drive.google.com/thumbnail?id=${id}&sz=${size}`;
        }

        function handleDriveError(img) {
            const id = img.getAttribute('data-gdrive-id');
            const stage = parseInt(img.getAttribute('data-fallback-stage') || '0', 10);
            if (stage === 0 && id) {
                img.setAttribute('data-fallback-stage', '1');
                img.src = `https://lh3.googleusercontent.com/d/${id}=w1000`;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/800x600/0F2A4A/C8922A?text=AN+DAI+HAN';
            }
        }

        /* =====================================================================
           2. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
              Phân loại chuẩn theo danh mục mẫu tintruongthinh.com
        ===================================================================== */
        const constructionItems = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi công phần thô nhà phố 3 tầng hiện đại – Khu vực Hòa Xuân',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                spec: 'Thi công phần thô & nhân công hoàn thiện • TP Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng được đội ngũ kỹ sư An Đại Hân trực tiếp giám sát từng công đoạn cốt thép, cốp pha và đổ bê tông đúng tiêu chuẩn kỹ thuật.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi công kết cấu móng và khung bê tông nhà phố Cẩm Lệ',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                spec: 'Kết cấu phần thô chuẩn kỹ thuật • Quận Cẩm Lệ',
                desc: 'Triển khai hệ thống dầm móng, giằng cột chắc chắn, đảm bảo độ bền kết cấu lâu dài và an toàn tuyệt đối cho công trình nhà ở dân dụng.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi công xây dựng biệt thự hiện đại 2 mặt tiền Đà Nẵng',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                spec: 'Thi công trọn gói chìa khóa trao tay • Đà Nẵng',
                desc: 'Biệt thự thiết kế không gian mở sang trọng, thi công xây tô sắc nét cùng giải pháp chống thấm và cách nhiệt tối ưu cho khí hậu miền Trung.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi công hoàn thiện căn hộ cho thuê & phòng trọ cao cấp',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ',
                spec: 'Thi công trọn gói căn hộ dịch vụ • Quận Sơn Trà',
                desc: 'Giải pháp thi công tối ưu công năng phòng cho thuê, hệ thống điện nước âm tường chuẩn an toàn và tiến độ bàn giao nhanh đưa vào khai thác.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi công xây tường, tô trát và hoàn thiện mặt tiền nhà phố',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                spec: 'Thi công hoàn thiện mặt tiền • Khu Nam Hòa Xuân',
                desc: 'Kỹ thuật xây tô phẳng chuẩn thước, xử lý kỹ các vị trí góc cạnh, ban công và chống nứt tường đảm bảo thẩm mỹ bền đẹp theo thời gian.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi công lắp dựng kết cấu sàn và hệ thống kỹ thuật tòa nhà văn phòng',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                spec: 'Thi công văn phòng thương mại • Quận Hải Châu',
                desc: 'Đáp ứng tiêu chuẩn kỹ thuật cao cho không gian làm việc hiện đại, tối ưu tải trọng sàn và đồng bộ hệ thống cơ điện chiếu sáng.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi công hoàn thiện nội ngoại thất biệt thự sân vườn',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                spec: 'Hoàn thiện & Nội thất đồng bộ • Quận Ngũ Hành Sơn',
                desc: 'Kết hợp hài hòa giữa vật liệu đá tự nhiên, gỗ nội thất cao cấp và mảng xanh sân vườn mang lại không gian nghỉ dưỡng đẳng cấp.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi công cải tạo và hoàn thiện khách sạn mini gần biển',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ',
                spec: 'Thi công hoàn thiện khách sạn • Đà Nẵng',
                desc: 'Tổ chức thi công khoa học, đảm bảo vệ sinh an toàn lao động và hoàn thiện chuẩn từng chi tiết phòng lưu trú, hành lang, khu lễ tân.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Giám sát nghiệm thu và bàn giao nhà phố xây trọn gói',
                category: 'van-phong',
                categoryName: 'Văn phòng',
                spec: 'Nghiệm thu kỹ thuật & bàn giao • TP Đà Nẵng',
                desc: 'Kiểm tra chất lượng đồng bộ toàn bộ hạng mục sơn nước, cửa nhôm kính, thiết bị vệ sinh và điện nước trước khi bàn giao chìa khóa cho chủ đầu tư.'
            }
        ];

        /* =====================================================================
           3. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE
        ===================================================================== */
        const danangProjects = [
            { id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', title: 'Nhà phố hiện đại Hòa Xuân', location: 'Phường Hòa Xuân, Đà Nẵng' },
            { id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', title: 'Biệt thự vườn Nam Việt Á', location: 'Ngũ Hành Sơn, Đà Nẵng' },
            { id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz', title: 'Căn hộ dịch vụ Sơn Trà', location: 'Quận Sơn Trà, Đà Nẵng' },
            { id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k', title: 'Nhà phố 3 tầng Cẩm Lệ', location: 'Quận Cẩm Lệ, Đà Nẵng' },
            { id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N', title: 'Khách sạn Boutique biển Mỹ Khê', location: 'Sơn Trà, Đà Nẵng' },
            { id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML', title: 'Nhà ở kết hợp văn phòng Hải Châu', location: 'Quận Hải Châu, Đà Nẵng' },
            { id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF', title: 'Biệt thự phố 2 mặt tiền Phước Lý', location: 'Cẩm Lệ, Đà Nẵng' },
            { id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A', title: 'Nhà phố mái thái Liên Chiểu', location: 'Quận Liên Chiểu, Đà Nẵng' },
            { id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80', title: 'Tòa căn hộ cho thuê An Thượng', location: 'Ngũ Hành Sơn, Đà Nẵng' },
            { id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4', title: 'Nhà phố hiện đại Thanh Khê', location: 'Quận Thanh Khê, Đà Nẵng' }
        ];

        /* =====================================================================
           4. DỮ LIỆU CÁC BÀI VIẾT TIN TỨC XÂY DỰNG TRANG CHỦ
        ===================================================================== */
        const articles = [
            {
                id: 'art-1',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng chuẩn kỹ thuật xây dựng',
                date: '15/11/2026',
                imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                excerpt: 'Bảo dưỡng bê tông đúng thời điểm và đủ độ ẩm giúp hạn chế rạn nứt bề mặt, gia tăng cường độ chịu lực và tuổi thọ công trình.',
                content: 'Trong quá trình thi công phần thô, công tác bảo dưỡng bê tông sau khi đổ đóng vai trò quyết định đến chất lượng kết cấu công trình. Sau khoảng 4 giờ kể từ lúc đổ bê tông (tùy điều kiện thời tiết nắng gió tại Đà Nẵng), cần tiến hành tưới nước giữ ẩm liên tục và che phủ bề mặt trong 7 ngày đầu tiên để thủy hóa xi măng diễn ra hoàn toàn, giúp khối bê tông đạt cường độ tối ưu.'
            },
            {
                id: 'art-2',
                title: 'Kinh nghiệm xây nhà phố trọn gói tại Đà Nẵng tối ưu ngân sách',
                date: '08/11/2026',
                imageId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                excerpt: 'Chuẩn bị hồ sơ thiết kế chi tiết, lựa chọn gói vật tư minh bạch và ký hợp đồng rõ tiến độ là 3 yếu tố tránh phát sinh chi phí.',
                content: 'Khi xây dựng nhà ở tại Đà Nẵng, chủ đầu tư nên hoàn thiện bản vẽ kiến trúc, kết cấu và điện nước đầy đủ trước khi khởi công. Việc chọn đơn vị thiết kế & thi công trọn gói uy tín như An Đại Hân giúp đồng bộ từ bản vẽ đến hiện trường, bóc tách dự toán rõ ràng từng chủng loại vật tư và tiết kiệm đáng kể thời gian giám sát.'
            },
            {
                id: 'art-3',
                title: '3 lưu ý quan trọng khi thiết kế nội thất nhà ở hiện đại',
                date: '29/10/2026',
                imageId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                excerpt: 'Tối ưu ánh sáng tự nhiên, lựa chọn bảng màu đồng điệu và ưu tiên vật liệu bền bỉ giúp không gian sống luôn rộng thoáng.',
                content: 'Thiết kế nội thất không chỉ là sắp đặt đồ dùng mà là nghệ thuật tổ chức không gian sống tiện nghi. Đối với nhà phố có chiều ngang hạn chế, việc bố trí giếng trời, hệ tủ kịch trần và sử dụng gam màu trung tính kết hợp gỗ ấm sẽ tạo cảm giác rộng rãi, thông thoáng và tăng tính thẩm mỹ lâu dài.'
            },
            {
                id: 'art-4',
                title: 'Quy trình nghiệm thu phần thô trước khi bước vào hoàn thiện',
                date: '18/10/2026',
                imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: 'Kiểm tra độ thẳng tường xây, thử áp hệ thống cấp thoát nước và chống thấm sàn mái là những bước bắt buộc không thể bỏ qua.',
                content: 'Trước khi lát gạch, đóng trần hay sơn bả hoàn thiện, kỹ sư giám sát và chủ nhà cần nghiệm thu chặt chẽ toàn bộ hạng mục phần thô: kiểm tra độ phẳng tường tô, thử áp lực đường ống cấp nước, ngâm thử chống thấm nhà vệ sinh và ban công trong 48 giờ để đảm bảo công trình vận hành bền vững không thấm dột.'
            }
        ];

        /* =====================================================================
           5. RENDER DANH SÁCH CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT MOBILE)
        ===================================================================== */
        function renderConstruction(filter = 'all') {
            const grid = document.getElementById('constructionGrid');
            const list = filter === 'all'
                ? constructionItems
                : constructionItems.filter(item => item.category === filter);

            grid.innerHTML = list.map((item) => `
                <article onclick="openImageModal('${item.id}', '${escapeHtml(item.title)}', '${escapeHtml(item.spec)}', '${escapeHtml(item.desc)}')"
                         class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="${getDriveUrl(item.id, 'w900')}"
                             data-gdrive-id="${item.id}"
                             onerror="handleDriveError(this)"
                             loading="lazy"
                             alt="${escapeHtml(item.title)}"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-normal break-words">
                            ${item.spec}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(category) {
            renderConstruction(category);
            document.querySelectorAll('.filter-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-filter') === category;
                btn.className = isActive
                    ? 'filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-brand-navy text-white transition-colors'
                    : 'filter-btn whitespace-nowrap px-3.5 py-2 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-goldSoft hover:text-brand-navy transition-colors';
            });
        }

        /* =====================================================================
           6. RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE)
        ===================================================================== */
        function renderDanangProjects() {
            const grid = document.getElementById('danangProjectsGrid');
            grid.innerHTML = danangProjects.map(proj => `
                <article onclick="openImageModal('${proj.id}', '${escapeHtml(proj.title)}', '${escapeHtml(proj.location)}', 'Dự án tiêu biểu tại Đà Nẵng do Công ty TNHH Thương Mại & Dịch Vụ An Đại Hân thiết kế và triển khai thi công.')"
                         class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="${getDriveUrl(proj.id, 'w800')}"
                             data-gdrive-id="${proj.id}"
                             onerror="handleDriveError(this)"
                             loading="lazy"
                             alt="${escapeHtml(proj.title)}"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                            ${proj.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-brand-gold text-[10px] shrink-0"></i>
                            <span class="break-words">${proj.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* =====================================================================
           7. RENDER CÁC BÀI VIẾT TIN TỨC TRANG CHỦ
        ===================================================================== */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            grid.innerHTML = articles.map(art => `
                <article onclick="openArticleModal('${art.id}')"
                         class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="${getDriveUrl(art.imageId, 'w800')}"
                             data-gdrive-id="${art.imageId}"
                             onerror="handleDriveError(this)"
                             loading="lazy"
                             alt="${escapeHtml(art.title)}"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 mb-1.5">${art.date}</div>
                            <h3 class="text-sm font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="pt-3 text-xs font-semibold text-brand-gold flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* =====================================================================
           8. ĐIỀU KHIỂN SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI
        ===================================================================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            const track = document.getElementById('bannerTrack');
            track.style.transform = `translateX(-${currentSlide * 50}%)`;

            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById(`dot${i}`);
                if (dot) {
                    dot.className = i === currentSlide
                        ? 'w-6 h-2 rounded-full bg-brand-gold transition-all'
                        : 'w-2 h-2 rounded-full bg-white/50 transition-all';
                }
            }
            resetSliderTimer();
        }

        function resetSliderTimer() {
            clearInterval(sliderTimer);
            sliderTimer = setInterval(() => {
                goToSlide(currentSlide + 1);
            }, 5500);
        }

        /* =====================================================================
           9. MODAL XEM CHI TIẾT ẢNH & BÀI VIẾT
        ===================================================================== */
        function escapeHtml(str) {
            return String(str).replace(/'/g, "\\'").replace(/"/g, '&quot;');
        }

        function openImageModal(driveId, title, meta, desc) {
            const modal = document.getElementById('detailModal');
            const body = document.getElementById('modalBody');
            body.innerHTML = `
                <div class="bg-brand-navyDark">
                    <img src="${getDriveUrl(driveId, 'w1400')}"
                         data-gdrive-id="${driveId}"
                         onerror="handleDriveError(this)"
                         alt="${title}"
                         class="w-full max-h-[60vh] object-contain mx-auto">
                </div>
                <div class="p-5 sm:p-6 space-y-2.5">
                    <div class="text-xs font-semibold text-brand-gold uppercase">${meta}</div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy">${title}</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">${desc}</p>
                    <div class="pt-3 flex flex-wrap gap-3">
                        <a href="#bao-gia" onclick="closeDetailModal()" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm transition-colors">
                            Yêu cầu báo giá công trình tương tự
                        </a>
                        <a href="tel:0971646699" class="px-5 py-2.5 rounded-lg bg-brand-navy text-white font-semibold text-xs sm:text-sm hover:bg-brand-navyLight transition-colors">
                            Gọi tư vấn: 0971.646.699
                        </a>
                    </div>
                </div>
            `;
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openArticleModal(articleId) {
            const art = articles.find(a => a.id === articleId);
            if (!art) return;
            const modal = document.getElementById('detailModal');
            const body = document.getElementById('modalBody');
            body.innerHTML = `
                <div class="w-full aspect-[16/9] bg-slate-100 overflow-hidden">
                    <img src="${getDriveUrl(art.imageId, 'w1200')}"
                         data-gdrive-id="${art.imageId}"
                         onerror="handleDriveError(this)"
                         alt="${art.title}"
                         class="w-full h-full object-cover">
                </div>
                <div class="p-5 sm:p-7 space-y-3">
                    <div class="text-xs text-slate-500">Ngày đăng: ${art.date} • CÔNG TY TNHH TM &amp; DV AN ĐẠI HÂN</div>
                    <h3 class="text-lg sm:text-2xl font-extrabold text-brand-navy leading-snug">${art.title}</h3>
                    <p class="text-sm text-slate-700 leading-relaxed font-medium">${art.excerpt}</p>
                    <p class="text-sm text-slate-600 leading-relaxed">${art.content}</p>
                    <div class="pt-4 border-t border-slate-100 flex flex-wrap items-center justify-between gap-3">
                        <span class="text-xs text-slate-500">Cần tư vấn kỹ thuật? Liên hệ ngay kỹ sư An Đại Hân</span>
                        <a href="tel:0971646699" class="px-4 py-2 rounded-lg bg-brand-gold text-white text-xs font-bold hover:bg-brand-goldHover">
                            Hotline: 0971.646.699
                        </a>
                    </div>
                </div>
            `;
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            document.getElementById('detailModal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        /* =====================================================================
           10. KHỞI TẠO SỰ KIỆN KHI TẢI TRANG
        ===================================================================== */
        document.addEventListener('DOMContentLoaded', () => {
            renderConstruction('all');
            renderDanangProjects();
            renderArticles();
            resetSliderTimer();

            // Nút slider trái / phải
            document.getElementById('prevSlideBtn').addEventListener('click', () => goToSlide(currentSlide - 1));
            document.getElementById('nextSlideBtn').addEventListener('click', () => goToSlide(currentSlide + 1));

            // Hỗ trợ vuốt cảm ứng banner trên điện thoại
            let touchStartX = 0;
            const sliderEl = document.getElementById('heroSlider');
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    goToSlide(diff > 0 ? currentSlide - 1 : currentSlide + 1);
                }
            }, { passive: true });

            // Đóng mở menu mobile
            const mobileBtn = document.getElementById('mobileMenuBtn');
            const mobileMenu = document.getElementById('mobileMenu');
            mobileBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            document.querySelectorAll('.mobile-link').forEach(link => {
                link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
            });

            // Đóng modal khi bấm ra vùng nền tối
            document.getElementById('detailModal').addEventListener('click', (e) => {
                if (e.target.id === 'detailModal') closeDetailModal();
            });

            // Xử lý Form Yêu Cầu Báo Giá (không dùng alert)
            const quoteForm = document.getElementById('quoteForm');
            const quoteMsg = document.getElementById('quoteMessage');
            quoteForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const name = document.getElementById('customerName').value.trim();
                const phone = document.getElementById('customerPhone').value.trim();
                const type = document.getElementById('projectType').value;

                if (!name || !phone) {
                    quoteMsg.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                    quoteMsg.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư liên hệ báo giá.';
                    quoteMsg.classList.remove('hidden');
                    return;
                }

                quoteMsg.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                quoteMsg.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong>! Yêu cầu tư vấn hạng mục <strong>${type}</strong> đã được ghi nhận. Kỹ sư An Đại Hân sẽ gọi lại số <strong>${phone}</strong> trong thời gian sớm nhất.`;
                quoteMsg.classList.remove('hidden');
                quoteForm.reset();
            });
        });
    </script>
</body>
</html>
