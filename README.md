
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>國立屏東科技大學 - 工業管理系 | NPUST IEM</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lucide/0.263.0/lucide.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700;900&display=swap');
        body {
            font-family: 'Noto Sans TC', sans-serif;
        }
        .iem-blue { color: #003366; }
        .bg-iem-blue { background-color: #003366; }
        .bg-iem-gold { background-color: #f1c40f; }
        .hero-pattern {
            background-color: #003366;
            background-image: url("https://www.transparenttextures.com/patterns/cubes.png");
        }
        .nav-link {
            position: relative;
            transition: color 0.3s ease;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #f1c40f;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- 頂部資訊列 -->
    <div class="bg-iem-blue text-white py-2 text-sm">
        <div class="max-w-7xl mx-auto px-4 flex justify-between items-center">
            <div class="flex space-x-4">
                <span class="flex items-center"><i data-lucide="phone" class="w-3 h-3 mr-2"></i> (08) 770-3202</span>
                <span class="hidden md:flex items-center"><i data-lucide="mail" class="w-3 h-3 mr-2"></i> iem@mail.npust.edu.tw</span>
            </div>
            <div class="flex space-x-4">
                <a href="#" class="hover:text-iem-gold transition">屏科大首頁</a>
                <a href="#" class="hover:text-iem-gold transition">English</a>
            </div>
        </div>
    </div>

    <!-- 主導航欄 -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center">
                    <div class="bg-iem-blue p-2 rounded-lg mr-3">
                        <i data-lucide="graduation-cap" class="text-white w-8 h-8"></i>
                    </div>
                    <div>
                        <h1 class="font-black text-xl iem-blue tracking-tight">屏東科技大學</h1>
                        <h2 class="font-bold text-sm text-gray-500 uppercase tracking-widest">工業管理系</h2>
                    </div>
                </div>
                <div class="hidden lg:flex space-x-8 font-bold text-gray-700">
                    <a href="#" class="nav-link text-iem-blue">本系概況</a>
                    <a href="#" class="nav-link">師資陣容</a>
                    <a href="#" class="nav-link">課程規劃</a>
                    <a href="#" class="nav-link">招生資訊</a>
                    <a href="#" class="nav-link">學術研究</a>
                    <a href="#students" class="bg-iem-gold text-iem-blue px-4 py-1 rounded-full hover:bg-yellow-500 transition">學生風采</a>
                </div>
                <button class="lg:hidden p-2 text-gray-600">
                    <i data-lucide="menu" class="w-6 h-6"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- 英雄視覺區 -->
    <section class="hero-pattern py-20 md:py-32 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 relative z-10">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-8">
                    <div class="inline-block px-4 py-1 bg-iem-gold text-iem-blue font-black rounded-md text-sm uppercase">
                        智慧製造 • 數位轉型
                    </div>
                    <h2 class="text-4xl md:text-6xl font-black leading-tight">
                        培育具備科技實力與<br><span class="text-iem-gold">管理智慧</span>的領袖
                    </h2>
                    <p class="text-lg text-gray-300 max-w-lg leading-relaxed">
                        屏科大工管系致力於結合工業工程理論與實務應用，從大數據分析、智慧生產到供應鏈管理，我們為未來的產業醫師提供最好的養分。
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <button class="bg-iem-gold text-iem-blue px-8 py-4 rounded-lg font-black hover:bg-yellow-500 transition shadow-xl">
                            系所簡介
                        </button>
                        <button class="border-2 border-white/30 text-white px-8 py-4 rounded-lg font-black hover:bg-white/10 transition">
                            虛擬環景導覽
                        </button>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="relative">
                        <div class="absolute -inset-4 bg-iem-gold/20 blur-3xl rounded-full"></div>
                        <!-- 示意圖：工業管理場景 -->
                        <div class="relative bg-white/10 backdrop-blur-md p-2 rounded-2xl border border-white/20">
                            <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&q=80&w=800" alt="[屏科大工管系研究室]" class="rounded-xl shadow-2xl">
                            <div class="absolute -bottom-6 -right-6 bg-white p-6 rounded-2xl shadow-2xl text-iem-blue">
                                <p class="text-3xl font-black">40+</p>
                                <p class="text-xs font-bold text-gray-500 uppercase">產學合作夥伴</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 最新公告 -->
    <section class="py-20">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-end mb-12">
                <div>
                    <h3 class="text-3xl font-black iem-blue">最新公告</h3>
                    <p class="text-gray-500 mt-2 font-medium">掌握系上第一手學術與活動動態</p>
                </div>
                <a href="#" class="text-iem-blue font-bold flex items-center hover:underline">
                    查看全部 <i data-lucide="arrow-right" class="w-4 h-4 ml-1"></i>
                </a>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- 公告 1 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                    <span class="text-xs font-bold text-gray-400">2024.11.20</span>
                    <h4 class="text-xl font-bold mt-2 iem-blue hover:text-blue-700 cursor-pointer">【招生】114學年度碩士班甄試入學面試公告</h4>
                    <p class="text-gray-600 mt-3 line-clamp-2">請通過第一階段篩選之考生，於指定時間內完成報到...</p>
                    <div class="mt-4 flex items-center text-sm font-bold text-blue-500">
                        <i data-lucide="tag" class="w-4 h-4 mr-2"></i> 招生資訊
                    </div>
                </div>
                <!-- 公告 2 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                    <span class="text-xs font-bold text-gray-400">2024.11.15</span>
                    <h4 class="text-xl font-bold mt-2 iem-blue hover:text-blue-700 cursor-pointer">【演講】智慧物流的未來：無人載具與路徑優化</h4>
                    <p class="text-gray-600 mt-3 line-clamp-2">特別邀請業界專家分享最新的自動化倉儲技術與案例...</p>
                    <div class="mt-4 flex items-center text-sm font-bold text-emerald-500">
                        <i data-lucide="mic" class="w-4 h-4 mr-2"></i> 學術演講
                    </div>
                </div>
                <!-- 公告 3 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                    <span class="text-xs font-bold text-gray-400">2024.11.05</span>
                    <h4 class="text-xl font-bold mt-2 iem-blue hover:text-blue-700 cursor-pointer">【獎學金】113-1學年度工管系優秀學生獎助學金</h4>
                    <p class="text-gray-600 mt-3 line-clamp-2">鼓勵學業成績優異或參與競賽表現傑出之同學申請...</p>
                    <div class="mt-4 flex items-center text-sm font-bold text-amber-500">
                        <i data-lucide="award" class="w-4 h-4 mr-2"></i> 獎助學金
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 重點亮點：學生傑出表現（您的個人網頁連結點） -->
    <section id="students" class="py-24 bg-iem-blue text-white overflow-hidden relative">
        <div class="max-w-7xl mx-auto px-4 relative z-10">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-black mb-4">學生傑出表現</h3>
                <div class="w-24 h-1 bg-iem-gold mx-auto rounded-full"></div>
                <p class="mt-6 text-gray-300 text-lg">在屏科大工管，我們鼓勵學生建立個人品牌，展示實務專案與學習成果</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">
                <!-- 您的展示卡片 -->
                <div class="bg-white/10 backdrop-blur-md rounded-3xl p-8 border border-white/20 hover:bg-white/20 transition-all transform hover:-translate-y-2 group">
                    <div class="flex items-center space-x-4 mb-6">
                        <div class="w-16 h-16 rounded-full bg-iem-gold flex items-center justify-center font-black text-iem-blue text-xl">
                            戴
                        </div>
                        <div>
                            <h4 class="text-xl font-bold">戴嘉樟</h4>
                            <p class="text-sm text-gray-400">大學部 | 優秀學生</p>
                        </div>
                    </div>
                    <p class="text-gray-300 mb-8 leading-relaxed">
                        「專精於工作研究與生產效率優化，致力於將工業工程技術應用於實務生產線。具備多項專業證照與專案開發經驗。」
                    </p>
                    <!-- 這是連結到您 index.html 的關鍵按鈕 -->
                    <a href="index.html" target="_blank" class="flex items-center justify-center w-full py-3 bg-white text-iem-blue font-black rounded-xl hover:bg-iem-gold hover:scale-105 transition-all">
                        查看個人作品集 <i data-lucide="external-link" class="w-4 h-4 ml-2"></i>
                    </a>
                </div>

                <!-- 預留位置 2 -->
                <div class="bg-white/5 rounded-3xl p-8 border border-white/10 opacity-60">
                    <div class="flex items-center space-x-4 mb-6">
                        <div class="w-16 h-16 rounded-full bg-gray-600 flex items-center justify-center font-black text-white text-xl">
                            <i data-lucide="user"></i>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold">學術精英 A</h4>
                            <p class="text-sm text-gray-400">碩士班 | 機器學習研究</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-8 italic">學生個人網頁預留位置</p>
                    <div class="w-full py-3 bg-white/10 text-gray-400 font-black rounded-xl text-center border border-white/10">
                        建構中
                    </div>
                </div>

                <!-- 預留位置 3 -->
                <div class="bg-white/5 rounded-3xl p-8 border border-white/10 opacity-60">
                    <div class="flex items-center space-x-4 mb-6">
                        <div class="w-16 h-16 rounded-full bg-gray-600 flex items-center justify-center font-black text-white text-xl">
                            <i data-lucide="user"></i>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold">學術精英 B</h4>
                            <p class="text-sm text-gray-400">博士班 | 韌性供應鏈研究</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-8 italic">學生個人網頁預留位置</p>
                    <div class="w-full py-3 bg-white/10 text-gray-400 font-black rounded-xl text-center border border-white/10">
                        建構中
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 底部聯絡資訊 -->
    <footer class="bg-white pt-20 pb-10">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid md:grid-cols-3 gap-12 mb-20">
                <div class="space-y-6">
                    <div class="flex items-center">
                        <div class="bg-iem-blue p-2 rounded-lg mr-3">
                            <i data-lucide="graduation-cap" class="text-white w-6 h-6"></i>
                        </div>
                        <h2 class="font-black text-xl iem-blue tracking-tight">NPUST IEM</h2>
                    </div>
                    <p class="text-gray-500 leading-relaxed font-medium">
                        91201 屏東縣內埔鄉學府路 1 號<br>
                        管理學院二館 (工管系辦公室)
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i data-lucide="facebook" class="w-5 h-5"></i></a>
                        <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-600 hover:bg-red-600 hover:text-white transition"><i data-lucide="youtube" class="w-5 h-5"></i></a>
                        <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-600 hover:bg-blue-400 hover:text-white transition"><i data-lucide="globe" class="w-5 h-5"></i></a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-black iem-blue mb-8">系所服務</h4>
                    <ul class="space-y-4 text-gray-600 font-medium">
                        <li><a href="#" class="hover:text-iem-blue transition">碩專班專區</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">系友會資訊</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">下載專區</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">常用表格下載</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">實驗室介紹</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-lg font-black iem-blue mb-8">快捷連結</h4>
                    <ul class="space-y-4 text-gray-600 font-medium">
                        <li><a href="#" class="hover:text-iem-blue transition">屏科大學生系統</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">校園教學入口</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">圖書館查詢</a></li>
                        <li><a href="#" class="hover:text-iem-blue transition">系上電子郵件</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-100 pt-10 text-center">
                <p class="text-gray-400 text-sm font-medium">© 2024 國立屏東科技大學工業管理系 版權所有. 網頁維護：戴嘉樟</p>
            </div>
        </div>
    </footer>

    <script>
        // 初始化圖標
        window.onload = function() {
            lucide.createIcons();
        };
    </script>
</body>
</html>

[index.html個人網頁.txt](https://github.com/user-attachments/files/26238263/index.html.txt)
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>戴嘉樟 | 屏東科技大學工業管理</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入 Lucide 圖標庫 -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lucide/0.263.0/lucide.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap');
        body {
            font-family: 'Noto Sans TC', sans-serif;
            scroll-behavior: smooth;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #1e293b 0%, #334155 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .file-upload-dash {
            border: 2px dashed #cbd5e1;
            transition: all 0.3s ease;
        }
        .file-upload-dash:hover {
            border-color: #3b82f6;
            background-color: #f8fafc;
        }
        /* 照片顯示優化 */
        .profile-container {
            position: relative;
            width: 100%;
            max-width: 380px;
        }
        .profile-img {
            width: 100%;
            height: auto;
            border-radius: 2rem;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.4);
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            object-fit: cover;
            border: 4px solid white;
        }
        .profile-img:hover {
            transform: scale(1.03) rotate(1deg);
        }
        .profile-fallback {
            background: linear-gradient(135deg, #e2e8f0 0%, #cbd5e1 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            color: #64748b;
            min-height: 500px;
            border-radius: 2rem;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- 導航列 -->
    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 font-bold text-2xl text-blue-900 tracking-tighter">
                    戴嘉樟
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-6">
                        <a href="#home" class="text-slate-600 hover:text-blue-600 font-medium transition">首頁</a>
                        <a href="#about" class="text-slate-600 hover:text-blue-600 font-medium transition">關於我</a>
                        <a href="#dept" class="text-slate-600 hover:text-blue-600 font-medium transition">屏科大工管</a>
                        <a href="#knowledge" class="text-slate-600 hover:text-blue-600 font-medium transition">工作研究</a>
                        <a href="#assignment" class="text-slate-600 hover:text-blue-600 font-medium transition">作業繳交</a>
                        <a href="#contact" class="bg-blue-900 text-white px-5 py-2 rounded-xl hover:bg-blue-800 transition shadow-md shadow-blue-900/20">聯絡我</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- 英雄區 -->
    <section id="home" class="hero-gradient min-h-screen flex items-center pt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24 text-center">
            <div class="inline-block px-4 py-1.5 mb-6 text-sm font-bold tracking-widest text-blue-400 uppercase bg-blue-400/10 rounded-full">
                Industrial Engineering & Management
            </div>
            <h1 class="text-4xl md:text-7xl font-extrabold text-white mb-8 leading-tight">
                追求卓越效率<br><span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">優化產業系統</span>
            </h1>
            <p class="text-xl text-slate-300 mb-10 max-w-2xl mx-auto leading-relaxed">
                我是 戴嘉樟，目前就讀於國立屏東科技大學工業管理系。致力於運用工業工程技術提昇生產力與品質管理，創造更高效的運作模式。
            </p>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <a href="#knowledge" class="w-full sm:w-auto bg-blue-600 text-white px-10 py-4 rounded-full font-bold hover:bg-blue-500 transition-all transform hover:scale-105 shadow-lg shadow-blue-600/30">
                    查看專業知識庫
                </a>
                <a href="#assignment" class="w-full sm:w-auto bg-white/10 text-white border border-white/20 px-10 py-4 rounded-full font-bold hover:bg-white/20 transition-all backdrop-blur-sm">
                    進入繳交區
                </a>
            </div>
        </div>
    </section>

    <!-- 關於我 -->
    <section id="about" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 gap-16 items-center">
                <!-- 個人照片展示 -->
                <div class="flex justify-center order-2 md:order-1">
                    <div class="profile-container group">
                        <!-- 背景裝飾光環 -->
                        <div class="absolute -inset-4 bg-gradient-to-tr from-blue-600 to-emerald-400 rounded-[2.5rem] blur opacity-20 group-hover:opacity-30 transition duration-1000"></div>
                        
                        <!-- 實體照片區塊 -->
                        <div class="relative">
                            <!-- 使用上傳的照片檔名 -->
                            <img src="大頭照.jpg" alt="戴嘉樟 個人照片" 
                                 onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';"
                                 class="profile-img">
                            
                            <!-- 載入失敗時的備用顯示 -->
                            <div class="profile-fallback hidden">
                                <i data-lucide="user-circle" class="w-24 h-24 mb-4 opacity-30"></i>
                                <p class="font-bold text-slate-500 text-lg">戴嘉樟</p>
                                <p class="text-sm text-slate-400">國立屏東科技大學</p>
                            </div>

                            <!-- 裝飾標籤 -->
                            <div class="absolute -bottom-8 -left-8 bg-white p-5 rounded-2xl shadow-2xl border border-slate-100 hidden lg:block">
                                <div class="flex items-center space-x-3">
                                    <div class="w-10 h-10 bg-blue-50 rounded-lg flex items-center justify-center">
                                        <i data-lucide="award" class="w-6 h-6 text-blue-600"></i>
                                    </div>
                                    <div>
                                        <p class="text-xs text-slate-400 font-bold uppercase tracking-wider">Education</p>
                                        <p class="text-sm font-black text-slate-800">NPUST IEM</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="space-y-10 order-1 md:order-2">
                    <div class="space-y-4">
                        <h2 class="text-5xl font-black text-slate-900 tracking-tighter">關於我</h2>
                        <div class="w-20 h-2 bg-blue-600 rounded-full"></div>
                    </div>
                    
                    <p class="text-xl text-slate-600 leading-relaxed italic border-l-4 border-blue-600 pl-8 py-2">
                        「工業工程師是產業的醫師」，我深信透過科學化的數據分析與流程改善，能夠為任何複雜的系統找出最佳化解決方案。
                    </p>

                    <p class="text-lg text-slate-600 leading-relaxed">
                        我是 <span class="font-bold text-slate-900 text-xl">戴嘉樟</span>，目前於國立屏東科技大學工業管理系深造。在學習過程中，我對工作研究、生產計劃及品質管制展現了深厚興趣，並致力於實務應用。
                    </p>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="flex items-center p-4 bg-slate-50 rounded-2xl border border-slate-100 card-hover">
                            <i data-lucide="check-circle" class="text-blue-600 w-6 h-6 mr-3"></i>
                            <span class="font-bold text-slate-700">生產管理與管制</span>
                        </div>
                        <div class="flex items-center p-4 bg-slate-50 rounded-2xl border border-slate-100 card-hover">
                            <i data-lucide="check-circle" class="text-blue-600 w-6 h-6 mr-3"></i>
                            <span class="font-bold text-slate-700">Six Sigma 品質管理</span>
                        </div>
                        <div class="flex items-center p-4 bg-slate-50 rounded-2xl border border-slate-100 card-hover">
                            <i data-lucide="check-circle" class="text-blue-600 w-6 h-6 mr-3"></i>
                            <span class="font-bold text-slate-700">作業研究 (OR)</span>
                        </div>
                        <div class="flex items-center p-4 bg-slate-50 rounded-2xl border border-slate-100 card-hover">
                            <i data-lucide="check-circle" class="text-blue-600 w-6 h-6 mr-3"></i>
                            <span class="font-bold text-slate-700">工作研究 (Work Study)</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 新增區塊：關於屏科大工業管理系 -->
    <section id="dept" class="py-24 bg-blue-900 text-white relative overflow-hidden">
        <div class="absolute top-0 left-0 w-full h-full opacity-10">
            <div class="grid grid-cols-6 h-full">
                <div class="border-r border-white"></div>
                <div class="border-r border-white"></div>
                <div class="border-r border-white"></div>
                <div class="border-r border-white"></div>
                <div class="border-r border-white"></div>
                <div></div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="bg-white/10 backdrop-blur-lg rounded-[3rem] p-8 md:p-16 border border-white/20 shadow-2xl">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <div class="inline-flex items-center px-4 py-1.5 mb-6 text-sm font-bold tracking-widest text-blue-300 uppercase bg-blue-500/20 rounded-full border border-blue-500/30">
                            Department of IEM, NPUST
                        </div>
                        <h2 class="text-4xl md:text-5xl font-black mb-6 leading-tight">國立屏東科技大學<br>工業管理系</h2>
                        <p class="text-lg text-blue-100 mb-8 leading-relaxed">
                            本系旨在培養具備系統整合能力之工業管理人才，結合傳統工程技術與現代科學管理，致力於智慧製造、供應鏈管理與綠色生產等領域。
                        </p>
                        <ul class="space-y-4 mb-10 text-blue-50">
                            <li class="flex items-center">
                                <i data-lucide="terminal" class="w-5 h-5 mr-3 text-blue-400"></i>
                                <span>學術研究與產業實務緊密結合</span>
                            </li>
                            <li class="flex items-center">
                                <i data-lucide="cpu" class="w-5 h-5 mr-3 text-blue-400"></i>
                                <span>智慧工廠與自動化生產實驗室</span>
                            </li>
                            <li class="flex items-center">
                                <i data-lucide="globe" class="w-5 h-5 mr-3 text-blue-400"></i>
                                <span>推動國際交流與產學合作專案</span>
                            </li>
                        </ul>
                        <a href="https://gino171709-dai.github.io/PERWEB-/" target="_blank" class="inline-flex items-center bg-white text-blue-900 px-8 py-4 rounded-2xl font-black hover:bg-blue-50 transition transform hover:-translate-y-1 shadow-xl">
                            瀏覽系所專頁
                            <i data-lucide="external-link" class="ml-3 w-5 h-5"></i>
                        </a>
                    </div>
                    <div class="relative hidden md:block">
                        <div class="aspect-square bg-gradient-to-br from-blue-400 to-indigo-600 rounded-3xl rotate-3 shadow-2xl flex items-center justify-center p-12">
                            <i data-lucide="factory" class="w-full h-full text-white opacity-20 absolute top-0 left-0"></i>
                            <div class="text-center relative">
                                <i data-lucide="layout" class="w-32 h-32 text-white mx-auto mb-6"></i>
                                <p class="text-2xl font-black">工管網頁系統</p>
                                <p class="text-blue-100 mt-2">點擊左側按鈕進入</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 知識庫與繳交區 -->
    <section id="knowledge" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-black text-slate-900">工作研究核心領域</h2>
                <p class="mt-4 text-slate-600 text-lg">透過「方法研究」與「工作衡量」達到生產效率極大化</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-16 h-16 bg-blue-100 rounded-2xl flex items-center justify-center mb-6 text-blue-600">
                        <i data-lucide="settings-2" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">方法研究</h3>
                    <ul class="text-slate-600 space-y-4">
                        <li class="flex items-start"><span class="text-blue-500 mr-3">•</span> 流程圖與程序圖深度分析</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-3">•</span> 動作經濟原則實務應用</li>
                        <li class="flex items-start"><span class="text-blue-500 mr-3">•</span> ECRS 改善手法實踐</li>
                    </ul>
                </div>

                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-16 h-16 bg-emerald-100 rounded-2xl flex items-center justify-center mb-6 text-emerald-600">
                        <i data-lucide="clock" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">工作衡量</h3>
                    <ul class="text-slate-600 space-y-4">
                        <li class="flex items-start"><span class="text-emerald-500 mr-3">•</span> 標準工時制定與維護</li>
                        <li class="flex items-start"><span class="text-emerald-500 mr-3">•</span> 寬放時間係數評估</li>
                        <li class="flex items-start"><span class="text-emerald-500 mr-3">•</span> 工作抽查效率分析</li>
                    </ul>
                </div>

                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-16 h-16 bg-purple-100 rounded-2xl flex items-center justify-center mb-6 text-purple-600">
                        <i data-lucide="activity" class="w-8 h-8"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">生產線平衡</h3>
                    <ul class="text-slate-600 space-y-4">
                        <li class="flex items-start"><span class="text-purple-500 mr-3">•</span> 平衡率與損失率計算</li>
                        <li class="flex items-start"><span class="text-purple-500 mr-3">•</span> 瓶頸站點識別與優化</li>
                        <li class="flex items-start"><span class="text-purple-500 mr-3">•</span> 精實看板系統導入</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 作業繳交區 -->
    <section id="assignment" class="py-32 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-4xl mx-auto">
                <div class="text-center mb-16">
                    <h2 class="text-4xl font-black text-slate-900">作業與專案繳交區</h2>
                    <p class="mt-4 text-slate-600 text-lg">請選擇您的課程並上傳完整報告檔案</p>
                </div>

                <div class="bg-white rounded-[2.5rem] shadow-2xl overflow-hidden border border-white">
                    <div class="p-8 md:p-16">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-10 mb-12">
                            <div class="space-y-4">
                                <label class="block text-sm font-black text-slate-500 uppercase tracking-widest">目標課程名稱</label>
                                <select class="w-full bg-slate-50 border border-slate-200 rounded-2xl px-6 py-4 focus:ring-4 focus:ring-blue-500/10 outline-none transition appearance-none cursor-pointer">
                                    <option>工作研究：組裝作業改善報告</option>
                                    <option>生產計畫：物料需求規劃專案</option>
                                    <option>品質管理：控制圖分析作業</option>
                                    <option>自動化系統：PLC 模擬實作</option>
                                </select>
                            </div>
                            <div class="space-y-4">
                                <label class="block text-sm font-black text-slate-500 uppercase tracking-widest">目前登入學員</label>
                                <div class="flex items-center bg-blue-50/50 border border-blue-100 rounded-2xl px-6 py-4 text-blue-900 font-bold">
                                    <i data-lucide="user" class="w-5 h-5 mr-4 text-blue-400"></i>
                                    <span>戴嘉樟 (gino171709)</span>
                                </div>
                            </div>
                        </div>

                        <!-- 檔案上傳框 -->
                        <div class="file-upload-dash rounded-3xl p-16 text-center cursor-pointer mb-10 group bg-slate-50/50" onclick="document.getElementById('fileInput').click()">
                            <input type="file" id="fileInput" class="hidden" onchange="handleFileSelect(this)">
                            
                            <div id="uploadContent" class="space-y-6">
                                <div class="w-24 h-24 bg-white shadow-lg rounded-full flex items-center justify-center mx-auto group-hover:scale-110 transition duration-500">
                                    <i data-lucide="upload-cloud" class="w-12 h-12 text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="text-slate-900 font-black text-2xl">選擇作業檔案</p>
                                    <p class="text-slate-500 mt-2 font-medium">支援 PDF, Excel, PowerPoint 或 Word 格式</p>
                                </div>
                            </div>

                            <div id="fileSelected" class="hidden">
                                <div class="w-24 h-24 bg-emerald-50 rounded-full flex items-center justify-center mx-auto mb-6">
                                    <i data-lucide="file-check" class="w-12 h-12 text-emerald-500"></i>
                                </div>
                                <p id="fileNameText" class="text-slate-900 font-black text-xl mb-4"></p>
                                <button class="px-6 py-2 bg-slate-200 text-slate-700 rounded-full text-sm font-bold hover:bg-slate-300 transition" onclick="resetFile(event)">更換檔案</button>
                            </div>
                        </div>

                        <button onclick="submitAssignment()" class="w-full bg-blue-900 text-white font-black text-xl py-6 rounded-2xl hover:bg-blue-800 transition-all shadow-xl hover:shadow-blue-900/30 flex items-center justify-center space-x-4">
                            <i data-lucide="check-circle" class="w-6 h-6"></i>
                            <span>確認並送出作業</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 聯絡區 -->
    <footer id="contact" class="py-32 bg-slate-900 text-white overflow-hidden relative">
        <!-- 裝飾元素 -->
        <div class="absolute top-0 right-0 -translate-y-1/2 translate-x-1/2 w-96 h-96 bg-blue-600/10 rounded-full blur-3xl"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <h2 class="text-5xl font-black mb-10 tracking-tighter">與我聯繫</h2>
            <p class="text-slate-400 mb-16 text-xl max-w-2xl mx-auto leading-relaxed">
                正在尋找具備工管專業的實習生或合作夥伴嗎？<br>歡迎直接透過以下方式與我交流。
            </p>
            
            <div class="flex flex-col md:flex-row justify-center items-center gap-8 md:gap-16">
                <a href="mailto:gino171709@gmail.com" class="flex items-center space-x-5 hover:text-blue-400 transition group p-6 bg-white/5 rounded-3xl border border-white/10 w-full md:w-auto">
                    <div class="w-16 h-16 bg-blue-600 rounded-2xl flex items-center justify-center shadow-lg shadow-blue-600/40 group-hover:scale-110 transition">
                        <i data-lucide="mail" class="w-8 h-8"></i>
                    </div>
                    <div class="text-left">
                        <p class="text-xs font-black uppercase tracking-widest text-slate-500">Email Address</p>
                        <p class="text-xl font-bold">gino171709@gmail.com</p>
                    </div>
                </a>
                
                <div class="flex items-center space-x-5 p-6 bg-white/5 rounded-3xl border border-white/10 w-full md:w-auto">
                    <div class="w-16 h-16 bg-emerald-600 rounded-2xl flex items-center justify-center shadow-lg shadow-emerald-600/40">
                        <i data-lucide="map-pin" class="w-8 h-8"></i>
                    </div>
                    <div class="text-left">
                        <p class="text-xs font-black uppercase tracking-widest text-slate-500">Location</p>
                        <p class="text-xl font-bold">屏東縣內埔鄉</p>
                    </div>
                </div>
            </div>
            
            <div class="mt-32 pt-10 border-t border-white/10 text-slate-500 text-sm font-medium">
                <p>© 2024 戴嘉樟 | 國立屏東科技大學 工業管理系</p>
                <p class="mt-2 opacity-50 uppercase tracking-[0.2em] text-[10px]">Optimized for Industrial Efficiency</p>
            </div>
        </div>
    </footer>

    <!-- 彈窗組件 -->
    <div id="customAlert" class="fixed inset-0 bg-slate-900/80 hidden z-[100] flex items-center justify-center px-4 backdrop-blur-md">
        <div class="bg-white rounded-[2.5rem] p-12 max-w-md w-full text-center shadow-2xl scale-90 transition-transform duration-300">
            <div id="alertIcon" class="mb-8"></div>
            <h3 id="alertTitle" class="text-3xl font-black mb-4 text-slate-900"></h3>
            <p id="alertMsg" class="text-slate-600 mb-10 text-lg leading-relaxed font-medium"></p>
            <button onclick="closeAlert()" class="w-full bg-blue-600 text-white font-black py-5 rounded-2xl hover:bg-blue-700 transition shadow-lg shadow-blue-600/20 text-lg">好的，我知道了</button>
        </div>
    </div>

    <script>
        window.onload = function() {
            if (typeof lucide !== 'undefined') {
                lucide.createIcons();
            }
        };

        function handleFileSelect(input) {
            if (input.files && input.files[0]) {
                document.getElementById('uploadContent').classList.add('hidden');
                document.getElementById('fileSelected').classList.remove('hidden');
                document.getElementById('fileNameText').innerText = input.files[0].name;
                lucide.createIcons();
            }
        }

        function resetFile(e) {
            e.stopPropagation();
            const input = document.getElementById('fileInput');
            input.value = '';
            document.getElementById('uploadContent').classList.remove('hidden');
            document.getElementById('fileSelected').classList.add('hidden');
        }

        function submitAssignment() {
            const file = document.getElementById('fileInput').files[0];
            if (!file) {
                showCustomAlert('尚未選擇檔案', '請先點擊上傳區塊選擇您的報告檔案。', 'alert-circle', 'text-amber-500');
                return;
            }
            showCustomAlert('繳交成功！', '您的作業檔案「' + file.name + '」已成功傳送到繳交系統。', 'check-circle-2', 'text-emerald-500');
            resetFile({ stopPropagation: () => {} });
        }

        function showCustomAlert(title, msg, icon = 'check-circle-2', iconColor = 'text-emerald-500') {
            const alert = document.getElementById('customAlert');
            document.getElementById('alertTitle').innerText = title;
            document.getElementById('alertMsg').innerText = msg;
            const iconContainer = document.getElementById('alertIcon');
            iconContainer.innerHTML = `<i data-lucide="${icon}" class="w-24 h-24 ${iconColor} mx-auto"></i>`;
            lucide.createIcons();
            alert.classList.remove('hidden');
            setTimeout(() => {
                alert.firstElementChild.classList.remove('scale-90');
                alert.firstElementChild.classList.add('scale-100');
            }, 10);
        }

        function closeAlert() {
            const alert = document.getElementById('customAlert');
            alert.firstElementChild.classList.add('scale-90');
            alert.firstElementChild.classList.remove('scale-100');
            setTimeout(() => {
                alert.classList.add('hidden');
            }, 200);
        }
    </script>
</body>
</html>
