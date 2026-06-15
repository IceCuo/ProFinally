<!DOCTYPE html>

<html lang="zh-CN"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>狗狗日记 - DOGGY DIARY</title>
<!-- Tailwind CSS -->
<script src="js/tailwindcss.js"></script>
<!-- Iconify -->
<script src="js/iconify-icon.min.js"></script>
<style>
        @font-face{
             font-family: 'Ma Shan Zheng';
             src: url('fonts/MaShanZheng-Regular.ttf')
          format('truetype');
             font-weight: normal;
             font-style: normal;
}

        @font-face{
             font-family: 'Note Sans SC';
             src: url('fonts/NoteSansSC-Regular.ttf')
          format('truetype');
             font-weight: 400;
             font-style: normal;
}
        body {
            font-family: 'Noto Sans SC', sans-serif;
            background-color: #fcfdf7;
        }
        .font-cute {
            font-family: 'Ma Shan Zheng', cursive;
        }
        .nav-item-active {
            background-color: #60a5fa;
            color: white !important;
        }
        .hero-mask {
            background: rgba(0, 0, 0, 0.45);
            backdrop-filter: blur(4px);
        }
        .section-title-en {
            letter-spacing: 0.2em;
            color: #94a3b8;
        }
    </style>
</head>
<body class="text-slate-800 is-mb-ai-setting">
<!-- 导航栏 -->
<nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-100 shadow-sm">
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex justify-between items-center h-20">
<!-- Logo -->
<div class="flex items-center space-x-2">
<div class="w-10 h-10 bg-yellow-400 rounded-full flex items-center justify-center shadow-inner">
<iconify-icon class="text-white text-2xl" icon="ph:dog-fill"></iconify-icon>
</div>
<div class="flex flex-col">
<span class="text-xl font-bold tracking-tight text-slate-800">狗狗日记</span>
<span class="text-[10px] uppercase tracking-[0.2em] text-slate-400 font-medium">DOGGY DIARY</span>
</div>
</div>
<!-- 导航选项 -->
<div class="hidden md:flex items-center space-x-1">
<a class="px-5 py-2 rounded-full text-sm font-medium nav-item-active transition-all" href="#">首页</a>
<a class="px-5 py-2 rounded-full text-sm font-medium text-slate-600 hover:text-blue-500 transition-all" href="#">品种图鉴</a>
<a class="px-5 py-2 rounded-full text-sm font-medium text-slate-600 hover:text-blue-500 transition-all" href="#">性格特点</a>
<a class="px-5 py-2 rounded-full text-sm font-medium text-slate-600 hover:text-blue-500 transition-all" href="#">饲养指南</a>
<a class="px-5 py-2 rounded-full text-sm font-medium text-slate-600 hover:text-blue-500 transition-all" href="#">萌照集</a>
<a class="px-5 py-2 rounded-full text-sm font-medium text-slate-600 hover:text-blue-500 transition-all" href="#">留言板</a>
</div>
<!-- 移动端菜单按钮 -->
<div class="md:hidden">
<button class="text-slate-600"><iconify-icon class="text-3xl" icon="heroicons:bars-3-bottom-right"></iconify-icon></button>
</div>
</div>
</div>
</nav>
<!-- 横幅区 (Hero) -->
<header class="relative h-[600px] overflow-hidden">
<img alt="A happy Corgi running joyfully on a lush green lawn with sunlight filtering through trees" class="w-full h-full object-cover" src="images/hero-dog.jpg"/>
<div class="absolute inset-0 bg-gradient-to-r from-black/30 to-transparent"></div>
<div class="absolute top-1/2 left-8 md:left-24 -translate-y-1/2 max-w-lg">
<div class="hero-mask p-8 md:p-12 rounded-2xl border border-white/20 shadow-2xl">
<h1 class="text-white text-4xl md:text-5xl font-bold mb-6 leading-tight">和一只小狗，<br/>慢慢过日子</h1>
<p class="text-white/90 text-lg md:text-xl font-light leading-relaxed border-l-4 border-yellow-400 pl-4">
                    它们在门口等你，风里都藏着温柔——一晃神，便是四季。
                </p>
<button class="mt-8 px-8 py-3 bg-white text-blue-600 rounded-full font-bold shadow-lg hover:bg-yellow-400 hover:text-white transition-all transform hover:-translate-y-1">
                    开启治愈之旅
                </button>
</div>
</div>
</header>
<!-- 核心内容区 -->
<main class="max-w-7xl mx-auto px-4 py-20 space-y-32">
<!-- 1. 关于这些毛孩子 -->
<section class="flex flex-col md:flex-row items-center gap-12">
<div class="flex-1 space-y-6">
<div class="space-y-1">
<h2 class="text-3xl font-bold text-slate-800">关于这些毛孩子</h2>
<p class="section-title-en text-sm font-medium uppercase">ABOUT DOGS</p>
</div>
<div class="w-20 h-1.5 bg-yellow-400 rounded-full"></div>
<p class="text-slate-600 text-lg leading-loose italic">
                    “狗狗是世界上最热情的小家伙之一，会在门口等你回家，用尾巴摇出情绪；会把玩具叼到你手边，用头蹭你表达依赖；难过时会用爪子搭在你身上……”
                </p>
