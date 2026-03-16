<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quản lý Proxy & UDID</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f8fafc; }
    </style>
</head>
<body class="text-gray-800">

    <nav class="bg-white shadow-md flex justify-between items-center px-8 py-4 sticky top-0 z-50">
        <div class="flex items-center space-x-2 font-bold text-xl text-blue-900">
            <i class="fas fa-shield-alt text-2xl"></i>
            <span>ProxyServerphamhoa.net</span>
        </div>
        <div class="hidden md:flex space-x-6 font-semibold text-sm">
            <a href="#" class="text-blue-600 border-b-2 border-blue-600 pb-1">TRANG CHỦ</a>
            <a href="#" class="hover:text-blue-600">DỊCH VỤ PROXY <i class="fas fa-chevron-down text-xs"></i></a>
            <a href="#" class="hover:text-blue-600">BẢNG GIÁ</a>
            <a href="#" class="hover:text-blue-600">CÔNG CỤ UDID</a>
            <a href="#" class="hover:text-blue-600">HỖ TRỢ</a>
        </div>
        <div>
            <button class="bg-blue-900 text-white px-5 py-2 rounded font-semibold hover:bg-blue-800 transition">ĐĂNG NHẬP / ĐĂNG KÝ</button>
        </div>
    </nav>

    <header class="bg-blue-900 text-white relative overflow-hidden py-16 px-8 flex justify-between items-center">
        <div class="z-10 max-w-xl">
            <h1 class="text-3xl md:text-4xl font-bold mb-2">DỊCH VỤ PROXY</h1>
            <p class="text-lg md:text-xl font-light mb-6">TỐC ĐỘ CAO - BẢO MẬT - ỔN ĐỊNH</p>
            <button class="bg-white text-blue-900 font-bold px-6 py-2 rounded shadow hover:bg-gray-100 transition">MUA NGAY</button>
        </div>
        <div class="z-10 hidden md:block">
            <i class="fas fa-server text-8xl text-blue-300 opacity-80"></i>
            <i class="fas fa-server text-8xl text-blue-300 opacity-80 ml-2"></i>
        </div>
        <div class="absolute inset-0 opacity-10 bg-[url('https://upload.wikimedia.org/wikipedia/commons/8/80/World_map_-_low_resolution.svg')] bg-cover bg-center"></div>
    </header>

    <main class="max-w-7xl mx-auto px-4 py-8">
        
        <div class="text-center mb-8">
            <h2 class="text-2xl font-bold text-gray-800 uppercase">Quản lý máy chủ Proxy & UDID</h2>
            <div class="w-24 h-1 bg-blue-900 mx-auto mt-2"></div>
        </div>

        <section class="mb-12 bg-white rounded shadow-sm border border-gray-200 overflow-hidden">
            <div class="p-4 border-b border-gray-200">
                <h3 class="font-bold text-lg text-gray-700">DANH SÁCH MÁY CHỦ PROXY</h3>
            </div>
            <div class="overflow-x-auto">
                <table class="w-full text-left text-sm">
                    <thead class="bg-blue-900 text-white">
                        <tr>
                            <th class="px-4 py-3">ID MÁY CHỦ</th>
                            <th class="px-4 py-3">VỊ TRÍ</th>
                            <th class="px-4 py-3">LOẠI PROXY</th>
                            <th class="px-4 py-3">TRẠNG THÁI</th>
                            <th class="px-4 py-3">TỐC ĐỘ</th>
                            <th class="px-4 py-3 text-center">THAO TÁC</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-gray-200">
                        <tr class="hover:bg-gray-50">
                            <td class="px-4 py-3 font-semibold">VN-HN-001</td>
                            <td class="px-4 py-3">Hà Nội, VN</td>
                            <td class="px-4 py-3">Datacenter</td>
                            <td class="px-4 py-3"><span class="text-green-500"><i class="fas fa-circle text-xs mr-1"></i>Online</span></td>
                            <td class="px-4 py-3">1 Gbps</td>
                            <td class="px-4 py-3 text-center"><button class="border border-gray-400 px-3 py-1 rounded hover:bg-gray-100">Quản lý</button></td>
                        </tr>
                        <tr class="hover:bg-gray-50 bg-gray-50/50">
                            <td class="px-4 py-3 font-semibold">US-NY-015</td>
                            <td class="px-4 py-3">New York, US</td>
                            <td class="px-4 py-3">Residential</td>
                            <td class="px-4 py-3"><span class="text-green-500"><i class="fas fa-circle text-xs mr-1"></i>Online</span></td>
                            <td class="px-4 py-3">500 Mbps</td>
                            <td class="px-4 py-3 text-center"><button class="border border-gray-400 px-3 py-1 rounded hover:bg-gray-100">Quản lý</button></td>
                        </tr>
                        <tr class="hover:bg-gray-50">
                            <td class="px-4 py-3 font-semibold">VN-HCM-003</td>
                            <td class="px-4 py-3">TP.HCM, VN</td>
                            <td class="px-4 py-3">Datacenter</td>
                            <td class="px-4 py-3"><span class="text-green-500"><i class="fas fa-circle text-xs mr-1"></i>Online</span></td>
                            <td class="px-4 py-3">800 Mbps</td>
                            <td class="px-4 py-3 text-center"><button class="border border-gray-400 px-3 py-1 rounded hover:bg-gray-100">Quản lý</button></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section>
            <h3 class="font-bold text-lg text-gray-700 mb-4 uppercase">Danh sách thiết bị UDID</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
                
                <div class="bg-white p-5 rounded-lg shadow-sm border border-gray-200">
                    <div class="flex text-gray-400 text-2xl space-x-2 mb-3">
                        <i class="fas fa-mobile-alt"></i>
                        <i class="fab fa-apple"></i>
                    </div>
                    <div class="text-xs text-gray-500 font-bold mb-1">TÊN THIẾT BỊ</div>
                    <div class="font-bold mb-2">iPhone 13 - HN</div>
                    
                    <div class="text-xs text-gray-500 font-bold mb-1">UDID</div>
                    <div class="text-sm font-mono break-words mb-2">ffffffff-1234-5678-90ab-cdef01234567</div>
                    
                    <div class="text-xs text-gray-500 font-bold mb-1">Proxy Đang Dùng</div>
                    <div class="font-semibold text-sm mb-4">VN-HN-001</div>
                    
                    <div class="flex space-x-2">
                        <button class="flex-1 bg-blue-900 text-white text-sm py-1.5 rounded hover:bg-blue-800">GÁN PROXY</button>
                        <button class="px-3 py-1.5 border border-red-500 text-red-500 text-sm rounded hover:bg-red-50">XÓA</button>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-lg shadow-sm border border-gray-200">
                    <div class="flex text-gray-400 text-2xl space-x-2 mb-3">
                        <i class="fas fa-mobile-alt"></i>
                        <i class="fab fa-android"></i>
                    </div>
                    <div class="text-xs text-gray-500 font-bold mb-1">TÊN THIẾT BỊ</div>
                    <div class="font-bold mb-2">Samsung S21 - HCM</div>
                    
                    <div class="text-xs text-gray-500 font-bold mb-1">UDID</div>
                    <div class="text-sm font-mono break-words mb-2">aaaaaa-1234-5678-90ab-cdef01234567</div>
                    
                    <div class="text-xs text-gray-500 font-bold mb-1">Proxy Đang Dùng</div>
                    <div class="font-semibold text-sm mb-4">VN-HCM-003</div>
                    
                    <div class="flex space-x-2">
                        <button class="flex-1 bg-blue-900 text-white text-sm py-1.5 rounded hover:bg-blue-800">GÁN PROXY</button>
                        <button class="px-3 py-1.5 border border-red-500 text-red-500 text-sm rounded hover:bg-red-50">XÓA</button>
                    </div>
                </div>

                </div>
        </section>

    </main>

    <footer class="bg-[#0f172a] text-gray-300 py-10 px-8 mt-12 text-sm">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-8">
            <div>
                <h4 class="text-white font-bold mb-4 uppercase">Contact</h4>
                <ul class="space-y-2">
                    <li><i class="fas fa-envelope mr-2"></i> contact@domain.vn</li>
                    <li><i class="fas fa-phone mr-2"></i> 0923.x.xxx.xxx</li>
                    <li><i class="fas fa-globe mr-2"></i> ProxyServerphamhoa.net</li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4 uppercase">Bảng giá</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Bảng giá Proxy</a></li>
                    <li><a href="#" class="hover:text-white">Công cụ UDID</a></li>
                    <li><a href="#" class="hover:text-white">Hỗ trợ</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4 uppercase">Terms of Service</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">- Điều khoản dịch vụ</a></li>
                    <li><a href="#" class="hover:text-white">- Chính sách bảo mật</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4 uppercase">Hỗ trợ</h4>
                <p>Mọi thắc mắc xin vui lòng liên hệ qua các kênh hỗ trợ của chúng tôi.</p>
            </div>
        </div>
        <div class="max-w-7xl mx-auto mt-8 pt-4 border-t border-gray-700 flex justify-between text-xs">
            <p>ProxyServerphamhoa.net - All rights reserved</p>
            <p>&copy; Copyright Vphamhoa.net</p>
        </div>
    </footer>

</body>
</html>
