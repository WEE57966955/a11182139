<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>a11182139 | NKUST 個人學修檔案</title>
    <!-- 使用 Tailwind CSS 打造現代化視覺 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700&display=swap');
        body { font-family: 'Noto Sans TC', sans-serif; scroll-behavior: smooth; }
        .gradient-bg { background: linear-gradient(135deg, #0056a4 0%, #002e5a 100%); }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- 導覽列 -->
    <nav class="fixed w-full bg-white/80 backdrop-blur-md shadow-sm z-50">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-xl font-bold text-blue-800 tracking-tighter uppercase">
                <i class="fas fa-university mr-2"></i>NKUST Portfolio
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#home" class="hover:text-blue-600 transition">首頁</a>
                <a href="#about" class="hover:text-blue-600 transition">關於我</a>
                <a href="#projects" class="hover:text-blue-600 transition">成果展示</a>
                <a href="#contact" class="hover:text-blue-600 transition">聯絡資訊</a>
            </div>
        </div>
    </nav>

    <!-- 英雄首頁區塊 (Hero Section) -->
    <header id="home" class="pt-32 pb-20 gradient-bg text-white px-6">
        <div class="max-w-4xl mx-auto text-center">
            <div class="inline-block px-4 py-1 bg-blue-500/30 rounded-full text-sm mb-6 backdrop-blur-md border border-white/20">
                國立高雄科技大學 | 智慧商務系 (或您的系所)
            </div>
            <h1 class="text-4xl md:text-6xl font-bold mb-6">您好，我是 <span class="text-yellow-400">a11182139</span></h1>
            <p class="text-xl opacity-90 mb-10 leading-relaxed max-w-2xl mx-auto">
                這是我的個人學修檔案，記錄了我在校期間的學習歷程、專業技能以及專案作品。
            </p>
            <div class="flex justify-center gap-4">
                <a href="#about" class="px-8 py-3 bg-white text-blue-900 rounded-full font-bold hover:bg-yellow-400 transition shadow-lg">開始探索</a>
                <a href="#projects" class="px-8 py-3 border border-white/50 rounded-full font-bold hover:bg-white/10 transition">查看作品</a>
            </div>
        </div>
    </header>

    <!-- 關於我 (About) -->
    <section id="about" class="py-20 px-6">
        <div class="max-w-5xl mx-auto">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="relative">
                    <div class="aspect-square bg-blue-100 rounded-2xl overflow-hidden shadow-2xl">
                        <!-- 這裡可以放您的照片 -->
                        <div class="w-full h-full flex items-center justify-center text-slate-300 italic text-sm p-8 text-center border-4 border-white">
                            <i class="fas fa-user-circle text-[120px] text-blue-200"></i>
                        </div>
                    </div>
                    <div class="absolute -bottom-6 -right-6 bg-yellow-400 p-6 rounded-2xl shadow-xl hidden md:block">
                        <p class="font-bold text-blue-900">積極學習<br>持續成長</p>
                    </div>
                </div>
                <div>
                    <h2 class="text-3xl font-bold mb-6 text-blue-900 border-l-4 border-blue-600 pl-4">關於我 / About Me</h2>
                    <p class="text-lg leading-relaxed text-slate-600 mb-6">
                        請將您 Google Sites 上的「自我介紹」內容複製並貼到這裡。您可以描述您的特質、對專業領域的熱情，以及未來的職涯目標。
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-center gap-3">
                            <span class="w-10 h-10 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center"><i class="fas fa-graduation-cap"></i></span>
                            <span class="font-medium text-slate-700 underline decoration-blue-200">國立高雄科技大學 [您的科系名稱]</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-10 h-10 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center"><i class="fas fa-id-badge"></i></span>
                            <span class="font-medium text-slate-700 italic text-sm">學號：a11182139</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 學習成果展示 (Projects) -->
    <section id="projects" class="py-20 bg-slate-100 px-6">
        <div class="max-w-5xl mx-auto text-center mb-16">
            <h2 class="text-3xl font-bold text-blue-900 mb-4 tracking-tight">成果展示 / Learning Showcase</h2>
            <p class="text-slate-500 max-w-xl mx-auto">以下是我在「316 課程」或其他學科中的代表性作品與報告。</p>
        </div>

        <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-8">
            <!-- 專案 1 -->
            <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition group overflow-hidden border border-slate-200">
                <div class="h-48 bg-slate-200 flex items-center justify-center group-hover:bg-blue-50 transition duration-500">
                    <i class="fas fa-folder-open text-4xl text-slate-400 group-hover:scale-110 transition"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-bold text-xl mb-2 text-blue-800 underline decoration-yellow-400">課程作業 A</h3>
                    <p class="text-slate-500 text-sm mb-4 leading-relaxed">在這裡填寫這份作品的內容。例如：網路行銷分析、智慧商務平台建置等。</p>
                    <a href="#" class="text-blue-600 font-bold flex items-center hover:translate-x-2 transition">查看詳情 <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>
            </div>

            <!-- 專案 2 -->
            <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition group overflow-hidden border border-slate-200">
                <div class="h-48 bg-slate-200 flex items-center justify-center group-hover:bg-blue-50 transition duration-500">
                    <i class="fas fa-project-diagram text-4xl text-slate-400 group-hover:scale-110 transition"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-bold text-xl mb-2 text-blue-800 underline decoration-yellow-400">專題作品 B</h3>
                    <p class="text-slate-500 text-sm mb-4 leading-relaxed">描述您的第二個作品亮點，這可以是期中或期末的大型報告。</p>
                    <a href="#" class="text-blue-600 font-bold flex items-center hover:translate-x-2 transition">查看詳情 <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>
            </div>

            <!-- 專案 3 -->
            <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition group overflow-hidden border border-slate-200">
                <div class="h-48 bg-slate-200 flex items-center justify-center group-hover:bg-blue-50 transition duration-500">
                    <i class="fas fa-certificate text-4xl text-slate-400 group-hover:scale-110 transition"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-bold text-xl mb-2 text-blue-800 underline decoration-yellow-400">證照與技能 C</h3>
                    <p class="text-slate-500 text-sm mb-4 leading-relaxed">列出您考取的專業證照或學習到的軟體工具技能（如 Python, SQL, Excel）。</p>
                    <a href="#" class="text-blue-600 font-bold flex items-center hover:translate-x-2 transition">查看詳情 <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- 聯絡資訊 -->
    <footer id="contact" class="py-20 gradient-bg text-white px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8 italic uppercase tracking-widest">Connect with Me</h2>
            <p class="text-white/70 mb-12">歡迎透過以下方式與我交流或提供建議！</p>
            <div class="flex justify-center gap-10 mb-16">
                <a href="mailto:a11182139@nkust.edu.tw" class="text-3xl hover:text-yellow-400 hover:scale-125 transition duration-300"><i class="fas fa-envelope"></i></a>
                <a href="#" class="text-3xl hover:text-yellow-400 hover:scale-125 transition duration-300"><i class="fab fa-github"></i></a>
                <a href="#" class="text-3xl hover:text-yellow-400 hover:scale-125 transition duration-300"><i class="fas fa-paper-plane"></i></a>
            </div>
            <div class="pt-8 border-t border-white/10 text-white/50 text-sm">
                <p>© 2024 NKUST a11182139. 
                    <br class="md:hidden"> Powered by GitHub Pages & Tailwind CSS.
                </p>
            </div>
        </div>
    </footer

</body>
</html>