<p class="text-slate-500 leading-relaxed">
                    它们不仅仅是宠物，更是家庭的一员。在它们有限的生命里，把所有的爱都给了我们。
                </p>
</div>
<div class="flex-1 relative group">
<div class="absolute -inset-4 bg-blue-100 rounded-3xl -rotate-2 group-hover:rotate-0 transition-transform"></div>
<div class="relative overflow-hidden rounded-2xl shadow-xl">
<img alt="A large St. Bernard dog lying peacefully on a warm wooden floor, resting its head on paws" class="w-full h-[400px] object-cover transform group-hover:scale-105 transition-duration-700" src="images/lie-dog.jpg"/>
</div>
</div>
</section>
<!-- 2. 为什么喜欢狗 -->
<section class="space-y-12 text-center">
<div class="space-y-2">
<h2 class="text-3xl font-bold text-slate-800">为什么喜欢狗</h2>
<p class="section-title-en text-sm font-medium uppercase">WHY WE LOVE THEM</p>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
<!-- 卡片 1 -->
<div class="bg-white p-6 rounded-3xl shadow-sm hover:shadow-xl transition-all border border-slate-100 group">
<div class="aspect-square rounded-2xl overflow-hidden mb-6">
<img alt="An excited dog running towards the camera with a happy face" class="w-full h-full object-cover group-hover:scale-110 transition-all" src="images/shout-dog.jpg"/>
</div>
<h3 class="text-xl font-bold mb-3 text-blue-600">热情亲人</h3>
<p class="text-slate-500 text-sm leading-relaxed">它们总是用最热烈的摇尾巴迎接你回家，仿佛你是它们的全世界。</p>
</div>
<!-- 卡片 2 -->
<div class="bg-white p-6 rounded-3xl shadow-sm hover:shadow-xl transition-all border border-slate-100 group">
<div class="aspect-square rounded-2xl overflow-hidden mb-6">
<img alt="A dog sitting quietly next to its owner on a bench" class="w-full h-full object-cover group-hover:scale-110 transition-all" src="images/sit-dog.jpg"/>
</div>
<h3 class="text-xl font-bold mb-3 text-blue-600">忠诚陪伴</h3>
<p class="text-slate-500 text-sm leading-relaxed">无论开心还是难过，它们永远在你身边，不离不弃，跨越岁月。</p>
</div>
<!-- 卡片 3 -->
<div class="bg-white p-6 rounded-3xl shadow-sm hover:shadow-xl transition-all border border-slate-100 group">
<div class="aspect-square rounded-2xl overflow-hidden mb-6">
<img alt="Close up of a dog with gentle, soulful eyes looking up" class="w-full h-full object-cover group-hover:scale-110 transition-all" src="images/big-dog.jpg"/>
</div>
<h3 class="text-xl font-bold mb-3 text-blue-600">治愈心灵</h3>
<p class="text-slate-500 text-sm leading-relaxed">光是看着它们纯净的眼神，所有的烦恼和压力都能瞬间烟消云散。</p>
</div>
<!-- 卡片 4 -->
<div class="bg-white p-6 rounded-3xl shadow-sm hover:shadow-xl transition-all border border-slate-100 group">
<div class="aspect-square rounded-2xl overflow-hidden mb-6">
<img alt="A dog playing with a colorful ball in a park" class="w-full h-full object-cover group-hover:scale-110 transition-all" src="images/play-dog.jpg"/>
</div>
<h3 class="text-xl font-bold mb-3 text-blue-600">欢乐源泉</h3>
<p class="text-slate-500 text-sm leading-relaxed">每一个滑稽的动作、每一次笨拙的跳跃，都能逗得你开怀大笑。</p>
</div>
</div>
</section>
<!-- 3. 养狗小贴士 -->
<section class="bg-blue-50/50 rounded-[3rem] p-12 md:p-16 border border-blue-100 shadow-inner">
<div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-6">
<div class="space-y-2">
<h2 class="text-3xl font-bold text-slate-800">养狗小贴士</h2>
<p class="section-title-en text-sm font-medium uppercase">TIPS FOR DOG OWNERS</p>
</div>
<div class="text-slate-400 font-cute text-2xl">记录每一份爱心与责任...</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
<div class="flex items-start space-x-4 bg-white p-6 rounded-2xl shadow-sm">
<div class="w-12 h-12 bg-orange-100 rounded-xl flex-none flex items-center justify-center text-orange-500">
<iconify-icon class="text-2xl" icon="ph:bowl-food-fill"></iconify-icon>
</div>
<div>
<h4 class="font-bold text-slate-800 mb-1">均衡饮食</h4>
<p class="text-sm text-slate-500">选择优质狗粮，定时定量喂养，避免喂食巧克力等禁忌食物。</p>
</div>
</div>
<div class="flex items-start space-x-4 bg-white p-6 rounded-2xl shadow-sm">
<div class="w-12 h-12 bg-green-100 rounded-xl flex-none flex items-center justify-center text-green-500">
<iconify-icon class="text-2xl" icon="ph:sneaker-move-fill"></iconify-icon>
</div>
<div>
<h4 class="font-bold text-slate-800 mb-1">定期运动</h4>
<p class="text-sm text-slate-500">每天带狗狗散步至少30分钟，释放精力，保持健康的体魄。</p>
</div>
</div>
<div class="flex items-start space-x-4 bg-white p-6 rounded-2xl shadow-sm">
<div class="w-12 h-12 bg-red-100 rounded-xl flex-none flex items-center justify-center text-red-500">
<iconify-icon class="text-2xl" icon="ph:first-aid-kit-fill"></iconify-icon>
</div>
<div>
<h4 class="font-bold text-slate-800 mb-1">健康检查</h4>
<p class="text-sm text-slate-500">定期接种疫苗，进行驱虫和全面体检，预防疾病发生。</p>
</div>
</div>
<div class="flex items-start space-x-4 bg-white p-6 rounded-2xl shadow-sm">
<div class="w-12 h-12 bg-blue-100 rounded-xl flex-none flex items-center justify-center text-blue-500">
<iconify-icon class="text-2xl" icon="ph:shower-fill"></iconify-icon>
</div>
<div>
<h4 class="font-bold text-slate-800 mb-1">日常护理</h4>
<p class="text-sm text-slate-500">梳理毛发减少掉毛，定期修剪指甲和清洁牙齿，保持清爽。</p>
</div>
</div>
</div>
</section>
<!-- 4. 萌宠瞬间 -->
<section class="space-y-12">
<div class="flex justify-between items-center">
<div class="space-y-2">
<h2 class="text-3xl font-bold text-slate-800">萌宠瞬间</h2>
<p class="section-title-en text-sm font-medium uppercase">CUTE MOMENTS</p>
</div>
<a class="text-blue-500 hover:text-blue-700 font-medium flex items-center" href="#">
                    查看更多 <iconify-icon class="ml-1" icon="heroicons:arrow-right-20-solid"></iconify-icon>
