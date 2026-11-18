<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ - thietkemaunha.com | Thiết Kế & Thi Công Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ (thietkemaunha.com) chuyên Thiết kế Kiến trúc - Nội thất, Thi công phần thô, Thi công hoàn thiện, Xây nhà trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ tại Đà Nẵng. Địa chỉ: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng. Hotline: 0931.999.334.">
    <meta name="keywords" content="thietkemaunha.com, Công ty TNHH Xây dựng Thiết kế Mẫu Nhà, xây nhà trọn gói Đà Nẵng, thiết kế nhà đẹp Đà Nẵng, thi công nội thất Đà Nẵng, 261 Nguyễn Sinh Sắc">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thietkemaunha.com/">
    <meta property="og:site_name" content="thietkemaunha.com - CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ | thietkemaunha.com">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc - Thi công xây dựng trọn gói - Nội thất uy tín tại Đà Nẵng. Địa chỉ: 261 Nguyễn Sinh Sắc, P. Hòa Khánh, TP Đà Nẵng. Hotline: 0931.999.334">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w1200">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ - thietkemaunha.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w1200">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w256" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#14213d',      /* Xanh đen kiến trúc theo tông logo */
                            navy: '#1e293b',      /* Xám xanh đậm chủ đạo */
                            gold: '#c88a2b',      /* Vàng đồng kiến trúc chủ đạo theo logo */
                            goldLight: '#e0a445', /* Vàng sáng điểm nhấn */
                            goldDark: '#9e6816',  /* Vàng đậm hover */
                            bgSoft: '#f8fafc'     /* Nền xám sáng Flatsome */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1e293b;
            background-color: #ffffff;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome: Chiều ngang trên máy tính bằng 95% kích thước màn hình */
        .ux-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 767px) {
            .ux-container {
                width: 94%;
                max-width: 94%;
            }
        }

        /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ xuống dòng bên trong tên danh mục */
        .ux-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px;
        }
        @media (min-width: 1150px) {
            .ux-nav-list {
                flex-wrap: nowrap;
                gap: 4px;
            }
        }
        .ux-nav-item {
            white-space: nowrap !important;
            font-size: 11.5px;
            font-weight: 700;
            letter-spacing: 0.01em;
            padding: 7px 8px;
            border-radius: 6px;
            color: #14213d;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 3px;
            line-height: 1.2;
        }
        @media (min-width: 1360px) {
            .ux-nav-item {
                font-size: 12.2px;
                padding: 8px 10px;
            }
        }
        .ux-nav-item:hover, .ux-nav-item.active {
            color: #c88a2b;
            background-color: rgba(200, 138, 43, 0.08);
        }

        /* Dropdown menu chuẩn Flatsome */
        .ux-dropdown {
            position: relative;
        }
        .ux-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-top: 3px solid #c88a2b;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
            padding: 6px 0;
        }
        .ux-dropdown:hover .ux-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .ux-dropdown-link {
            display: block;
            padding: 8px 14px;
            font-size: 12px;
            font-weight: 600;
            color: #334155;
            white-space: nowrap;
            transition: all 0.15s ease;
        }
        .ux-dropdown-link:hover {
            background-color: #f8fafc;
            color: #c88a2b;
            padding-left: 18px;
        }

        /* Nút danh mục lọc ở trang chủ nhỏ gọn, không xuống dòng chữ bên trong */
        .ux-cat-pill {
            white-space: nowrap !important;
            font-size: 11.5px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background-color: #ffffff;
            color: #1e293b;
            transition: all 0.2s ease;
            cursor: pointer;
            line-height: 1.2;
        }
        @media (max-width: 640px) {
            .ux-cat-pill {
                font-size: 11px;
                padding: 5px 9px;
            }
        }
        .ux-cat-pill:hover, .ux-cat-pill.active {
            background-color: #14213d;
            border-color: #14213d;
            color: #ffffff;
        }

        /* Tiêu đề Section chuẩn Flatsome (section-title-center) */
        .ux-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            width: 100%;
            margin-bottom: 8px;
        }
        .ux-section-title::before,
        .ux-section-title::after {
            content: "";
            flex: 1;
            max-width: 110px;
            height: 2px;
            background-color: #c88a2b;
            opacity: 0.45;
        }

        /* Card sản phẩm / công trình chuẩn Flatsome Box: Tên không bị cắt chữ, không tràn viền */
        .ux-product-card {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .ux-product-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -5px rgba(20, 33, 61, 0.12);
            border-color: #c88a2b;
        }
        .ux-product-title {
            white-space: normal !important;
            word-break: break-word;
            overflow-wrap: break-word;
            overflow: visible !important;
            text-overflow: clip !important;
            display: block !important;
            line-height: 1.38;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(200, 138, 43, 0.65); }
            70% { box-shadow: 0 0 0 12px rgba(200, 138, 43, 0); }
            100% { box-shadow: 0 0 0 0 rgba(200, 138, 43, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>

    <!-- Hàm tự động xử lý đa luồng ảnh Google Drive để luôn hiển thị sắc nét -->
    <script>
        function handleDriveImageFallback(imgEl, fileId, labelText) {
            const currentStep = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            if (currentStep === 0) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (currentStep === 1) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else if (currentStep === 2) {
                imgEl.setAttribute('data-fallback-step', '3');
                const safeText = encodeURIComponent(labelText || 'THIETKEMAUNHA.COM');
                imgEl.src = 'https://placehold.co/800x600/14213d/e0a445?text=' + safeText;
            }
        }
    </script>
</head>

<body class="bg-white text-slate-800 antialiased selection:bg-brand-gold selection:text-white">

    <!-- =====================================================================
         [FLATSOME WRAPPER] - CẤU TRÚC ĐƠN GIẢN CHUẨN UX BUILDER FLATSOME
    ====================================================================== -->
    <div id="wrapper" class="w-full overflow-x-hidden">

        <!-- =================================================================
             1. HEADER (#header) - TOP BAR + MASTHEAD (KHÔNG ĐỂ NÚT GỌI NGAY TRÊN HEADER)
        ================================================================== -->
        <header id="header" class="sticky top-0 z-50 bg-white shadow-sm border-b border-slate-200">
            
            <!-- Top Bar (#top-bar) -->
            <div id="top-bar" class="bg-brand-dark text-white text-[11px] sm:text-xs py-1.5">
                <div class="ux-container flex flex-wrap items-center justify-between gap-2">
                    <div class="flex items-center gap-3 sm:gap-5 truncate">
                        <span class="inline-flex items-center gap-1.5 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-goldLight"></i>
                            <span>261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng</span>
                        </span>
                        <span class="hidden md:inline-flex items-center gap-1.5 text-slate-300">
                            <i class="fa-solid fa-envelope text-brand-goldLight"></i>
                            <span>ctythietkemaunha@gmail.com</span>
                        </span>
                    </div>
                    <div class="flex items-center gap-3 sm:gap-4 ml-auto">
                        <span class="inline-flex items-center gap-1 font-semibold text-brand-goldLight">
                            <i class="fa-solid fa-globe"></i>
                            <span>thietkemaunha.com</span>
                        </span>
                        <span class="hidden sm:inline text-slate-400">|</span>
                        <span class="hidden sm:inline text-slate-200">MST: 0401905630</span>
                        <a href="https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldLight transition-colors" title="Fanpage Facebook">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                    </div>
                </div>
            </div>

            <!-- Header Main (#masthead) - Logo chỉnh gọn nhỏ lại & Menu 1 hàng chữ nhỏ gọn, KHÔNG để nút gọi ngay -->
            <div id="masthead" class="bg-white py-2">
                <div class="ux-container flex items-center justify-between gap-2">
                    
                    <!-- Logo công ty (chỉnh gọn nhỏ lại) -->
                    <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" title="CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ">
                        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-md border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w300" 
                                onerror="handleDriveImageFallback(this, '1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj', 'LOGO')"
                                alt="Logo Công ty TNHH Xây dựng Thiết kế Mẫu Nhà" 
                                class="max-h-9 sm:max-h-10 w-auto object-contain"
                            >
                        </div>
                        <div class="leading-tight">
                            <span class="block font-heading font-extrabold text-[11px] sm:text-xs md:text-[13px] text-brand-dark tracking-tight group-hover:text-brand-gold transition-colors">
                                XÂY DỰNG THIẾT KẾ MẪU NHÀ
                            </span>
                            <span class="block text-[10px] text-brand-gold font-semibold tracking-wider">
                                thietkemaunha.com
                            </span>
                        </div>
                    </a>

                    <!-- Danh mục Menu trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng (hoặc xuống hàng 2 nguyên cụm), không xuống dòng tên danh mục -->
                    <nav class="hidden lg:block flex-1 pl-2" aria-label="Menu chính">
                        <ul class="ux-nav-list">
                            <li>
                                <a href="#trang-chu" class="ux-nav-item active">TRANG CHỦ</a>
                            </li>
                            <li>
                                <a href="#gioi-thieu" class="ux-nav-item">GIỚI THIỆU</a>
                            </li>
                            <li class="ux-dropdown">
                                <a href="#cong-trinh-thuc-te" class="ux-nav-item">
                                    <span>CÔNG TRÌNH THỰC TẾ</span>
                                    <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                                </a>
                                <div class="ux-dropdown-menu">
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="ux-dropdown-link">Khách sạn – Căn hộ – Phòng trọ</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="ux-dropdown-link">Biệt thự</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="ux-dropdown-link">Nhà phố</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="ux-dropdown-link">Văn phòng</a>
                                </div>
                            </li>
                            <li class="ux-dropdown">
                                <a href="#linh-vuc-hoat-dong" class="ux-nav-item">
                                    <span>LĨNH VỰC HOẠT ĐỘNG</span>
                                    <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                                </a>
                                <div class="ux-dropdown-menu">
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('thiet-ke')" class="ux-dropdown-link">Thiết kế Kiến trúc – Nội thất</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('phan-tho')" class="ux-dropdown-link">Thi công phần thô</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('hoan-thien')" class="ux-dropdown-link">Thi công hoàn thiện</a>
                                    <a href="#cong-trinh-thuc-te" onclick="filterConstruction('noi-that')" class="ux-dropdown-link">Thi công nội thất</a>
                                </div>
                            </li>
                            <li class="ux-dropdown">
                                <a href="#du-an-da-nang" class="ux-nav-item">
                                    <span>MẪU THIẾT KẾ</span>
                                    <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                                </a>
                                <div class="ux-dropdown-menu">
                                    <a href="#du-an-da-nang" onclick="filterDanangProjects('nha-pho')" class="ux-dropdown-link">Mẫu thiết kế nhà phố</a>
                                    <a href="#du-an-da-nang" onclick="filterDanangProjects('biet-thu')" class="ux-dropdown-link">Mẫu thiết kế biệt thự</a>
                                    <a href="#du-an-da-nang" onclick="filterDanangProjects('noi-that')" class="ux-dropdown-link">Mẫu thiết kế nội thất</a>
                                </div>
                            </li>
                            <li>
                                <a href="#du-an-da-nang" class="ux-nav-item">DỰ ÁN ĐÀ NẴNG</a>
                            </li>
                            <li class="ux-dropdown">
                                <a href="#bao-gia" class="ux-nav-item">
                                    <span>BÁO GIÁ</span>
                                    <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                                </a>
                                <div class="ux-dropdown-menu">
                                    <a href="#bao-gia" class="ux-dropdown-link">Báo giá thiết kế kiến trúc</a>
                                    <a href="#bao-gia" class="ux-dropdown-link">Báo giá thi công phần thô</a>
                                    <a href="#bao-gia" class="ux-dropdown-link">Báo giá thi công hoàn thiện</a>
                                    <a href="#bao-gia" class="ux-dropdown-link">Báo giá thi công trọn gói</a>
                                </div>
                            </li>
                            <li>
                                <a href="#doi-tac" class="ux-nav-item">ĐỐI TÁC</a>
                            </li>
                            <li>
                                <a href="#tin-tuc" class="ux-nav-item">TIN TỨC</a>
                            </li>
                            <li>
                                <a href="#lien-he" class="ux-nav-item">LIÊN HỆ</a>
                            </li>
                        </ul>
                    </nav>

                    <!-- Nút mở Menu trên Điện thoại / Tablet -->
                    <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center p-2 rounded-md text-brand-dark hover:bg-slate-100 focus:outline-none" aria-label="Mở danh mục">
                        <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                    </button>
                </div>

                <!-- Menu Danh mục trên Điện thoại (ổn định, gọn đẹp) -->
                <div id="mobile-menu-panel" class="hidden lg:hidden border-t border-slate-200 bg-white mt-2">
                    <div class="ux-container py-3 grid grid-cols-2 sm:grid-cols-3 gap-1.5">
                        <a href="#trang-chu" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Trang chủ</a>
                        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Giới thiệu</a>
                        <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Công trình thực tế</a>
                        <a href="#linh-vuc-hoat-dong" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Lĩnh vực hoạt động</a>
                        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Mẫu thiết kế</a>
                        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Dự án Đà Nẵng</a>
                        <a href="#bao-gia" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Báo giá xây dựng</a>
                        <a href="#doi-tac" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Đối tác vật tư</a>
                        <a href="#tin-tuc" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-brand-dark font-bold text-xs whitespace-nowrap">Tin tức</a>
                        <a href="#lien-he" onclick="closeMobileMenu()" class="px-3 py-2 rounded bg-brand-gold text-white font-bold text-xs whitespace-nowrap text-center">Liên hệ & Bản đồ</a>
                    </div>
                </div>
            </div>
        </header>

        <!-- =================================================================
             MAIN CONTENT (#main) - CÁC SECTION UX BUILDER FLATSOME
        ================================================================== -->
        <main id="main">

            <!-- =============================================================
                 [UX SECTION 1: SLIDER 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP]
                 - 2 ảnh kích thước bằng nhau
                 - Hình ảnh và chữ nằm gọn bên trong banner, cách xa viền
                 - Không bị thiếu chữ trên cả điện thoại và máy tính
            ============================================================== -->
            <section id="trang-chu" class="py-3 sm:py-4 bg-brand-bgSoft">
                <div class="ux-container">
                    <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-brand-dark">
                        
                        <!-- Vùng chứa 2 Slide kích thước bằng nhau tuyệt đối -->
                        <div id="banner-slider" class="relative w-full h-[300px] sm:h-[370px] md:h-[430px]">
                            
                            <!-- SLIDE 1 -->
                            <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 flex items-center">
                                <!-- Ảnh nền banner 1 -->
                                <img 
                                    src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400" 
                                    onerror="handleDriveImageFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'BANNER+1')"
                                    alt="Banner Công ty TNHH Xây dựng Thiết kế Mẫu Nhà 1" 
                                    class="absolute inset-0 w-full h-full object-cover object-center opacity-35"
                                >
                                <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-dark/85 to-brand-dark/70"></div>

                                <!-- Nội dung chữ & hình nằm hoàn toàn trong banner, cách xa viền (px-10 sm:px-16 md:px-20) -->
                                <div class="relative z-10 w-full h-full px-10 sm:px-16 md:px-20 py-6 sm:py-10 flex flex-col md:flex-row items-center justify-between gap-4 sm:gap-8">
                                    <div class="w-full md:w-7/12 text-center md:text-left">
                                        <p class="text-brand-goldLight font-bold text-[11px] sm:text-xs md:text-sm uppercase tracking-wider mb-1.5">
                                            thietkemaunha.com • MST: 0401905630
                                        </p>
                                        <h1 class="font-heading font-extrabold text-white text-base sm:text-xl md:text-3xl lg:text-4xl leading-snug mb-2 sm:mb-3">
                                            CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ
                                        </h1>
                                        <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-3 sm:mb-5">
                                            Chuyên Thiết Kế Kiến Trúc – Thi Công Xây Dựng Trọn Gói – Nội Thất Nhà Phố, Biệt Thự, Khách Sạn, Căn Hộ Uy Tín Tại TP Đà Nẵng.
                                        </p>
                                        <div class="flex flex-wrap items-center justify-center md:justify-start gap-2 sm:gap-3">
                                            <a href="#form-bao-gia" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm transition-colors shadow">
                                                Đăng Ký Tư Vấn & Báo Giá
                                            </a>
                                            <span class="px-3 py-2 rounded-lg bg-white/10 text-white font-semibold text-xs sm:text-sm border border-white/20">
                                                Hotline: 0931.999.334
                                            </span>
                                        </div>
                                    </div>
                                    <!-- Khung ảnh thực tế nằm gọn bên trong phải banner -->
                                    <div class="hidden md:flex md:w-5/12 justify-center">
                                        <div class="w-full max-w-[340px] h-[240px] rounded-lg overflow-hidden border-2 border-brand-goldLight shadow-xl bg-slate-900">
                                            <img 
                                                src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800" 
                                                onerror="handleDriveImageFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'CONG+TRINH+DA+NANG')"
                                                alt="Thiết kế thi công nhà đẹp Đà Nẵng" 
                                                class="w-full h-full object-cover"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!-- SLIDE 2 (Kích thước bằng đúng Slide 1) -->
                            <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 flex items-center">
                                <!-- Ảnh nền banner 2 -->
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1400" 
                                    onerror="handleDriveImageFallback(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'BANNER+2')"
                                    alt="Banner Công ty TNHH Xây dựng Thiết kế Mẫu Nhà 2" 
                                    class="absolute inset-0 w-full h-full object-cover object-center opacity-35"
                                >
                                <div class="absolute inset-0 bg-gradient-to-r from-slate-900/95 via-brand-dark/85 to-slate-900/75"></div>

                                <!-- Nội dung chữ & hình nằm hoàn toàn trong banner, cách xa viền (px-10 sm:px-16 md:px-20) -->
                                <div class="relative z-10 w-full h-full px-10 sm:px-16 md:px-20 py-6 sm:py-10 flex flex-col md:flex-row items-center justify-between gap-4 sm:gap-8">
                                    <div class="w-full md:w-7/12 text-center md:text-left">
                                        <p class="text-brand-goldLight font-bold text-[11px] sm:text-xs md:text-sm uppercase tracking-wider mb-1.5">
                                            NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH
                                        </p>
                                        <h2 class="font-heading font-extrabold text-white text-base sm:text-xl md:text-3xl lg:text-4xl leading-snug mb-2 sm:mb-3">
                                            XÂY NHÀ TRỌN GÓI – CHÌA KHÓA TRAO TAY
                                        </h2>
                                        <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-3 sm:mb-5">
                                            Cam kết An Toàn – Chất Lượng – Đúng Tiến Độ – Chi Phí Minh Bạch. Trụ sở: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng.
                                        </p>
                                        <div class="flex flex-wrap items-center justify-center md:justify-start gap-2 sm:gap-3">
                                            <a href="#cong-trinh-thuc-te" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm transition-colors shadow">
                                                Xem Công Trình Thực Tế
                                            </a>
                                            <a href="#du-an-da-nang" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs sm:text-sm border border-white/25 transition-colors">
                                                Dự Án Tại Đà Nẵng
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Khung ảnh thực tế nằm gọn bên trong phải banner -->
                                    <div class="hidden md:flex md:w-5/12 justify-center">
                                        <div class="w-full max-w-[340px] h-[240px] rounded-lg overflow-hidden border-2 border-brand-goldLight shadow-xl bg-slate-900">
                                            <img 
                                                src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800" 
                                                onerror="handleDriveImageFallback(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'BIET+THU+NHA+PHO')"
                                                alt="Thi công xây dựng trọn gói Đà Nẵng" 
                                                class="w-full h-full object-cover"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!-- Nút điều hướng trái / phải nằm sát mép ngoài, không đè vào chữ -->
                            <button type="button" onclick="prevBannerSlide()" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Slide trước">
                                <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                            </button>
                            <button type="button" onclick="nextBannerSlide()" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Slide tiếp">
                                <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                            </button>

                            <!-- Chấm chỉ báo 2 banner -->
                            <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                                <button type="button" onclick="goToBannerSlide(0)" id="banner-dot-0" class="w-6 h-2 rounded-full bg-brand-gold transition-all" aria-label="Banner 1"></button>
                                <button type="button" onclick="goToBannerSlide(1)" id="banner-dot-1" class="w-2.5 h-2 rounded-full bg-white/50 transition-all" aria-label="Banner 2"></button>
                            </div>
                        </div>

                    </div>
                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 2: DỊCH VỤ TIÊU BIỂU & GIỚI THIỆU CÔNG TY]
                 (Thiết kế giống cấu trúc trang mẫu tintruongthinh.com)
            ============================================================== -->
            <section id="gioi-thieu" class="py-8 sm:py-12 bg-white">
                <div class="ux-container">
                    
                    <!-- 3 Khối Dịch Vụ Tiêu Biểu: THIẾT KẾ - THI CÔNG - NỘI THẤT -->
                    <div id="linh-vuc-hoat-dong" class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6 mb-10">
                        <div class="p-5 sm:p-6 rounded-xl border border-slate-200 bg-brand-bgSoft hover:border-brand-gold transition-all flex items-start gap-4">
                            <div class="w-12 h-12 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-xl">
                                <i class="fa-solid fa-compass-drafting"></i>
                            </div>
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark mb-1">THIẾT KẾ KIẾN TRÚC</h3>
                                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                    Thiết kế hồ sơ kỹ thuật thi công, phối cảnh 3D kiến trúc Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê tối ưu công năng & phong thủy.
                                </p>
                            </div>
                        </div>

                        <div class="p-5 sm:p-6 rounded-xl border border-slate-200 bg-brand-bgSoft hover:border-brand-gold transition-all flex items-start gap-4">
                            <div class="w-12 h-12 rounded-lg bg-brand-gold text-white flex items-center justify-center shrink-0 text-xl">
                                <i class="fa-solid fa-helmet-safety"></i>
                            </div>
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark mb-1">THI CÔNG XÂY DỰNG</h3>
                                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                    Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay đúng tiêu chuẩn kỹ thuật, vật tư chính hãng.
                                </p>
                            </div>
                        </div>

                        <div class="p-5 sm:p-6 rounded-xl border border-slate-200 bg-brand-bgSoft hover:border-brand-gold transition-all flex items-start gap-4">
                            <div class="w-12 h-12 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-xl">
                                <i class="fa-solid fa-couch"></i>
                            </div>
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark mb-1">THIẾT KẾ & THI CÔNG NỘI THẤT</h3>
                                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                    Sản xuất và lắp đặt nội thất gỗ công nghiệp An Cường, gỗ tự nhiên cho phòng khách, bếp, phòng ngủ, văn phòng hiện đại.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Giới thiệu CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ -->
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center bg-brand-bgSoft p-5 sm:p-8 rounded-xl border border-slate-200">
                        <div class="lg:col-span-7">
                            <p class="text-xs font-bold uppercase tracking-wider text-brand-gold mb-1">VỀ CHÚNG TÔI • thietkemaunha.com</p>
                            <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-brand-dark mb-3">
                                CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ
                            </h2>
                            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                                <strong>CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ</strong> (Tên quốc tế: <em>HOME DESIGN CONSTRUCTION CO.,LTD</em> - Mã số thuế: <strong>0401905630</strong> - Chứng chỉ năng lực HĐXD: <strong>00038607</strong>) chuyên Thiết kế – Xây dựng – Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng và khu vực miền Trung.
                            </p>
                            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                                Với tiêu chí <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt chữ <strong>“TÂM”</strong> và <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình luôn đạt kết quả: <strong>AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG</strong>.
                            </p>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs sm:text-sm text-slate-700 mb-4">
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                    <span><strong>Trụ sở:</strong> 261 Nguyễn Sinh Sắc, P. Hòa Khánh, Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                    <span><strong>Hotline/Zalo:</strong> 0931.999.334</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                    <span><strong>Website:</strong> thietkemaunha.com</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                    <span><strong>Bảo hành kết cấu:</strong> Lên đến 10 năm</span>
                                </div>
                            </div>
                        </div>

                        <div class="lg:col-span-5">
                            <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm bg-white p-2">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w900" 
                                    onerror="handleDriveImageFallback(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI+CONG+THUC+TE')"
                                    alt="Thi công thực tế Công ty TNHH Xây dựng Thiết kế Mẫu Nhà" 
                                    class="w-full h-56 sm:h-64 object-cover rounded-lg"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- 6 Thế mạnh của chúng tôi (Giống web mẫu tintruongthinh.com) -->
                    <div class="mt-10">
                        <div class="ux-section-title">
                            <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                                THẾ MẠNH CỦA CHÚNG TÔI
                            </h2>
                        </div>
                        <p class="text-center text-xs sm:text-sm text-slate-600 mb-6">
                            6 giá trị cốt lõi tạo nên uy tín của CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ tại Đà Nẵng
                        </p>

                        <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-user-tie"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Đội ngũ KTS, kỹ sư chuyên nghiệp</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    Đội ngũ kiến trúc sư sáng tạo, kỹ sư xây dựng giàu kinh nghiệm thực chiến và đội thợ lành nghề tại Đà Nẵng.
                                </p>
                            </div>

                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-layer-group"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Cập nhật xu hướng mới nhất</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    Ứng dụng giải pháp kiến trúc xanh, thông tầng, lấy sáng tự nhiên và vật liệu xây dựng hiện đại, bền vững.
                                </p>
                            </div>

                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-clipboard-check"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Giám sát tiến độ chuẩn xác</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    Kỹ sư giám sát trực tiếp tại hiện trường, báo cáo hình ảnh thi công từng giai đoạn để chủ đầu tư dễ dàng theo dõi.
                                </p>
                            </div>

                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-shield-halved"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Bảo hành công trình lâu dài</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    “Gọi đâu có đó” – cam kết đồng hành bảo hành kết cấu và chống thấm dài hạn, tận tâm sau khi bàn giao nhà.
                                </p>
                            </div>

                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-scale-balanced"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Giá cả hợp lý phải chăng</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    Dự toán bóc tách rõ ràng từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng, tối ưu ngân sách.
                                </p>
                            </div>

                            <div class="p-4 sm:p-5 rounded-xl border border-slate-200 bg-white hover:border-brand-gold transition-all">
                                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center mb-3 text-sm sm:text-base">
                                    <i class="fa-solid fa-headset"></i>
                                </div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">Hỗ trợ tư vấn miễn phí 24/7</h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                    Tư vấn khảo sát mặt bằng, xin phép xây dựng và lên phương án thiết kế sơ bộ hoàn toàn miễn phí qua 0931.999.334.
                                </p>
                            </div>
                        </div>
                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 3: 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG & DANH MỤC SẢN PHẨM]
                 - Lấy đúng 9 ảnh thực tế thi công từ Google Drive
                 - Phân loại đúng danh mục của web mẫu tintruongthinh.com
                 - Chia thành 2 cột trên điện thoại (grid-cols-2), không để nhãn dán trên ảnh
                 - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
            ============================================================== -->
            <section id="cong-trinh-thuc-te" class="py-8 sm:py-12 bg-brand-bgSoft border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            CÔNG TRÌNH THỰC TẾ & HẠNG MỤC THI CÔNG
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-5">
                        Hình ảnh thực tế thi công xây dựng & hoàn thiện tại công trường của CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ
                    </p>

                    <!-- Thanh nút danh mục trang chủ nhỏ gọn, đẹp trên cả máy tính và điện thoại -->
                    <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6" id="construction-filter-bar">
                        <button type="button" onclick="filterConstruction('all')" data-cat="all" class="ux-cat-pill active">Tất cả (9)</button>
                        <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="ux-cat-pill">Nhà phố</button>
                        <button type="button" onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="ux-cat-pill">Biệt thự</button>
                        <button type="button" onclick="filterConstruction('khach-san')" data-cat="khach-san" class="ux-cat-pill">Khách sạn – Căn hộ – Phòng trọ</button>
                        <button type="button" onclick="filterConstruction('van-phong')" data-cat="van-phong" class="ux-cat-pill">Văn phòng</button>
                        <button type="button" onclick="filterConstruction('phan-tho')" data-cat="phan-tho" class="ux-cat-pill">Thi công phần thô</button>
                        <button type="button" onclick="filterConstruction('hoan-thien')" data-cat="hoan-thien" class="ux-cat-pill">Thi công hoàn thiện</button>
                        <button type="button" onclick="filterConstruction('noi-that')" data-cat="noi-that" class="ux-cat-pill">Thi công nội thất</button>
                    </div>

                    <!-- Grid 9 sản phẩm / công trình thực tế: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính -->
                    <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                        
                        <!-- Thực tế 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                        <article class="ux-product-card construction-item" data-categories="nha-pho phan-tho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w800" 
                                    onerror="handleDriveImageFallback(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI+CONG+THUC+TE+01')"
                                    alt="Thi công phần thô & kết cấu nhà phố hiện đại tại Hòa Khánh" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Thi công phần thô • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công phần thô & kết cấu bê tông cốt thép nhà phố 3 tầng Hòa Khánh
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                        <article class="ux-product-card construction-item" data-categories="nha-pho phan-tho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800" 
                                    onerror="handleDriveImageFallback(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'THI+CONG+THUC+TE+02')"
                                    alt="Thi công móng, đà kiềng và sàn bê tông nhà phố Liên Chiểu" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Thi công phần thô • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công cốt thép dầm sàn & đổ bê tông tươi thương phẩm nhà phố Liên Chiểu
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                        <article class="ux-product-card construction-item" data-categories="biet-thu phan-tho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800" 
                                    onerror="handleDriveImageFallback(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'THI+CONG+THUC+TE+03')"
                                    alt="Thi công xây tường gạch tuynel và khung kết cấu biệt thự" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Biệt thự • Thi công phần thô</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công xây tường bao & khung kết cấu biệt thự phố 2 mặt tiền tại Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                        <article class="ux-product-card construction-item" data-categories="khach-san phan-tho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800" 
                                    onerror="handleDriveImageFallback(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'THI+CONG+THUC+TE+04')"
                                    alt="Thi công kết cấu công trình căn hộ cho thuê & khách sạn" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Khách sạn – Căn hộ – Phòng trọ</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công thực tế tòa nhà căn hộ dịch vụ cho thuê cao tầng tại Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                        <article class="ux-product-card construction-item" data-categories="nha-pho hoan-thien">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800" 
                                    onerror="handleDriveImageFallback(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO', 'THI+CONG+THUC+TE+05')"
                                    alt="Thi công hoàn thiện mặt tiền và chống thấm công trình nhà phố" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Thi công hoàn thiện • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công tô trát, ốp lát & hoàn thiện mặt tiền nhà phố hiện đại Nguyễn Sinh Sắc
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                        <article class="ux-product-card construction-item" data-categories="biet-thu hoan-thien">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800" 
                                    onerror="handleDriveImageFallback(this, '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t', 'THI+CONG+THUC+TE+06')"
                                    alt="Thi công hoàn thiện ngoại thất và hệ cửa nhôm kính biệt thự" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Biệt thự • Thi công hoàn thiện</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công hoàn thiện sơn bả ngoại thất & lắp đặt nhôm kính biệt thự Hòa Xuân
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                        <article class="ux-product-card construction-item" data-categories="van-phong hoan-thien">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w800" 
                                    onerror="handleDriveImageFallback(this, '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_', 'THI+CONG+THUC+TE+07')"
                                    alt="Thi công hệ thống cơ điện M&E và trần thạch cao văn phòng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Văn phòng • Thi công hoàn thiện</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công trọn gói văn phòng kết hợp nhà ở gia đình tại quận Hải Châu
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                        <article class="ux-product-card construction-item" data-categories="noi-that nha-pho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w800" 
                                    onerror="handleDriveImageFallback(this, '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT', 'THI+CONG+THUC+TE+08')"
                                    alt="Thi công lắp đặt nội thất phòng khách và tủ bếp hiện đại" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Thi công nội thất • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Thi công hoàn thiện nội thất gỗ phòng khách – bếp nhà phố trọn gói Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                        <!-- Thực tế 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                        <article class="ux-product-card construction-item" data-categories="noi-that khach-san thiet-ke">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w800" 
                                    onerror="handleDriveImageFallback(this, '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn', 'THI+CONG+THUC+TE+09')"
                                    alt="Bàn giao công trình xây dựng trọn gói nhà phố & nội thất tại Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs font-semibold text-brand-gold mb-1">Thiết kế & Thi công trọn gói</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Nghiệm thu & bàn giao công trình xây nhà trọn gói chìa khóa trao tay tại Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-600">
                                    <span>Đà Nẵng</span>
                                    <a href="#form-bao-gia" class="font-bold text-brand-dark hover:text-brand-gold">Nhận báo giá</a>
                                </div>
                            </div>
                        </article>

                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 4: DANH MỤC 10 DỰ ÁN Ở ĐÀ NẴNG VÀO TRANG CHỦ]
                 - Lấy đúng 10 ảnh dự án Đà Nẵng từ Google Drive
                 - Chia thành 2 cột trên điện thoại (grid-cols-2), không để nhãn dán
                 - Tên sản phẩm/dự án đầy đủ, không bị tràn hoặc thiếu chữ
            ============================================================== -->
            <section id="du-an-da-nang" class="py-8 sm:py-12 bg-white border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-5">
                        Bộ sưu tập mẫu thiết kế kiến trúc & dự án tiêu biểu do CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ thực hiện tại TP Đà Nẵng
                    </p>

                    <!-- Thanh nút lọc danh mục dự án Đà Nẵng nhỏ gọn -->
                    <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6" id="danang-filter-bar">
                        <button type="button" onclick="filterDanangProjects('all')" data-dncat="all" class="ux-cat-pill active">Tất cả dự án Đà Nẵng (10)</button>
                        <button type="button" onclick="filterDanangProjects('nha-pho')" data-dncat="nha-pho" class="ux-cat-pill">Mẫu thiết kế nhà phố</button>
                        <button type="button" onclick="filterDanangProjects('biet-thu')" data-dncat="biet-thu" class="ux-cat-pill">Mẫu thiết kế biệt thự</button>
                        <button type="button" onclick="filterDanangProjects('khach-san')" data-dncat="khach-san" class="ux-cat-pill">Khách sạn – Căn hộ</button>
                        <button type="button" onclick="filterDanangProjects('noi-that')" data-dncat="noi-that" class="ux-cat-pill">Mẫu thiết kế nội thất</button>
                    </div>

                    <!-- Grid 10 Dự Án tại Đà Nẵng: 2 cột trên điện thoại (grid-cols-2), 5 cột trên màn hình lớn -->
                    <div id="danang-projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                        
                        <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                        <article class="ux-product-card danang-project-item" data-dncategories="nha-pho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800" 
                                    onerror="handleDriveImageFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'DU+AN+DA+NANG+01')"
                                    alt="Dự án Nhà phố hiện đại 3 tầng tại Hòa Khánh, Liên Chiểu, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Nhà phố hiện đại 3 tầng mặt tiền Nguyễn Sinh Sắc – P. Hòa Khánh, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Gia đình Anh Minh • Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                        <article class="ux-product-card danang-project-item" data-dncategories="biet-thu">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800" 
                                    onerror="handleDriveImageFallback(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'DU+AN+DA+NANG+02')"
                                    alt="Dự án Biệt thự phố nghỉ dưỡng tại KĐT Hòa Xuân, Cẩm Lệ, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Biệt thự</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Biệt thự phố hiện đại 3 tầng Khu đô thị sinh thái Hòa Xuân – Cẩm Lệ, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Gia đình Anh Bình • Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                        <article class="ux-product-card danang-project-item" data-dncategories="nha-pho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800" 
                                    onerror="handleDriveImageFallback(this, '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz', 'DU+AN+DA+NANG+03')"
                                    alt="Dự án Nhà phố lệch tầng thông thoáng tại Quận Hải Châu, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Thiết kế & thi công nhà phố 3 tầng kiến trúc xanh tại Quận Hải Châu, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Chị Hương • Hải Châu, Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                        <article class="ux-product-card danang-project-item" data-dncategories="khach-san">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800" 
                                    onerror="handleDriveImageFallback(this, '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k', 'DU+AN+DA+NANG+04')"
                                    alt="Dự án Căn hộ cho thuê kết hợp nhà ở tại Quận Sơn Trà, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Khách sạn – Căn hộ • Đà Nẵng</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Tòa nhà căn hộ Apartment & Homestay cao cấp gần biển Sơn Trà, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Anh Tuấn • Sơn Trà, Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                        <article class="ux-product-card danang-project-item" data-dncategories="biet-thu">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w800" 
                                    onerror="handleDriveImageFallback(this, '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N', 'DU+AN+DA+NANG+05')"
                                    alt="Dự án Biệt thự 2 mặt tiền sang trọng tại Khu Nam Việt Á, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Biệt thự</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Biệt thự 2 mặt tiền phong cách hiện đại tại Khu đô thị Nam Việt Á, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Anh Quang • Ngũ Hành Sơn, Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                        <article class="ux-product-card danang-project-item" data-dncategories="nha-pho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w800" 
                                    onerror="handleDriveImageFallback(this, '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML', 'DU+AN+DA+NANG+06')"
                                    alt="Dự án Nhà phố 2 tầng 1 tum tối ưu chi phí tại Khu Phước Lý, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Mẫu nhà phố 2 tầng 1 tum trẻ trung tại Khu đô thị Phước Lý – Liên Chiểu, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Gia đình Anh Phong • Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                        <article class="ux-product-card danang-project-item" data-dncategories="nha-pho noi-that">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w800" 
                                    onerror="handleDriveImageFallback(this, '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF', 'DU+AN+DA+NANG+07')"
                                    alt="Dự án Nhà phố kết hợp kinh doanh tại Quận Thanh Khê, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Nhà phố • Nội thất Đà Nẵng</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Nhà phố 4 tầng kết hợp văn phòng kinh doanh tại Quận Thanh Khê, TP Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Chị Ly • Thanh Khê, Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                        <article class="ux-product-card danang-project-item" data-dncategories="biet-thu noi-that">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w800" 
                                    onerror="handleDriveImageFallback(this, '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A', 'DU+AN+DA+NANG+08')"
                                    alt="Dự án Biệt thự sân vườn mái Nhật tại Hòa Minh, Liên Chiểu, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Biệt thự</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Biệt thự vườn mái Nhật sang trọng tại Phường Hòa Minh – Liên Chiểu, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Gia đình Anh Lộc • Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                        <article class="ux-product-card danang-project-item" data-dncategories="khach-san noi-that">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80=w800" 
                                    onerror="handleDriveImageFallback(this, '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80', 'DU+AN+DA+NANG+09')"
                                    alt="Dự án Thiết kế & thi công nội thất căn hộ cao cấp tại Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Mẫu thiết kế nội thất • Đà Nẵng</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Thiết kế & thi công trọn gói nội thất căn hộ nghỉ dưỡng view sông Hàn, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Chị Anh Thư • Đà Nẵng
                                </div>
                            </div>
                        </article>

                        <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                        <article class="ux-product-card danang-project-item" data-dncategories="nha-pho">
                            <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4=w800" 
                                    onerror="handleDriveImageFallback(this, '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4', 'DU+AN+DA+NANG+10')"
                                    alt="Dự án Nhà phố 3 tầng mặt tiền 5m hiện đại tại Hòa Khánh, Đà Nẵng" 
                                    class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-[11px] font-semibold text-brand-gold mb-1">Dự án Đà Nẵng • Nhà phố</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-[13px] text-brand-dark">
                                        Nhà phố 3 tầng mặt tiền 5m có gara ô tô tại KĐT Golden Hills – Hòa Khánh, Đà Nẵng
                                    </h3>
                                </div>
                                <div class="mt-2 pt-2 border-t border-slate-100 text-[10px] sm:text-xs text-slate-500">
                                    CĐT: Gia đình Anh Hùng • Đà Nẵng
                                </div>
                            </div>
                        </article>

                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 5: BÁO GIÁ XÂY DỰNG & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ]
                 - Lấy đúng 4 danh mục Báo giá từ web mẫu tintruongthinh.com
                 - Form "MIỄN PHÍ TƯ VẤN & BÁO GIÁ" giống web mẫu tintruongthinh.com
            ============================================================== -->
            <section id="bao-gia" class="py-8 sm:py-12 bg-brand-bgSoft border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG ĐÀ NẴNG
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-6">
                        Đơn giá minh bạch, vật tư chính hãng – Miễn phí 100% hồ sơ thiết kế và giấy phép xây dựng khi ký hợp đồng thi công trọn gói
                    </p>

                    <!-- 4 Gói Báo Giá chuẩn danh mục tintruongthinh.com (Chia 2 cột trên điện thoại, 4 cột trên máy tính) -->
                    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mb-10">
                        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition-all">
                            <div>
                                <p class="text-[11px] font-bold uppercase text-brand-gold mb-1">Danh mục báo giá 01</p>
                                <h3 class="ux-product-title font-heading font-bold text-xs sm:text-base text-brand-dark mb-2">
                                    Báo giá thiết kế kiến trúc
                                </h3>
                                <p class="text-sm sm:text-lg font-extrabold text-brand-goldDark mb-3">
                                    120.000đ – 180.000đ/m²
                                </p>
                                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                                    <li>• Hồ sơ kiến trúc & phối cảnh 3D mặt tiền</li>
                                    <li>• Hồ sơ kết cấu, điện nước M&E chi tiết</li>
                                    <li>• Bố trí mặt bằng công năng chuẩn phong thủy</li>
                                    <li>• Giảm 100% khi thi công trọn gói</li>
                                </ul>
                            </div>
                            <a href="#form-bao-gia" onclick="selectPackage('Báo giá thiết kế kiến trúc')" class="block w-full py-2 text-center rounded-lg bg-brand-dark hover:bg-brand-gold text-white font-bold text-xs transition-colors">
                                Nhận Báo Giá Chi Tiết
                            </a>
                        </div>

                        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition-all">
                            <div>
                                <p class="text-[11px] font-bold uppercase text-brand-gold mb-1">Danh mục báo giá 02</p>
                                <h3 class="ux-product-title font-heading font-bold text-xs sm:text-base text-brand-dark mb-2">
                                    Báo giá thi công phần thô
                                </h3>
                                <p class="text-sm sm:text-lg font-extrabold text-brand-goldDark mb-3">
                                    3.500.000đ – 3.900.000đ/m²
                                </p>
                                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                                    <li>• Vật tư chuẩn: Thép Hòa Phát, Xi măng Hà Tiên</li>
                                    <li>• Nhân công hoàn thiện tô trát, ốp lát</li>
                                    <li>• Hệ thống ống điện, cấp thoát nước âm tường</li>
                                    <li>• Bảo hành kết cấu công trình 10 năm</li>
                                </ul>
                            </div>
                            <a href="#form-bao-gia" onclick="selectPackage('Báo giá thi công phần thô')" class="block w-full py-2 text-center rounded-lg bg-brand-dark hover:bg-brand-gold text-white font-bold text-xs transition-colors">
                                Nhận Báo Giá Chi Tiết
                            </a>
                        </div>

                        <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition-all">
                            <div>
                                <p class="text-[11px] font-bold uppercase text-brand-gold mb-1">Danh mục báo giá 03</p>
                                <h3 class="ux-product-title font-heading font-bold text-xs sm:text-base text-brand-dark mb-2">
                                    Báo giá thi công hoàn thiện
                                </h3>
                                <p class="text-sm sm:text-lg font-extrabold text-brand-goldDark mb-3">
                                    2.200.000đ – 3.200.000đ/m²
                                </p>
                                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                                    <li>• Gạch ốp lát, đá cầu thang, trần thạch cao</li>
                                    <li>• Sơn nước Dulux/Jotun nội ngoại thất</li>
                                    <li>• Cửa nhôm Xingfa, thiết bị vệ sinh Inax/Toto</li>
                                    <li>• Hệ thống chiếu sáng LED & thiết bị Panasonic</li>
                                </ul>
                            </div>
                            <a href="#form-bao-gia" onclick="selectPackage('Báo giá thi công hoàn thiện')" class="block w-full py-2 text-center rounded-lg bg-brand-dark hover:bg-brand-gold text-white font-bold text-xs transition-colors">
                                Nhận Báo Giá Chi Tiết
                            </a>
                        </div>

                        <div class="bg-white rounded-xl border-2 border-brand-gold p-4 sm:p-5 flex flex-col justify-between shadow-sm">
                            <div>
                                <p class="text-[11px] font-bold uppercase text-brand-gold mb-1">Danh mục báo giá 04</p>
                                <h3 class="ux-product-title font-heading font-bold text-xs sm:text-base text-brand-dark mb-2">
                                    Báo giá thi công trọn gói
                                </h3>
                                <p class="text-sm sm:text-lg font-extrabold text-brand-goldDark mb-3">
                                    5.600.000đ – 7.200.000đ/m²
                                </p>
                                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                                    <li>• Chìa khóa trao tay từ A - Z tại Đà Nẵng</li>
                                    <li>• Miễn phí 100% xin giấy phép & bản vẽ thiết kế</li>
                                    <li>• Cam kết không phát sinh chi phí hợp đồng</li>
                                    <li>• Giám sát kỹ sư 24/7 & bảo hành toàn diện</li>
                                </ul>
                            </div>
                            <a href="#form-bao-gia" onclick="selectPackage('Báo giá thi công trọn gói')" class="block w-full py-2 text-center rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs transition-colors">
                                Nhận Báo Giá Chi Tiết
                            </a>
                        </div>
                    </div>

                    <!-- FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ("MIỄN PHÍ TƯ VẤN & BÁO GIÁ") -->
                    <div id="form-bao-gia" class="bg-brand-dark text-white rounded-xl p-5 sm:p-8 shadow-md border border-slate-700">
                        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                            
                            <div class="lg:col-span-5">
                                <p class="text-xs font-bold uppercase tracking-wider text-brand-goldLight mb-1">
                                    ĐĂNG KÝ NHẬN DỰ TOÁN CHI PHÍ XÂY DỰNG
                                </p>
                                <h3 class="font-heading font-extrabold text-lg sm:text-2xl text-white mb-3">
                                    MIỄN PHÍ TƯ VẤN & BÁO GIÁ
                                </h3>
                                <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-4">
                                    Quý khách hàng vui lòng để lại thông tin nhu cầu xây dựng hoặc thiết kế, Kỹ sư trưởng của <strong>CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ</strong> sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết trong vòng 15 phút.
                                </p>
                                <div class="space-y-2.5 text-xs sm:text-sm text-slate-200">
                                    <div class="flex items-center gap-2.5">
                                        <i class="fa-solid fa-phone-volume text-brand-goldLight"></i>
                                        <span>Hotline / Zalo trực tiếp: <strong class="text-brand-goldLight">0931.999.334</strong></span>
                                    </div>
                                    <div class="flex items-center gap-2.5">
                                        <i class="fa-solid fa-location-dot text-brand-goldLight"></i>
                                        <span>Địa chỉ: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng</span>
                                    </div>
                                    <div class="flex items-center gap-2.5">
                                        <i class="fa-solid fa-globe text-brand-goldLight"></i>
                                        <span>Website: thietkemaunha.com</span>
                                    </div>
                                </div>
                            </div>

                            <div class="lg:col-span-7">
                                <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow">
                                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                        <div>
                                            <label for="customer-name" class="block text-xs font-bold text-brand-dark mb-1">Họ tên Quý khách *</label>
                                            <input type="text" id="customer-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                                        </div>
                                        <div>
                                            <label for="customer-phone" class="block text-xs font-bold text-brand-dark mb-1">Số điện thoại / Zalo *</label>
                                            <input type="tel" id="customer-phone" required placeholder="Ví dụ: 0931999334" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                                        </div>
                                        <div>
                                            <label for="project-type" class="block text-xs font-bold text-brand-dark mb-1">Loại công trình</label>
                                            <select id="project-type" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold bg-white">
                                                <option value="Nhà phố">Nhà phố</option>
                                                <option value="Biệt thự">Biệt thự</option>
                                                <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                                <option value="Văn phòng">Văn phòng</option>
                                                <option value="Thiết kế & Thi công nội thất">Thiết kế & Thi công nội thất</option>
                                                <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                            </select>
                                        </div>
                                        <div>
                                            <label for="investment-level" class="block text-xs font-bold text-brand-dark mb-1">Mức đầu tư dự kiến</label>
                                            <select id="investment-level" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold bg-white">
                                                <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                                                <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                                <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                                <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                                <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                                <option value="Chưa xác định">Chưa xác định</option>
                                            </select>
                                        </div>
                                        <div class="sm:col-span-2">
                                            <label for="customer-note" class="block text-xs font-bold text-brand-dark mb-1">Diện tích đất / Yêu cầu báo giá chi tiết</label>
                                            <input type="text" id="customer-note" placeholder="Ví dụ: Đất 5x20m tại Hòa Khánh, cần báo giá xây nhà trọn gói 3 tầng..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                                        </div>
                                    </div>

                                    <div class="mt-4 flex flex-col sm:flex-row items-center justify-between gap-3">
                                        <button type="submit" class="w-full sm:w-auto px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs sm:text-sm transition-colors shadow">
                                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                                        </button>
                                        <span class="text-[11px] text-slate-500">
                                            Hoặc kết nối Zalo: <strong class="text-brand-dark">0931.999.334</strong>
                                        </span>
                                    </div>

                                    <!-- Thông báo phản hồi ngay trong form (không dùng alert) -->
                                    <div id="quote-form-feedback" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs sm:text-sm font-medium"></div>
                                </form>
                            </div>

                        </div>
                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC)]
                 - Chia 2 cột trên điện thoại, 4 cột trên máy tính
                 - Nội dung bài viết thiết thực theo trang mẫu tintruongthinh.com
            ============================================================== -->
            <section id="tin-tuc" class="py-8 sm:py-12 bg-white border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            TIN TỨC & KINH NGHIỆM XÂY NHÀ
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-6">
                        Cẩm nang kiến thức thiết kế kiến trúc, kỹ thuật thi công phần thô và kinh nghiệm xây nhà trọn gói tại Đà Nẵng
                    </p>

                    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                        <!-- Bài viết 1 -->
                        <article class="ux-product-card">
                            <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w700" 
                                    onerror="handleDriveImageFallback(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'TIN+TUC+01')"
                                    alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng cách" 
                                    class="w-full h-full object-cover"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs text-brand-gold font-semibold mb-1">Kỹ thuật thi công</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">
                                        Hướng dẫn bảo dưỡng bê tông móng và dầm sàn đúng tiêu chuẩn kỹ thuật
                                    </h3>
                                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                        Trong quá trình thi công phần thô, bảo dưỡng ẩm bê tông đóng vai trò quyết định đến cường độ chịu lực và chống nứt công trình.
                                    </p>
                                </div>
                                <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-gold">
                                    Xem chi tiết →
                                </a>
                            </div>
                        </article>

                        <!-- Bài viết 2 -->
                        <article class="ux-product-card">
                            <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w700" 
                                    onerror="handleDriveImageFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'TIN+TUC+02')"
                                    alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư đều gặp phải" 
                                    class="w-full h-full object-cover"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs text-brand-gold font-semibold mb-1">Kinh nghiệm xây nhà</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">
                                        03 Nỗi lo lớn nhất khi xây nhà tại Đà Nẵng mà Chủ đầu tư nào cũng gặp phải
                                    </h3>
                                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                        Giải pháp kiểm soát ngân sách không phát sinh, lựa chọn nhà thầu có chứng chỉ năng lực và giám sát chất lượng vật tư.
                                    </p>
                                </div>
                                <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-gold">
                                    Xem chi tiết →
                                </a>
                            </div>
                        </article>

                        <!-- Bài viết 3 -->
                        <article class="ux-product-card">
                            <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w700" 
                                    onerror="handleDriveImageFallback(this, '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT', 'TIN+TUC+03')"
                                    alt="Thiết kế nội thất là gì – Khái niệm và tầm quan trọng" 
                                    class="w-full h-full object-cover"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs text-brand-gold font-semibold mb-1">Kiến trúc & Nội thất</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">
                                        Tâm lý học không gian: Thiết kế nội thất tác động đến tiện nghi gia đình thế nào?
                                    </h3>
                                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                        Cách bố trí ánh sáng tự nhiên, thông gió và vật liệu nội thất giúp ngôi nhà luôn ấm cúng, sang trọng và tối ưu diện tích.
                                    </p>
                                </div>
                                <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-gold">
                                    Xem chi tiết →
                                </a>
                            </div>
                        </article>

                        <!-- Bài viết 4 -->
                        <article class="ux-product-card">
                            <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w700" 
                                    onerror="handleDriveImageFallback(this, '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO', 'TIN+TUC+04')"
                                    alt="Quy trình xin phép xây dựng và thi công nhà trọn gói tại Đà Nẵng" 
                                    class="w-full h-full object-cover"
                                    loading="lazy"
                                >
                            </div>
                            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                <div>
                                    <p class="text-[10px] sm:text-xs text-brand-gold font-semibold mb-1">Pháp lý xây dựng</p>
                                    <h3 class="ux-product-title font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5">
                                        Thủ tục xin giấy phép xây dựng & chứng chỉ năng lực xây dựng tại TP Đà Nẵng
                                    </h3>
                                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                        Hướng dẫn hồ sơ pháp lý xin phép xây dựng nhà phố, biệt thự tại Hòa Khánh, Liên Chiểu, Hải Châu, Cẩm Lệ, Sơn Trà.
                                    </p>
                                </div>
                                <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-gold">
                                    Xem chi tiết →
                                </a>
                            </div>
                        </article>
                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 7: DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC & VẬT TƯ CHÍNH HÃNG)]
            ============================================================== -->
            <section id="doi-tac" class="py-8 sm:py-10 bg-brand-bgSoft border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-6">
                        CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ cam kết 100% vật tư đưa vào công trình chính hãng, đúng chủng loại hợp đồng
                    </p>

                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">THÉP HÒA PHÁT</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Kết cấu thép xây dựng</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">XI MĂNG HÀ TIÊN</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Xi măng & Bê tông chuẩn</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">SƠN DULUX & JOTUN</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất cao cấp</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">GỖ AN CƯỜNG</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Vật liệu gỗ nội thất chuẩn</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">INAX & TOTO</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Thiết bị phòng tắm chính hãng</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">ĐIỆN PANASONIC</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Thiết bị điện & chiếu sáng</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">NHÔM KÍNH XINGFA</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cường lực</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">ỐNG NHỰA BÌNH MINH</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Hệ thống cấp thoát nước</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">CHỐNG THẤM SIKA</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Hóa chất chống thấm Thụy Sĩ</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-brand-gold transition-colors">
                            <span class="block font-heading font-extrabold text-xs sm:text-sm text-brand-dark">GẠCH ĐỒNG TÂM</span>
                            <span class="block text-[11px] text-slate-500 mt-0.5">Gạch ốp lát & đá trang trí</span>
                        </div>
                    </div>

                </div>
            </section>

            <!-- =============================================================
                 [UX SECTION 8: ĐƯA FANPAGE VÀ ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ]
                 - Địa chỉ: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng
                 - SĐT: 0931.999.334
                 - Fanpage: https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN
            ============================================================== -->
            <section id="lien-he" class="py-8 sm:py-12 bg-white border-t border-slate-200">
                <div class="ux-container">
                    
                    <div class="ux-section-title">
                        <h2 class="font-heading font-extrabold text-base sm:text-xl md:text-2xl text-brand-dark text-center uppercase">
                            KẾT NỐI FANPAGE & BẢN ĐỒ TRỤ SỞ TRANG CHỦ
                        </h2>
                    </div>
                    <p class="text-center text-xs sm:text-sm text-slate-600 mb-6">
                        Trụ sở chính: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng • Hotline/Zalo: 0931.999.334
                    </p>

                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                        
                        <!-- CỘT 1: ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
                        <div class="lg:col-span-5 flex flex-col justify-between rounded-xl border border-slate-200 bg-brand-bgSoft p-4 sm:p-5 shadow-sm">
                            <div>
                                <div class="flex items-center justify-between gap-2 mb-3 pb-2.5 border-b border-slate-200">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-brands fa-facebook text-blue-600 text-xl"></i>
                                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark uppercase">
                                            FANPAGE CHÍNH THỨC TRÊN FACEBOOK
                                        </h3>
                                    </div>
                                    <a href="https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-blue-600 hover:underline">
                                        Mở Fanpage ↗
                                    </a>
                                </div>

                                <!-- Khung hiển thị trực quan Fanpage + Iframe Facebook Plugin -->
                                <div class="rounded-lg overflow-hidden border border-slate-200 bg-white mb-3">
                                    <div class="relative h-32 sm:h-36 bg-brand-dark overflow-hidden">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800" 
                                            onerror="handleDriveImageFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'FANPAGE+COVER')"
                                            alt="Ảnh bìa Fanpage Công ty TNHH Xây dựng Thiết kế Mẫu Nhà" 
                                            class="w-full h-full object-cover opacity-55"
                                        >
                                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                        <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                            <img 
                                                src="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w200" 
                                                onerror="handleDriveImageFallback(this, '1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj', 'LOGO')"
                                                alt="Logo Fanpage" 
                                                class="w-12 h-12 rounded-lg bg-white p-1 object-contain border border-slate-200 shrink-0"
                                            >
                                            <div class="text-white min-w-0">
                                                <h4 class="font-heading font-bold text-xs sm:text-sm truncate">
                                                    Thiết Kế Mẫu Nhà - Xây Dựng Nội Thất Đà Nẵng Uy Tín
                                                </h4>
                                                <p class="text-[11px] text-slate-200">
                                                    CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ • Đà Nẵng
                                                </p>
                                            </div>
                                        </div>
                                    </div>

                                    <div class="p-3.5 text-xs text-slate-700 space-y-2">
                                        <p class="leading-relaxed">
                                            Cập nhật hình ảnh nhật ký công trình thi công thực tế hằng ngày, mẫu nhà đẹp Đà Nẵng và bảng báo giá ưu đãi mới nhất trên Fanpage.
                                        </p>
                                        <div class="w-full overflow-hidden rounded border border-slate-100 bg-slate-50 flex justify-center py-1">
                                            <iframe 
                                                title="Facebook Fanpage Công ty TNHH Xây dựng Thiết kế Mẫu Nhà"
                                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fthietkemaunhaxaydungnoithatdananguytin&tabs=&width=340&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                                width="340" 
                                                height="130" 
                                                style="border:none;overflow:hidden;max-width:100%;" 
                                                scrolling="no" 
                                                frameborder="0" 
                                                allowfullscreen="true" 
                                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                            </iframe>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="flex flex-wrap items-center gap-2">
                                <a href="https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 px-4 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs text-center transition-colors">
                                    <i class="fa-brands fa-facebook-f mr-1.5"></i> Theo Dõi & Nhắn Tin Fanpage
                                </a>
                                <a href="https://zalo.me/0931999334" target="_blank" rel="noopener noreferrer" class="py-2.5 px-4 rounded-lg bg-brand-dark hover:bg-brand-gold text-white font-bold text-xs text-center transition-colors">
                                    Chat Zalo: 0931.999.334
                                </a>
                            </div>
                        </div>

                        <!-- CỘT 2: ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                        <div class="lg:col-span-7 flex flex-col justify-between rounded-xl border border-slate-200 bg-brand-bgSoft p-4 sm:p-5 shadow-sm">
                            <div>
                                <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2.5 border-b border-slate-200">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-map-location-dot text-brand-gold text-xl"></i>
                                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark uppercase">
                                            GOOGLE MAPS: 261 NGUYỄN SINH SẮC, PHƯỜNG HÒA KHÁNH, TP ĐÀ NẴNG
                                        </h3>
                                    </div>
                                    <a href="https://www.google.com/maps/search/?api=1&query=261+Nguy%E1%BB%85n+Sinh+S%E1%BA%AFc,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-brand-goldDark hover:underline">
                                        Chỉ đường Google Maps ↗
                                    </a>
                                </div>

                                <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                                <div class="w-full h-[270px] sm:h-[310px] rounded-lg overflow-hidden border border-slate-300 bg-slate-200 shadow-inner mb-3">
                                    <iframe 
                                        title="Google Map 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng"
                                        src="https://maps.google.com/maps?q=261%20Nguy%E1%BB%85n%20Sinh%20S%E1%BA%AFc,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                        class="w-full h-full border-0"
                                        allowfullscreen="" 
                                        loading="lazy" 
                                        referrerpolicy="no-referrer-when-downgrade">
                                    </iframe>
                                </div>
                            </div>

                            <!-- Thanh thông tin địa chỉ & chỉ đường dưới bản đồ -->
                            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 bg-white p-3 rounded-lg border border-slate-200">
                                <div class="text-xs text-slate-700">
                                    <p class="font-bold text-brand-dark">CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ</p>
                                    <p>Địa chỉ: 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng • ĐT: <strong>0931.999.334</strong></p>
                                </div>
                                <a href="https://www.google.com/maps/search/?api=1&query=261+Nguy%E1%BB%85n+Sinh+S%E1%BA%AFc,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="shrink-0 px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs text-center transition-colors">
                                    <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Bản Đồ Lớn
                                </a>
                            </div>
                        </div>

                    </div>

                </div>
            </section>

        </main>

        <!-- =================================================================
             FOOTER (#footer) - CHUẨN FLATSOME
        ================================================================== -->
        <footer id="footer" class="bg-brand-dark text-slate-200 pt-10 pb-6 border-t-4 border-brand-gold">
            <div class="ux-container">
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-slate-700">
                    
                    <!-- Thông tin công ty -->
                    <div class="lg:col-span-5">
                        <div class="flex items-center gap-3 mb-3">
                            <div class="w-11 h-11 rounded-md bg-white p-1 flex items-center justify-center shrink-0">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj=w200" 
                                    onerror="handleDriveImageFallback(this, '1sBvXDXWFuen-u8MVRCU4TL2t7OTIGuIj', 'LOGO')"
                                    alt="Logo Công ty TNHH Xây dựng Thiết kế Mẫu Nhà" 
                                    class="max-h-9 w-auto object-contain"
                                >
                            </div>
                            <div>
                                <h3 class="font-heading font-extrabold text-sm sm:text-base text-white">
                                    CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ
                                </h3>
                                <p class="text-xs text-brand-goldLight font-semibold">
                                    HOME DESIGN CONSTRUCTION CO.,LTD • thietkemaunha.com
                                </p>
                            </div>
                        </div>
                        <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-brand-goldLight mt-1"></i>
                                <span><strong>Trụ sở:</strong> 261 Nguyễn Sinh Sắc, Phường Hòa Khánh, TP Đà Nẵng</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone text-brand-goldLight"></i>
                                <span><strong>Hotline / Zalo:</strong> <a href="tel:0931999334" class="text-white font-bold hover:text-brand-goldLight">0931.999.334</a></span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-envelope text-brand-goldLight"></i>
                                <span><strong>Email:</strong> ctythietkemaunha@gmail.com</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-globe text-brand-goldLight"></i>
                                <span><strong>Website:</strong> thietkemaunha.com</span>
                            </li>
                            <li class="flex items-center gap-2.5">
                                <i class="fa-solid fa-file-shield text-brand-goldLight"></i>
                                <span><strong>Mã số thuế:</strong> 0401905630 • <strong>Chứng chỉ HĐXD:</strong> 00038607</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Danh mục Lĩnh vực hoạt động & Công trình -->
                    <div class="lg:col-span-4 grid grid-cols-2 gap-4">
                        <div>
                            <h4 class="font-heading font-bold text-xs sm:text-sm text-brand-goldLight uppercase mb-3">
                                LĨNH VỰC HOẠT ĐỘNG
                            </h4>
                            <ul class="space-y-2 text-xs text-slate-300">
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Thiết kế Kiến trúc – Nội thất</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Thi công phần thô</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Thi công hoàn thiện</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Thi công nội thất</a></li>
                                <li><a href="#bao-gia" class="hover:text-brand-goldLight">Xây nhà trọn gói Đà Nẵng</a></li>
                            </ul>
                        </div>
                        <div>
                            <h4 class="font-heading font-bold text-xs sm:text-sm text-brand-goldLight uppercase mb-3">
                                DANH MỤC SẢN PHẨM
                            </h4>
                            <ul class="space-y-2 text-xs text-slate-300">
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Khách sạn – Căn hộ – Phòng trọ</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Biệt thự hiện đại & sân vườn</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Nhà phố Đà Nẵng</a></li>
                                <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight">Văn phòng & Showroom</a></li>
                                <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight">Dự án tiêu biểu Đà Nẵng</a></li>
                            </ul>
                        </div>
                    </div>

                    <!-- Kết nối nhanh -->
                    <div class="lg:col-span-3">
                        <h4 class="font-heading font-bold text-xs sm:text-sm text-brand-goldLight uppercase mb-3">
                            KẾT NỐI VỚI CHÚNG TÔI
                        </h4>
                        <p class="text-xs text-slate-300 leading-relaxed mb-3">
                            Liên hệ trực tiếp với đội ngũ Kiến trúc sư & Kỹ sư CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ để nhận tư vấn miễn phí 24/7.
                        </p>
                        <div class="flex flex-col gap-2">
                            <a href="https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs flex items-center gap-2">
                                <i class="fa-brands fa-facebook-f"></i>
                                <span>Fanpage Thiết Kế Mẫu Nhà Đà Nẵng</span>
                            </a>
                            <a href="https://zalo.me/0931999334" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-sky-600 hover:bg-sky-700 text-white font-bold text-xs flex items-center gap-2">
                                <i class="fa-solid fa-comment-dots"></i>
                                <span>Nhắn Tin Zalo: 0931.999.334</span>
                            </a>
                        </div>
                    </div>

                </div>

                <!-- Bản quyền -->
                <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                    <p>Copyright © CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ (thietkemaunha.com). All rights reserved.</p>
                    <p>Thiết kế giao diện chuẩn UX Builder Flatsome</p>
                </div>
            </div>
        </footer>

        <!-- =================================================================
             CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             Tương thích hoàn hảo trên cả máy tính và điện thoại, không tràn viền
        ================================================================== -->
        <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5" aria-label="Nút liên hệ nổi">
            
            <!-- Nút Facebook Fanpage -->
            <a 
                href="https://www.facebook.com/thietkemaunhaxaydungnoithatdananguytin?locale=vi_VN" 
                target="_blank" 
                rel="noopener noreferrer"
                class="flex items-center gap-2 px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full bg-blue-600 hover:bg-blue-700 text-white shadow-lg transition-transform hover:scale-105"
                title="Fanpage Facebook"
            >
                <span class="w-6 h-6 rounded-full bg-white text-blue-600 flex items-center justify-center text-xs font-bold shrink-0">
                    <i class="fa-brands fa-facebook-f"></i>
                </span>
                <span class="text-xs font-bold pr-1">Facebook</span>
            </a>

            <!-- Nút Zalo 0931.999.334 -->
            <a 
                href="https://zalo.me/0931999334" 
                target="_blank" 
                rel="noopener noreferrer"
                class="flex items-center gap-2 px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full bg-sky-500 hover:bg-sky-600 text-white shadow-lg transition-transform hover:scale-105"
                title="Chat Zalo 0931.999.334"
            >
                <span class="w-6 h-6 rounded-full bg-white text-sky-600 flex items-center justify-center text-[10px] font-extrabold shrink-0">
                    Zalo
                </span>
                <span class="text-xs font-bold pr-1">Chat Zalo</span>
            </a>

            <!-- Nút Hotline 0931.999.334 -->
            <a 
                href="tel:0931999334" 
                class="floating-pulse flex items-center gap-2 px-3.5 py-2.5 sm:px-4 sm:py-2.5 rounded-full bg-brand-gold hover:bg-brand-goldDark text-white shadow-xl transition-transform hover:scale-105"
                title="Gọi Hotline 0931.999.334"
            >
                <span class="w-6 h-6 rounded-full bg-white text-brand-goldDark flex items-center justify-center text-xs shrink-0">
                    <i class="fa-solid fa-phone-volume"></i>
                </span>
                <span class="text-xs sm:text-sm font-extrabold pr-1">0931.999.334</span>
            </a>

        </div>

    </div>

    <!-- =====================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER BANNER, LỌC DANH MỤC & FORM BÁO GIÁ
    ====================================================================== -->
    <script>
        /* 1. Điều khiển Menu Mobile */
        function toggleMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            const icon = document.getElementById('mobile-menu-icon');
            if (!panel) return;
            panel.classList.toggle('hidden');
            if (panel.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars text-lg';
            } else {
                icon.className = 'fa-solid fa-xmark text-lg';
            }
        }

        function closeMobileMenu() {
            const panel = document.getElementById('mobile-menu-panel');
            const icon = document.getElementById('mobile-menu-icon');
            if (panel && !panel.classList.contains('hidden')) {
                panel.classList.add('hidden');
                icon.className = 'fa-solid fa-bars text-lg';
            }
        }

        /* 2. Điều khiển 2 Ảnh Banner Tự Trượt Chuyên Nghiệp */
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function showBannerSlide(index) {
            const slides = document.querySelectorAll('#banner-slider .banner-slide');
            const dot0 = document.getElementById('banner-dot-0');
            const dot1 = document.getElementById('banner-dot-1');
            if (!slides.length) return;

            currentBannerIndex = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            if (dot0 && dot1) {
                if (currentBannerIndex === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-brand-gold transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                    dot1.className = 'w-6 h-2 rounded-full bg-brand-gold transition-all';
                }
            }
        }

        function nextBannerSlide() {
            showBannerSlide(currentBannerIndex + 1);
            restartBannerAutoSlide();
        }

        function prevBannerSlide() {
            showBannerSlide(currentBannerIndex - 1);
            restartBannerAutoSlide();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            restartBannerAutoSlide();
        }

        function restartBannerAutoSlide() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 5000);
        }

        /* 3. Lọc Danh mục Công trình thực tế (9 ảnh) */
        function filterConstruction(category) {
            const buttons = document.querySelectorAll('#construction-filter-bar .ux-cat-pill');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            const items = document.querySelectorAll('#construction-grid .construction-item');
            items.forEach(item => {
                const itemCats = (item.getAttribute('data-categories') || '').split(' ');
                if (category === 'all' || itemCats.includes(category)) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        /* 4. Lọc Danh mục Dự án tại Đà Nẵng (10 ảnh) */
        function filterDanangProjects(category) {
            const buttons = document.querySelectorAll('#danang-filter-bar .ux-cat-pill');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-dncat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            const items = document.querySelectorAll('#danang-projects-grid .danang-project-item');
            items.forEach(item => {
                const itemCats = (item.getAttribute('data-dncategories') || '').split(' ');
                if (category === 'all' || itemCats.includes(category)) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        /* 5. Chọn nhanh gói báo giá vào Form */
        function selectPackage(packageName) {
            const noteInput = document.getElementById('customer-note');
            if (noteInput) {
                noteInput.value = 'Yêu cầu tư vấn: ' + packageName;
                noteInput.focus();
            }
        }

        /* 6. Xử lý gửi Form Yêu cầu & Báo giá trang chủ (Không dùng alert) */
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('customer-name').value.trim();
            const phone = document.getElementById('customer-phone').value.trim();
            const type = document.getElementById('project-type').value;
            const budget = document.getElementById('investment-level').value;
            const feedback = document.getElementById('quote-form-feedback');

            if (feedback) {
                feedback.classList.remove('hidden');
                feedback.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5"></i> Cảm ơn <strong>' + name + '</strong> (' + phone + ')! Yêu cầu tư vấn <strong>' + type + '</strong> (Mức đầu tư: ' + budget + ') đã được ghi nhận. Bộ phận Kỹ sư CÔNG TY TNHH XÂY DỰNG THIẾT KẾ MẪU NHÀ sẽ liên hệ qua số <strong>0931.999.334</strong> trong ít phút tới.';
            }
            document.getElementById('quote-request-form').reset();
        }

        window.addEventListener('load', () => {
            restartBannerAutoSlide();
        });
    </script>
</body>
</html>
