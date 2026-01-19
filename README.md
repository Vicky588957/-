</style>
</head>
<body class="bg-gray-100 font-sans text-gray-600">
    <!-- 顶部导航 -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <i class="fa-solid fa-building-columns text-primary text-xl"></i>
                <h1 class="text-lg font-semibold">供应商管理系统</h1>
            </div>
            <div class="flex items-center gap-4">
                <div class="relative hidden md:block">
                    <input type="text" placeholder="全局搜索..." class="pl-8 pr-4 py-1.5 rounded border border-gray-200 focus:outline-none focus:ring-2 focus:ring-primary/20 focus:border-primary text-sm w-48">
                    <i class="fa-solid fa-search absolute left-3 top-1/2 -translate-y-1/2 text-gray-400"></i>
                </div>
                <div class="flex items-center gap-2">
                    <img src="https://picsum.photos/32/32" alt="用户头像" class="w-8 h-8 rounded-full object-cover">
                    <span class="text-sm">系统管理员</span>
                </div>
            </div>
        </div>
    </header>

    <!-- 面包屑 -->
    <div class="container mx-auto px-4 py-3">
        <nav class="flex text-sm text-gray-400" aria-label="Breadcrumb">
            <ol class="inline-flex items-center space-x-1 md:space-x-3">
                <li><a href="#" class="hover:text-primary">首页</a></li>
                <li><i class="fa-solid fa-chevron-right mx-2 text-xs"></i></li>
                <li><a href="#" class="hover:text-primary">供应商管理</a></li>
                <li><i class="fa-solid fa-chevron-right mx-2 text-xs"></i></li>
                <li class="text-gray-600 font-medium">新增供应商</li>
            </ol>
        </nav>
    </div>

<!-- 主内容区 -->
<main class="container mx-auto px-4 py-6">
<div class="form-container">
@@ -615,13 +582,6 @@ <h2 class="text-lg font-semibold">新增供应商</h2>
</form>
</div>
</main>

    <footer class="bg-white border-t border-gray-200 py-4 mt-6">
        <div class="container mx-auto px-4 text-center text-sm text-gray-400">
            © 2026 供应商管理系统 - 版权所有
        </div>
    </footer>

<script>
// 1. 交易类型联动：服务商显示英文名称输入框
const tradeTypeSelect = document.getElementById('supplierTradeType');