</a>
</div>
<div class="columns-1 sm:columns-2 lg:columns-3 gap-6 space-y-6">
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="A cute puppy sleeping peacefully on a soft pillow" class="w-full h-auto" src="images/sleep-dog.jpg"/>
</div>
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="Two dogs playing together in the backyard" class="w-full h-auto" src="images/two-dog.jpg"/>
</div>
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="A dog wearing a cute birthday hat with a cake" class="w-full h-auto" src="images/cake-dog.jpg"/>
</div>
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="A golden retriever dog swimming in a clear blue lake" class="w-full h-auto" src="images/swim-dog.jpg"/>
</div>
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="A small dog looking out of a car window with ears flapping in the wind" class="w-full h-auto" src="images/car-dog.jpg"/>
</div>
<div class="break-inside-avoid rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition-all">
<img alt="A dog catching a frisbee in mid-air" class="w-full h-auto" src="images/jump-dog.jpg"/>
</div>
</div>
</section>
</main>
<!-- 页脚 -->
<footer class="bg-slate-900 text-slate-400 py-16">
<div class="max-w-7xl mx-auto px-4 text-center space-y-8">
<div class="flex justify-center items-center space-x-3">
<div class="w-8 h-8 bg-yellow-400 rounded-full flex items-center justify-center">
<iconify-icon class="text-white text-lg" icon="ph:dog-fill"></iconify-icon>
</div>
<span class="text-white text-xl font-bold">狗狗日记</span>
</div>
<div class="flex justify-center space-x-8 text-sm">
<a class="hover:text-white transition-colors" href="#">关于我们</a>
<a class="hover:text-white transition-colors" href="#">版权声明</a>
<a class="hover:text-white transition-colors" href="#">联系我们</a>
<a class="hover:text-white transition-colors" href="#">加入我们</a>
</div>
<div class="flex justify-center space-x-6">
<a class="w-10 h-10 rounded-full border border-slate-700 flex items-center justify-center hover:bg-slate-800 transition-all text-xl" href="#">
<iconify-icon icon="ri:wechat-fill"></iconify-icon>
</a>
<a class="w-10 h-10 rounded-full border border-slate-700 flex items-center justify-center hover:bg-slate-800 transition-all text-xl" href="#">
<iconify-icon icon="ri:weibo-fill"></iconify-icon>
</a>
<a class="w-10 h-10 rounded-full border border-slate-700 flex items-center justify-center hover:bg-slate-800 transition-all text-xl" href="#">
<iconify-icon icon="ri:instagram-line"></iconify-icon>
</a>
</div>
<div class="pt-8 border-t border-slate-800 text-xs tracking-widest uppercase">
                © 2026 狗狗日记 DOGGY DIARY | 用心记录每一个与毛孩子相伴的日子
            </div>
</div>
</footer>
</body></html>
